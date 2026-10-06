# Meeple Score

เว็บนับคะแนนแบบออฟไลน์สำหรับใช้คู่กับบอร์ดเกมบน iPad

## ฟีเจอร์เวอร์ชัน 1
- ผู้เล่น 2–6 คน
- ตั้งชื่อและเลือกสีผู้เล่น
- ปุ่ม -1, +1, +2, +5, +10
- กรอกคะแนนจำนวนอื่นได้ เช่น +12 หรือ -3
- Undo การเปลี่ยนคะแนนล่าสุด
- History ย้อนหลัง
- บันทึกอัตโนมัติด้วย localStorage
- PWA / Add to Home Screen
- Service Worker สำหรับใช้งานออฟไลน์หลังจากโหลดเว็บสำเร็จครั้งแรก

## ทดลองบนคอม
เนื่องจาก PWA/Service Worker ต้องเปิดผ่าน HTTP/HTTPS ไม่ควรดับเบิลคลิก `index.html` หากต้องการทดสอบโหมดออฟไลน์

วิธีง่ายเมื่อมี Python:

```bash
python -m http.server 8000
```

แล้วเปิด http://localhost:8000

## Deploy ฟรี
สามารถอัปโหลดโฟลเดอร์นี้ขึ้น GitHub Pages, Cloudflare Pages, Netlify หรือ Vercel ได้
