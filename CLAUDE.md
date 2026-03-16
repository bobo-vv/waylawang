# เวลาว่าง Waylawang — Project Notes

## เว็บไซต์
- **ไฟล์หลัก:** `index.html`
- **GitHub:** https://github.com/bobo-vv/waylawang
- **Deploy:** Render.com (static site, auto-deploy จาก GitHub)

## Deploy ขึ้น Render
1. ไปที่ https://render.com → **New → Static Site**
2. Connect GitHub repo: `bobo-vv/waylawang`
3. ตั้งค่า:
   - **Branch:** `main`
   - **Publish directory:** `.` (root)
   - **Build command:** *(ว่างเปล่า — ไม่ต้อง build)*
4. กด **Create Static Site** → Render จะ deploy ให้อัตโนมัติ

## อัพเดทเว็บในอนาคต
เปิด Cowork แล้วบอก Claude ว่าอยากแก้อะไร จะแก้ไฟล์และ push ให้อัตโนมัติ
หรือจะรันเองใน terminal:
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
- **TikTok:** https://www.tiktok.com/@waylawangcafe
- **เวลาเปิด:** จ–ศ 08:00–18:00 / ส–อา 08:30–18:00

## Delivery
- **LINE MAN:** https://wongn.ai/228qJH
- **Grab Food:** https://r.grab.com/g/6-20260317_010131_d8e3275d9cc741bfafbf117a6583accf_MEXMPS-3-C353GAEUARMDVN

## Design Tokens (Tiago-inspired)
- Background: `#fffefa`
- Navy: `#1e3e76`
- Pink banner: `#edb5cc`
- Gold accent: `#c9a84c`
- Fonts: Cormorant Garamond (headings) + Sarabun (body)

## รูปภาพสำคัญ
- Hero: `486167648_3149288460548520_4751146448667309177_n.jpg` (barista latte art)
- Logo: `281799.jpg`

## สิ่งที่ทำไปแล้ว
- ✅ Meta tags + Schema.org JSON-LD (SEO/AI discoverability)
- ✅ Open Graph (share บน Facebook/Line สวย)
- ✅ Google Maps embed พิกัดถูกต้อง
- ✅ Delivery section (LINE MAN + Grab)
- ✅ TikTok link (nav, contact, footer)
- ✅ Mobile responsive + hamburger menu
- ✅ Announcement bar แบบ marquee scroll
- ✅ Blog 3 บทความ (SEO)
- ✅ Deploy บน Render.com ผ่าน GitHub
