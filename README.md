# ราคาวัตถุดิบเกม & คำนวณต้นทุนอาวุธ

เว็บหน้าเดียว (`index.html`) เผยแพร่ผ่าน GitHub Pages

## ตั้งค่าครั้งแรก
1. สร้าง repo ใหม่บน GitHub แล้วอัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (รวม `.github/`)
2. ไปที่ **Settings → Pages → Build and deployment → Source** เลือก **GitHub Actions**
3. รอ Actions ทำงานเสร็จ เว็บจะอยู่ที่ `https://<ชื่อผู้ใช้>.github.io/<ชื่อ repo>/`

## อัปเดตเมื่อมีไฟล์ index ใหม่
**วิธี A (ง่ายสุด):** ลากไฟล์ใหม่ไปวางในโฟลเดอร์ `incoming/` บนเว็บ GitHub (Add file → Upload files) → Commit
ชื่อไฟล์อะไรก็ได้ เช่น `index (5).html` ระบบจะแทนที่ `index.html` และ deploy ให้เอง

**วิธี B:** อัปโหลดทับ `index.html` ตรง ๆ → Commit ระบบ deploy ให้เอง

ใช้เวลาประมาณ 1 นาทีหลัง commit
