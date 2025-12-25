<div align="center">

# VN-Travel

### ✈️ Website Khám Phá Vẻ Đẹp Việt Nam

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-success? style=flat-square" alt="Status">
  <img src="https://img.shields.io/badge/Responsive-Yes-blue? style=flat-square" alt="Responsive">
  <img src="https://img.shields.io/badge/License-MIT-yellow? style=flat-square" alt="License">
</p>

**Dự án học tập đầu tiên | Sinh viên năm 2 - CNTT**

[Demo](#-demo) • [Tính năng](#-tính-năng) • [Cài đặt](#-cài-đặt) • [Tác giả](#-tác-giả)

---

</div>

## 📖 Giới thiệu

> _"Việt Nam - Điểm đến của sự kỳ diệu"_

**VN-Travel** là website tĩnh giới thiệu vẻ đẹp du lịch Việt Nam, từ những bãi biển tuyệt đẹp ở Kiên Giang, Phú Quốc đến những thành phố sôi động như Sài Gòn, Hà Nội. Đây là dự án đầu tay trong hành trình học lập trình web của tôi.

## 🏗️ Kiến trúc dự án

```
┌─────────────────────────────────────────────────────────┐
│                       🎯 HEADER                         │
│  ┌─────┬─────────┬──────┬─────────┬──────┬───────────┐  │
│  │Home │Location │ Tour │ Contact │ More │ 🔍 Search │  │
│  └─────┴─────────┴──────┴─────────┴──────┴───────────┘  │
├─────────────────────────────────────────────────────────┤
│                                                         │
│                      🖼️ SLIDER                          │
│                   "Welcome to Vietnam"                  │
│                                                         │
├─────────────────────────────────────────────────────────┤
│                      📄 CONTENT                         │
│  ┌─────────────────────────────────────────────────┐    │
│  │ 📍 ABOUT      - Giới thiệu Việt Nam            │    │
│  ├─────────────────────────────────────────────────┤    │
│  │ 🗺️ LOCATION   - Kiên Giang | Sài Gòn | ...      │    │
│  ├─────────────────────────────────────────────────┤    │
│  │ 🎫 TOUR       - Các tour du lịch               │    │
│  ├─────────────────────────────────────────────────┤    │
│  │ 📞 CONTACT    - Thông tin liên hệ              │    │
│  ├─────────────────────────────────────────────────┤    │
│  │ 🖼️ IMAGE      - Thư viện ảnh                   │    │
│  └─────────────────────────────────────────────────┘    │
├─────────────────────────────────────────────────────────┤
│                       🦶 FOOTER                         │
└─────────────────────────────────────────────────────────┘
```

## ✨ Tính năng

<table>
  <tr>
    <td align="center" width="25%">
      <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/House.png" width="60"/>
      <br><b>Header & Navigation</b>
      <br><sub>Menu điều hướng responsive</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Clapper%20Board.png" width="60"/>
      <br><b>Slider</b>
      <br><sub>Banner ấn tượng</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/World%20Map.png" width="60"/>
      <br><b>Location</b>
      <br><sub>Địa điểm du lịch</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Mobile%20Phone.png" width="60"/>
      <br><b>Responsive</b>
      <br><sub>Tương thích mọi thiết bị</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Airplane.png" width="60"/>
      <br><b>Tour</b>
      <br><sub>Thông tin tour</sub>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Telephone%20Receiver.png" width="60"/>
      <br><b>Contact</b>
      <br><sub>Form liên hệ</sub>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Magnifying%20Glass%20Tilted%20Left.png" width="60"/>
      <br><b>Search</b>
      <br><sub>Tìm kiếm</sub>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Artist%20Palette.png" width="60"/>
      <br><b>Modal</b>
      <br><sub>Popup overlay</sub>
    </td>
  </tr>
</table>

## 🔧 Kỹ thuật nổi bật

### 📌 Modal với Overlay

```css
/* Overlay - Lớp phủ toàn màn hình */
.overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.7);
  z-index: 999;
}

/* Container Modal - Nội dung hiển thị */
. modal-container {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 1000;
}
```

### 📌 Responsive Design

```css
/* Mobile First Approach */
@media screen and (max-width: 768px) {
  /* Tablet styles */
}

@media screen and (max-width: 480px) {
  /* Mobile styles */
}
```

## 📁 Cấu trúc thư mục

```
VN-Travel/
│
├── 📄 index.html              # Trang chính
│
├── 📁 assets/
│   │
│   ├── 📁 css/
│   │   ├── 🎨 style. css      # CSS chính
│   │   └── 📱 responsive.css  # CSS responsive
│   │
│   ├── 📁 fonts/
│   │   └── 📁 themify-icons/  # Icon fonts
│   │
│   └── 📁 img/
│       ├── 📁 Logo/           # Logo website
│       └── 📁 location/       # Hình ảnh địa điểm
│
└── 📄 README.md
```

## 📋 Quy trình phát triển

```
Phase 1                Phase 2              Phase 3              Phase 4
┌──────────┐          ┌──────────┐        ┌──────────┐        ┌──────────┐
│ 📊       │          │ 🏗️       │        │ 🔨       │        │ ✅       │
│ PHÂN     │    ➡️    │ DỰNG     │   ➡️   │ XÂY      │   ➡️   │ HOÀN     │
│ TÍCH     │          │ BASE     │        │ DỰNG     │        │ THIỆN    │
│          │          │          │        │          │        │          │
└──────────┘          └──────────┘        └──────────┘        └──────────┘
   Header               Reset CSS           Component           Testing
   Slider               Grid System         by Component        Optimize
   Content              Variables           Styling             Deploy
   Footer               Base Layout         Responsive
```

## 🚀 Cài đặt

```bash
# Clone repository
git clone https://github.com/Thienhd68/VN-Travel.git

# Di chuyển vào thư mục
cd VN-Travel

# Mở với VS Code
code .

# Sử dụng Live Server hoặc mở trực tiếp index.html
```

## 📸 Demo

<div align="center">

### 🌐 [Xem Live Demo](https://thienhd68.github.io/VN-Travel/)

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-Click%20Here-blue?style=for-the-badge)](https://thienhd68.github.io/VN-Travel/)

<br>

|                                     Desktop                                     |                                               Mobile                                               |
| :-----------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: |
| <img src="./assets/img/readme/thienhd68.github.io_VN-Travel_.png" width="500"/> | <img src="./assets/img/readme/thienhd68.github.io_VN-Travel_(iPhone 14 Pro Max).png" width="200"/> |

</div>

## 📚 Kiến thức đã học

<details>
<summary><b>🔶 HTML5</b></summary>

- Semantic HTML (`header`, `nav`, `section`, `footer`)
- Form elements
- SEO meta tags
</details>

<details>
<summary><b>🔷 CSS3</b></summary>

- Flexbox & Grid Layout
- Position: `fixed`, `relative`, `absolute`
- Responsive với Media Queries
- CSS Variables
- Transitions & Animations
</details>

<details>
<summary><b>🟨 JavaScript</b></summary>

- DOM Manipulation
- Event Listeners
- Toggle classes
</details>

## 🔮 Roadmap

- [x] Hoàn thành giao diện cơ bản
- [x] Responsive design
- [x] Navigation menu
- [x] Deploy lên GitHub Pages
- [ ] Thêm hiệu ứng animation
- [ ] Tích hợp Google Maps API
- [ ] Dark mode
- [ ] Multi-language (EN/VI)

## 👨‍💻 Tác giả

<div align="center">
  <img src="https://github.com/Thienhd68.png" width="100" style="border-radius:  50%"/>
  <br>
  <b>Thienhd68</b>
  <br>
  <sub>Thien Huynh | 📍 SG - UTH - IT</sub>
  <br><br>
  
  [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Thienhd68)
</div>

## 📄 License

```
MIT License

Copyright (c) 2025 Thienhd68

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files.
```

---

<div align="center">

### ⭐ Nếu thấy hữu ích, hãy cho mình một star nhé!

Made with ❤️ in Vietnam 🇻🇳

</div>
