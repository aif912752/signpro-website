# SignPro Website 🎨

เว็บไซต์ร้านผลิตและติดตั้งป้ายโฆษณาครบวงจร - สำหรับ SignPro

## 📋 เกี่ยวกับโปรเจกต์

เว็บไซต์ SignPro เป็นเว็บไซต์สแตติก single-page application (SPA) ที่ออกแบบมาเพื่อจัดแสดงบริการผลิตและติดตั้งป้ายโฆษณาครบวงจร ทั้งสติ๊กเกอร์, ป้ายไฟ LED, ไวนิล Inkjet, และงานออกบูธ/อีเวนต์

## ✨ ฟีเจอร์หลัก

- **🎨 ดีไซน์ทันสมัย** - Dark theme สไตล์โปร พร้อม custom cursor และ animations
- **📱 Responsive** - รองรับทั้ง Desktop และ Mobile
- **⚡ Performance** - CSS/JS Minified โหลดเร็ว
- **🔄 Page Navigation** - ระบบเปลี่ยนหน้าโดยไม่ต้องโหลดใหม่ (SPA)
- **✨ Scroll Animations** - Animation effects เมื่อ scroll
- **📊 Counter Animations** - ตัวนับอัตโนมัติเมื่อเลื่อนมาเจอ
- **💬 FAQ Accordion** - คำถามที่พบบ่อยพร้อม animation
- **📝 Contact Form** - ฟอร์มติดต่อสอบถามราคา

## 🛠️ เทคโนโลยีที่ใช้

- **HTML5** - โครงสร้างหน้าเว็บ
- **CSS3** - การตกแต่งและ animations
- **Vanilla JavaScript** - ฟังก์ชันการทำงานโดยไม่ใช้ framework
- **Google Fonts** - Prompt & Sarabun fonts

## 📁 โครงสร้างไฟล์

```
signpro-website/
├── index.html          # หน้าเว็บหลัก
├── styles.min.css      # CSS ที่ minified แล้ว
├── script.min.js       # JavaScript ที่ minified แล้ว
└── README.md           # ไฟล์นี้
```

## 🚀 วิธีติดตั้งและใช้งาน

### วิธีที่ 1: เปิดไฟล์โดยตรง
1. Download ไฟล์ทั้งหมด
2. ดับเบิลคลิกที่ `index.html`
3. เว็บจะเปิดขึ้นใน browser

### วิธีที่ 2: ใช้ Local Server (แนะนำ)
```bash
# ใช้ Python 3
python -m http.server 8000

# ใช้ Node.js (npx)
npx serve

# ใช้ PHP
php -S localhost:8000
```
แล้วเปิด browser ที่ `http://localhost:8000`

### วิธีที่ 3: ใช้ VS Code Live Server
1. ติดตั้ง Extension "Live Server" ใน VS Code
2. คลิกขวาที่ `index.html`
3. เลือก "Open with Live Server"

## 📄 หน้าเว็บ (Pages)

เว็บไซต์มี 4 หน้าหลัก:

1. **หน้าแรก (Home)**
   - Hero section พร้อม animation
   - Statistics counters
   - Services preview
   - Why us section
   - Customer testimonials
   - CTA banner

2. **บริการ (Services)**
   - รายละเอียดบริการทั้งหมด
   - Service cards พร้อม visual
   - Pricing plans

3. **เกี่ยวกับเรา (About)**
   - Company story
   - Core values
   - Team members
   - Company timeline

4. **ติดต่อเรา (Contact)**
   - Contact form
   - Contact information
   - Opening hours
   - FAQ section

## ⚙️ การปรับแต่ง

### เปลี่ยนสีและสไตล์
แก้ไฟล์ `styles.min.css` - CSS Variables อยู่ที่บรรทัดแรก:
```css
:root {
  --black: #090909;
  --white: #f4efe7;
  --orange: #ff4500;
  --yellow: #ffd000;
  /* ... */
}
```

### แก้ไขข้อมูลติดต่อ
ค้นหาใน `index.html`:
- LINE: @signpro
- Tel: 02-XXX-XXXX
- Email: hello@signpro.co.th

### ปรับแต่ง JavaScript
แก้ไฟล์ `script.min.js`:
- Animation timing
- Scroll behavior
- Form handling

## 🎨 Customization

### เปลี่ยน Fonts
แก้ Google Fonts URL ใน `<head>`:
```html
<link href="https://fonts.googleapis.com/css2?family=Prompt:wght@300;400;600;700;900&family=Sarabun:wght@300;400;600&display=swap" rel="stylesheet">
```

### เพิ่ม/ลบ หน้า
1. เพิ่ม `<div class="page" id="page-name">` ใน HTML
2. เพิ่ม navigation link
3. เพิ่ม CSS/JS ตามต้องการ

### ปรับแต่ง Animations
CSS Animations อยู่ใน `styles.min.css`:
- `@keyframes fadeUp`
- `@keyframes fadeIn`
- `@keyframes float`
- `@keyframes pageIn`

## 🌐 Deployment

### GitHub Pages
1. Push โค้ดขึ้น GitHub
2. ไปที่ Settings → Pages
3. เลือก branch: `main` หรือ `master`
4. Save แล้วรอสักครู่

### Netlify
1. Login ด้วย GitHub
2. Drag & drop โฟลเดอร์โปรเจกต์
3. เสร็จแล้ว!

### Vercel
```bash
npm i -g vercel
vercel
```

## 📱 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 🔧 Performance

- **Lighthouse Score**: 90+ (Performance)
- **First Contentful Paint**: < 1.5s
- **Time to Interactive**: < 3s
- **Total Size**: ~93 KB (minified)

## 📝 License

ใช้ส่วนตัว/ธุรกิจได้ฟรี แต่ห้ามนำไปขายต่อ

## 🤝 Contributing

1. Fork โปรเจกต์
2. สร้าง branch (`git checkout -b feature/AmazingFeature`)
3. Commit (`git commit -m 'Add some AmazingFeature'`)
4. Push ไป branch (`git push origin feature/AmazingFeature`)
5. เปิด Pull Request

## 📧 ติดต่อ

หากมีข้อสงสัยหรือต้องการติดต่อ สามารถติดต่อได้ที่:
- Email: hello@signpro.co.th
- LINE: @signpro
- Tel: 02-XXX-XXXX

---

Made with ❤️ for SignPro
