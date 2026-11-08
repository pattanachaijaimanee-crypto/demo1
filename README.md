# DailyPulse News

Progressive Web App (PWA) สำหรับอ่านข่าว 5 หมวดหมู่ รองรับภาษาไทย อังกฤษ และจีน

## เปิดใช้งานผ่าน GitHub Pages

1. เปิดแท็บ **Settings** ของ repository นี้
2. เลือก **Pages** ในเมนูด้านซ้าย
3. ในส่วน **Build and deployment** เลือก **Deploy from a branch**
4. เลือก branch **main** และ folder **/(root)** แล้วกด **Save**
5. รอ GitHub Pages เผยแพร่เว็บไซต์ จากนั้นเปิด `https://pattanachaijaimanee-crypto.github.io/demo1/`

## ติดตั้งเป็นแอป

เปิดเว็บไซต์ผ่าน HTTPS บน Chrome หรือ Edge แล้วเลือก **Install app** หรือ **Add to Home Screen** จากเมนูเบราว์เซอร์

## ไฟล์หลัก

- `index.html` — หน้าแอป DailyPulse News
- `manifest.json` — ชื่อและการตั้งค่า PWA
- `sw.js` — Service worker สำหรับการแคชและการทำงานออฟไลน์บางส่วน

หมายเหตุ: การดึงข่าวสดต้องใช้อินเทอร์เน็ตและบริการ RSS ภายนอก ส่วนข่าวสำรองแสดงได้เมื่อดึงข้อมูลสดไม่สำเร็จ.
