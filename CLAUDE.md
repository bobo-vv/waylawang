# เวลาว่าง Waylawang — Project Notes

## เว็บไซต์
- **ไฟล์หลัก:** `index.html`
- **GitHub:** https://github.com/bobo-vv/waylawang
- **Deploy:** Render.com (static site)

## Deploy ขึ้น Render
1. ไปที่ https://render.com → **New → Static Site**
2. Connect GitHub repo: `bobo-vv/waylawang`
3. ตั้งค่า:
   - **Branch:** `main`
   - **Publish directory:** `.` (root)
   - **Build command:** *(ว่างเปล่า — ไม่ต้อง build)*
4. กด **Create Static Site** → Render จะ deploy ให้อัตโนมัติ

## อัพเดทเว็บในอนาคต
เปิด terminal หรือ Cowork แล้วรันคำสั่งนี้:
```bash
cd /tmp/waylawang_deploy
# แก้ไขไฟล์ที่ต้องการ แล้ว:
git add .
git commit -m "อธิบายการแก้ไข"
git push
```
Render จะ deploy ใหม่อัตโนมัติทันทีที่ push

## ข้อมูลร้าน
- **ชื่อ:** เวลาว่าง (Waylawang Coffee-Baked-Craft)
- **ที่ตั้ง:** โครงการดิสทริค รามอินทรา-จตุโชติ, คลองสามวา, กรุงเทพฯ
- **พิกัด:** 13.8908155, 100.6918139
- **Google Maps:** https://maps.app.goo.gl/Sy7RSwss2g1Fm4M79
- **Facebook:** https://www.facebook.com/waylawangcafe
- **เวลาเปิด:** จันทร์–ศุกร์ 08:00–18:00 / เสาร์–อาทิตย์ 08:00–19:00

## Design Tokens (Tiago-inspired)
- Background: `#fffefa`
- Navy: `#1e3e76`
- Pink banner: `#edb5cc`
- Gold accent: `#c9a84c`
- Fonts: Cormorant Garamond (headings) + Sarabun (body)

## รูปภาพสำคัญ
- Hero: `486167648_3149288460548520_4751146448667309177_n.jpg` (barista latte art)
- Logo: `281799.jpg`
