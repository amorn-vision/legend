# ลิงก์สั้นหน้าลงทะเบียนแขก BNI Legend Chapter

เปิด [https://amorn-vision.github.io/legend/](https://amorn-vision.github.io/legend/) แล้วระบบจะพาไปหน้าลงทะเบียนสาธารณะทันที

ลิงก์นี้เป็นหน้าที่พาไปอย่างเดียว ไม่มีฟอร์มในตัว เพราะหน้าลงทะเบียนอยู่ที่ Google Apps Script ซึ่งเปิดในกรอบ (iframe) ไม่ได้ดี

ถ้า Deploy สาธารณะของ Apps Script เปลี่ยนรหัสลิงก์ (`/macros/s/.../exec`) ให้แก้ปลายทางใน `index.html` แล้วอัปโหลดขึ้น repo นี้ใหม่ ถ้าเป็นไปได้ให้ใช้ deployment เดิม เพื่อไม่ต้องเปลี่ยนลิงก์สั้น
