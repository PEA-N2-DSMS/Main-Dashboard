# PEA N2 · DSMS Portal

เว็บหลักสำหรับเข้าถึงเว็บไซต์ระบบงานทั้ง 5 เว็บไซต์ ออกแบบให้รองรับคอมพิวเตอร์และมือถือ โดยใช้ HTML และ CSS ไม่มีขั้นตอน build หรือ dependency ที่ต้องติดตั้ง

## เปิดใช้งานในเครื่องพัฒนา

```sh
cd /workspace/Main-Dashboard
python3 -m http.server 8000 --bind 0.0.0.0
```

ตรวจสอบด้วย `curl --fail http://127.0.0.1:8000/` และ `curl --fail http://127.0.0.1:8000/assets/style.css`

## GitHub Pages

หลังนำไฟล์ขึ้น repository ให้ตั้งค่า Settings → Pages → Deploy from a branch → `main` / `(root)` หน้าเว็บใช้ relative paths จึงรองรับการเผยแพร่ที่ `/Main-Dashboard/`

การ์ดทุกใบเปิดเว็บไซต์ปลายทางในแท็บใหม่ ไม่มีระบบล็อกอินหรือการเก็บข้อมูลส่วนบุคคล ฟอนต์ Noto Sans Thai โหลดจาก Google Fonts และมี Tahoma / sans-serif เป็นฟอนต์สำรอง
