Virtual Memory and TLB Simulator
พัฒนาโดย: 
นางสาววิลาวัณย์  เที่ยนเฮง   6630300769
นางสาวชุัชฎาภรณ์ ช่างสุวรรณ์ 6630300173
นายจิรายุส เมียดคง         6630300122
นายกิตติธัช เลี้ยงรอด        6630300076
วิชา: Computer Architecture and Organization

📌 ภาพรวมโปรเจ็ค
โปรแกรมจำลองการทำงานของ หน่วยความจำเสมือน (Virtual Memory) และ Translation Lookaside Buffer (TLB) 
ที่พัฒนาด้วย React และ Tailwind CSS เพื่อช่วยให้เข้าใจกลไกการแปลงที่อยู่เสมือน (Virtual Address) 
เป็นที่อยู่ทางกายภาพ (Physical Address)

✨ คุณสมบัติหลัก
จำลองกระบวนการแปลที่อยู่อัตโนมัติ
แสดงผลลัพธ์แบบ Real-time
ปรับแต่งพารามิเตอร์ระบบ
เปลี่ยนอัลกอริทึมการแทนที่หน้า (FIFO, LRU, Optimal)
ปรับขนาด TLB และ Page Table
อธิบายแนวคิดด้วยตัวอย่างเข้าใจง่าย

📚 ทฤษฎีที่เกี่ยวข้อง
โปรเจ็คนี้ประยุกต์จากเนื้อหาใน Chapter 8: Virtual Machines and Virtual Memory โดยเฉพาะในส่วนของ:
การทำงานของ TLB (หน้า 40-44)
กลไก Page Table และ Address Translation (หน้า 28-32)
การจัดการ Page Fault (หน้า 33-37)

🛠️ การติดตั้ง
โคลน Repository:
git clone https://github.com/stamppppps/projectcomach-2.git

ติดตั้ง dependencies:
npm install

รันโปรเจ็ค:
npm start

🖥️ วิธีการใช้งาน
หน้าแรก: เลือกเข้าสู่โหมดต่างๆ

Start Simulation: เริ่มการจำลอง

Configuration: ตั้งค่าพารามิเตอร์ระบบ

About: เรียนรู้แนวคิด

หน้าตั้งค่า:
- เลือกอัลกอริทึม: FIFO, LRU หรือ Optimal
- กำหนดขนาด TLB Cache (ค่าเริ่มต้น: 4 entries)
- กำหนดขนาด Page Table (ค่าเริ่มต้น: 16 entries)

หน้าจำลองการทำงาน:
1. ป้อน Virtual Address ในรูปแบบ Hexadecimal (เช่น 0xABCD)
2. กดปุ่ม "Translate"
3. ดูผลลัพธ์การทำงาน:
   - TLB Hit/Miss
   - Page Fault Status
   - Physical Address ที่คำนวณได้

