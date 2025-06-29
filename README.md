# 🛡️ Portfolio Sinh viên An toàn Thông tin

Portfolio chuyên nghiệp dành cho sinh viên ngành An toàn Thông tin với thiết kế hiện đại và tính năng tương tác đa dạng.

## ✨ Tính năng

- **Thiết kế Responsive**: Tương thích hoàn hảo trên mọi thiết bị
- **Animations mượt mà**: Hiệu ứng chuyển tiếp và animation chuyên nghiệp
- **Navigation thông minh**: Thanh điều hướng sticky với hiệu ứng scroll
- **Skill bars động**: Thanh kỹ năng với animation theo thời gian thực
- **Contact form**: Form liên hệ với validation và thông báo
- **Dark theme**: Giao diện tối chuyên nghiệp phù hợp với theme cybersecurity

## 🚀 Cấu trúc dự án

```
portfolio/
├── index.html              # Trang chính
├── styles/
│   └── main.css            # CSS styling chính
├── js/
│   └── script.js           # JavaScript tương tác
├── assets/                 # Thư mục chứa hình ảnh (nếu có)
└── README.md              # Hướng dẫn dự án
```

## 🛠️ Công nghệ sử dụng

- **HTML5**: Cấu trúc semantic và accessibility
- **CSS3**: 
  - CSS Grid & Flexbox cho layout
  - CSS Variables cho theme management
  - Animations và transitions
  - Responsive design với media queries
- **JavaScript (ES6+)**:
  - Intersection Observer API
  - Smooth scrolling
  - Form validation
  - Dynamic animations
- **Font Awesome**: Icons chuyên nghiệp
- **Google Fonts**: Typography (Poppins)

## 📱 Responsive Breakpoints

- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px  
- **Mobile**: < 768px

## 🎨 Color Scheme (Cybersecurity Theme)

```css
--primary-color: #0f172a      /* Slate 900 */
--secondary-color: #1e293b    /* Slate 800 */
--accent-color: #3b82f6       /* Blue 500 */
--text-primary: #f8fafc       /* Slate 50 */
--text-secondary: #cbd5e1     /* Slate 300 */
```

## 📂 Các section chính

### 1. **Navigation**
- Logo với icon shield
- Menu responsive với hamburger trên mobile
- Active link highlighting
- Smooth scroll navigation

### 2. **Hero Section**
- Typing animation cho title
- Security-themed animation
- Call-to-action buttons
- Gradient background

### 3. **About Section**
- Thông tin cá nhân
- Stats counter animation
- Profile image placeholder

### 4. **Skills Section**
- 4 categories: Network Security, Penetration Testing, Programming, Digital Forensics
- Animated skill bars với percentage
- Hover effects

### 5. **Projects Section**
- Grid layout cho projects
- Hover animations
- Tech tags
- External links (GitHub, Demo)

### 6. **Certifications Section**
- Certificate cards với icons
- Achievement display
- Date information

### 7. **Contact Section**
- Contact information
- Working contact form với validation
- Social media links
- Success/error notifications

## ⚙️ Cài đặt và sử dụng

### Bước 1: Clone hoặc download dự án
```bash
git clone <repository-url>
cd portfolio
```

### Bước 2: Mở trong browser
- Mở file `index.html` trong trình duyệt web
- Hoặc sử dụng Live Server extension trong VS Code

### Bước 3: Tùy chỉnh nội dung

#### Thay đổi thông tin cá nhân:
1. Mở `index.html`
2. Tìm và thay đổi:
   - Tên: "Nguyễn Văn A"
   - Email: "nguyenvana@email.com" 
   - Số điện thoại: "+84 123 456 789"
   - Địa chỉ: "Hà Nội, Việt Nam"

#### Cập nhật skills:
1. Trong section `#skills`
2. Thay đổi skill names và data-width percentages
3. Thêm/xóa skill categories nếu cần

#### Thêm projects mới:
1. Copy cấu trúc `.project-card`
2. Thay đổi:
   - Icon (FontAwesome class)
   - Tiêu đề và mô tả
   - Tech tags
   - Links (GitHub, Demo)

#### Cập nhật chứng chỉ:
1. Trong section `#certifications`
2. Thay đổi tên chứng chỉ, mô tả và năm

## 🖼️ Thêm hình ảnh

### Thêm avatar:
1. Đặt ảnh vào thư mục `assets/`
2. Thay thế `.image-placeholder` trong CSS:
```css
.about-image img {
    width: 250px;
    height: 250px;
    border-radius: 50%;
    object-fit: cover;
}
```

### Thêm project thumbnails:
1. Thay thế `.project-image i` bằng thẻ `<img>`
2. Update CSS accordingly

## 🎭 Tùy chỉnh theme

### Thay đổi màu sắc:
Chỉnh sửa CSS variables trong `:root`:
```css
:root {
    --primary-color: #your-color;
    --accent-color: #your-accent;
    /* ... */
}
```

### Thay đổi fonts:
1. Update Google Fonts link trong `<head>`
2. Thay đổi `font-family` trong CSS

## 📊 Performance

- **Optimized images**: Sử dụng format WebP nếu có thể
- **Lazy loading**: Implement cho images
- **Minified CSS/JS**: Nén code cho production
- **CDN**: FontAwesome và Google Fonts qua CDN

## 🔧 Browser Support

- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+

## 📝 License

MIT License - Tự do sử dụng cho mục đích cá nhân và thương mại.

## 🤝 Đóng góp

1. Fork dự án
2. Tạo feature branch
3. Commit changes
4. Push to branch  
5. Tạo Pull Request

## 📞 Liên hệ

- **Email**: nguyenvana@email.com
- **LinkedIn**: [Your LinkedIn]
- **GitHub**: [Your GitHub]

---

**Happy Coding! 🛡️💻**

> "Security is not a product, but a process" - Bruce Schneier "# nguyennt.github.io" 
