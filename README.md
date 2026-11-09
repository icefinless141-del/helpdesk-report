📋 ระบบบันทึกงานรายวัน (Helpdesk Daily Report PWA)
เว็บแอปพลิเคชันรูปแบบ Progressive Web App (PWA) ที่ออกแบบมาสำหรับใช้งานบนมือถือ รองรับการเพิ่มลงหน้าจอหลัก (Add to Home Screen) เพื่อบันทึกงาน Helpdesk และอัปโหลดรูปภาพหลักฐานเข้าสู่ Google Drive และ Google Sheets ส่วนตัวของแต่ละบุคคลแบบอัตโนมัติผ่าน Google Apps Script Webhook

🚀 ฟังก์ชันหลักของระบบ (Features)
Multi-User Routing System (ระบบแยกผู้ใช้งาน):

รองรับการใช้งานหลายคนผ่านหน้าเว็บลิงก์เดียวกัน

ระบบจะสลับ Webhook URL อัตโนมัติตามชื่อผู้ใช้งานที่เลือกตอน Login เพื่อแยกเก็บข้อมูลลง Google Drive / Sheets ของแต่ละคนโดยเฉพาะ

Smart Ticket ID Generation (ระบบสร้างรหัส Ticket อัตโนมัติ):

สร้างคำนำหน้า Prefix อัตโนมัติตามวันที่เลือกในฟอร์ม ในรูปแบบ BK-YYYYMMDD-

เปิดให้ผู้ใช้งานกรอกเฉพาะเลข 4 หลักท้าย (เช่น 8792 จะถูกรวมร่างเป็น BK-20261109-8792 อัตโนมัติ)

รองรับกรณีไม่มีเลข Ticket สามารถเว้นว่างไว้ได้ ระบบจะบันทึกเป็นขีดเดี่ยว (-) ให้เรียบร้อย

Mobile-First Responsive UI:

ดีไซน์ปุ่ม ช่องกรอกข้อมูล และเลย์เอาต์ให้ใหญ่พิเศษ เหมาะสำหรับการใช้งานและกดจิ้มบนสมาร์ทโฟน

Multi-Image Evidence Upload (แนบรูปภาพหลักฐาน):

รองรับการอัปโหลดรูปภาพหลายรูปพร้อมกัน แปลงไฟล์เป็น Base64 และส่งตรงเข้าโฟลเดอร์บน Google Drive รายวัน

PWA (Progressive Web App) Support:

สามารถกด "เพิ่มลงในหน้าจอหลัก" (Add to Home Screen) บนมือถือ เพื่อใช้งานได้เหมือนแอปพลิเคชันทั่วไปแบบเต็มจอ

⚙️ สถาปัตยกรรมระบบ (Tech Stack)
Frontend: HTML5, CSS3, JavaScript (Vanilla JS), GitHub Pages

Backend: Google Apps Script (Webhook)

Database / Storage: Google Sheets & Google Drive
