# Sweet Dreams Bakery - เว็บไซต์ร้านเบเกอรี่

![Sweet Dreams Bakery Logo](https://img.shields.io/badge/Sweet%20Dreams-Bakery-gold?style=for-the-badge&logo=cake)

## 📖 เกี่ยวกับโปรเจกต์

Sweet Dreams Bakery เป็นเว็บไซต์ร้านเบเกอรี่ที่ออกแบบมาเพื่อธุรกิจขนาดเล็ก ที่ลูกค้าทั่วไปมักจะจ้างฟรีแลนซ์สร้าง เว็บไซต์นี้มีการออกแบบที่สวยงาม ใช้งานง่าย และรองรับการใช้งานบนอุปกรณ์ต่างๆ

## ✨ ฟีเจอร์หลัก

### 🏠 หน้าแรก (Home)
- Hero section ที่สวยงามพร้อม call-to-action
- การออกแบบที่ทันสมัยและน่าสนใจ
- แสดงชื่อร้านและสโลแกนอย่างโดดเด่น

### 🛍️ สินค้าของเรา (Products)
- แสดงสินค้าแนะนำในรูปแบบการ์ด
- รายการสินค้า: ครัวซองต์, คัพเค้ก, เค้กงานแต่ง, ขนมปัง, คุกกี้, เพสทรี่
- แสดงราคาและรายละเอียดสินค้า

### 👥 เกี่ยวกับเรา (About)
- เล่าเรื่องราวร้าน
- จุดเด่นและคุณภาพของสินค้า
- ความเชี่ยวชาญของทีมงาน

### 🖼️ แกลลอรี่ (Gallery)
- แสดงภาพผลงานและบรรยากาศร้าน
- Lightbox effect สำหรับดูภาพขยาย
- ภาพคุณภาพสูงจาก Unsplash

### 📞 ติดต่อเรา (Contact)
- ข้อมูลติดต่อครบถ้วน (ที่อยู่, เบอร์โทร, อีเมล, เวลาทำการ)
- แบบฟอร์มติดต่อพร้อม validation
- ลิงค์ Social Media
- Google Maps (แผนที่)

## 🛠️ เทคโนโลยีที่ใช้

- **HTML5**: โครงสร้างหน้าเว็บ
- **CSS3**: การออกแบบและ responsive design
- **JavaScript (Vanilla)**: การทำงานแบบ interactive
- **Google Fonts**: ฟอนต์ที่สวยงาม (Playfair Display, Inter)
- **Font Awesome**: ไอคอน
- **Unsplash**: รูปภาพคุณภาพสูง

## 📱 Responsive Design

เว็บไซต์รองรับการใช้งานบนอุปกรณ์ทุกขนาด:
- 📱 Mobile (320px - 768px)
- 📱 Tablet (768px - 992px)
- 💻 Desktop (992px ขึ้นไป)

## 🚀 ฟีเจอร์เพิ่มเติม

### การทำงานแบบ Interactive
- ✅ Smooth scrolling navigation
- ✅ Mobile-friendly hamburger menu
- ✅ Scroll-to-top button
- ✅ Active link highlighting
- ✅ Form validation
- ✅ Image lightbox
- ✅ Loading animations
- ✅ Hover effects

### การเพิ่มประสิทธิภาพ
- ✅ Lazy loading สำหรับรูปภาพ
- ✅ Debounced scroll events
- ✅ Optimized animations
- ✅ Fast loading times

### Accessibility
- ✅ Keyboard navigation
- ✅ Screen reader friendly
- ✅ Skip navigation link
- ✅ Proper ARIA labels

## 📁 โครงสร้างไฟล์

```
sweet-dreams-bakery/
├── index.html              # หน้าหลัก
├── css/
│   └── style.css          # ไฟล์ CSS หลัก
├── js/
│   └── script.js          # ไฟล์ JavaScript หลัก
├── images/                # โฟลเดอร์รูปภาพ (placeholder)
└── README.md             # ไฟล์อธิบายโปรเจกต์
```

## 🎨 Color Palette

- **Primary Color**: #D4AF37 (ทอง)
- **Secondary Color**: #8B4513 (น้าตาล)
- **Background**: #FEF9F3 (ครีมอ่อน)
- **Text**: #2D1810 (น้าตาลเข้म)
- **Accent**: #5A4A3A (น้าตาลกลาง)

## 🌟 การใช้งาน

1. **เปิดไฟล์**: เปิด `index.html` ในเว็บเบราว์เซอร์
2. **Navigation**: ใช้เมนูด้านบนเพื่อนำทางไปยังหน้าต่างๆ
3. **Mobile**: กดปุ่ม hamburger menu บนอุปกรณ์มือถือ
4. **Gallery**: คลิกที่รูปภาพเพื่อดูแบบขยาย
5. **Contact**: กรอกแบบฟอร์มเพื่อติดต่อร้าน

## 🔧 การปรับแต่ง

### เปลี่ยนสีธีม
แก้ไขค่าใน CSS Variables ที่ไฟล์ `css/style.css`:

```css
:root {
  --primary-color: #D4AF37;     /* สีหลัก */
  --secondary-color: #8B4513;   /* สีรอง */
  --title-color: #2D1810;       /* สีหัวข้อ */
  /* ... */
}
```

### เปลี่ยนเนื้อหา
แก้ไขข้อความใน `index.html`:
- ชื่อร้าน
- ข้อมูลติดต่อ
- รายละเอียดสินค้า
- เรื่องราวร้าน

### เพิ่มสินค้า
เพิ่ม product card ใหม่ในส่วน products section:

```html
<article class="product-card">
    <div class="product-image">
        <img src="รูปภาพ" alt="ชื่อสินค้า" class="product-img">
    </div>
    <div class="product-data">
        <h3 class="product-title">ชื่อสินค้า</h3>
        <p class="product-description">รายละเอียด</p>
        <span class="product-price">ราคา</span>
    </div>
</article>
```

## 📈 SEO Ready

- ✅ Meta tags ครบถ้วน
- ✅ Semantic HTML
- ✅ Image alt attributes
- ✅ Structured content
- ✅ Fast loading speed

## 🌐 การใช้งานจริง

เว็บไซต์นี้เหมาะสำหรับ:
- 🧁 ร้านเบเกอรี่
- 🍰 ร้านเค้ก
- 🍞 ร้านขนมปัง
- 🍪 ร้านขนม
- ☕ คาเฟ่ที่มีเบเกอรี่

## 💡 การพัฒนาต่อ

สิ่งที่สามารถเพิ่มเติมได้:
- 🛒 ระบบสั่งซื้อออนไลน์
- 💳 ระบบชำระเงิน
- 📱 Mobile app
- 🔐 ระบบสมาชิก
- 📊 Analytics
- 🤖 Chatbot
- 📧 Email marketing integration

## 📞 ติดต่อนักพัฒนา

หากต้องการปรับแต่งหรือพัฒนาเพิ่มเติม สามารถติดต่อได้ที่:

- 📧 Email: developer@example.com
- 📱 Phone: 02-XXX-XXXX
- 🌐 Website: www.developer.com

## 📄 License

โปรเจกต์นี้สร้างขึ้นเพื่อการใช้งานทางธุรกิจ สามารถนำไปใช้และปรับแต่งได้ตามต้องการ

---

**Sweet Dreams Bakery** - Where Every Bite is a Sweet Dream 🍰✨

*สร้างด้วยความใส่ใจสำหรับธุรกิจขนาดเล็ก*