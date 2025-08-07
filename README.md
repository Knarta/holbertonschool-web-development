# 🎨 CSS Advanced - Get Schooled Website

<div align="center">

![CSS Advanced](images/img_readme.jpg)

</div>

## 📋 Project Overview

This CSS Advanced project demonstrates the creation of a complete website for "Get schooled" - a platform that teaches people how to master different types of smiles using advanced CSS techniques and modern styling.

## 🎯 What I Built

I created a website with these styled sections:

| Section | Content | CSS Techniques |
|---------|---------|----------------|
| 🏠 Header | Logo + Navigation (Courses, Pricing, Login) | Absolute positioning, Flexbox, Transparency |
| 🎬 Banner | "Get schooled" + "SMILES GRIN LAUGH" + Register button | Background-image, Typography, Buttons |
| 👨‍🏫 Instructors | Phillip Massey, Nannie Lawrence, Bruce Walters, Henry Hughes | Cards layout, Images, Typography |
| 💬 Testimonial | Customer quote about tutorials | Blockquote, Flexbox layout |
| 📹 Tutorials | 4 smile videos (Diagonal, Sad, Natural, Happy) | Grid layout, Cards, Ratings |
| 💎 Membership | Free membership with 4 benefits | Cards, Icons, Buttons |
| ❓ FAQ | 4 questions about how it works | Grid layout, Typography |
| 🦶 Footer | Logo + Social icons + Copyright | Flexbox, Social icons |

## 🛠️ How I Built It

I used these advanced CSS techniques:

### 🎨 **Layout & Positioning**
```css
/* Flexbox for navigation */
.nav-links {
  display: flex;
  gap: 50px;
}

/* Absolute positioning for header */
header {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
}
```

### 🖼️ **Background & Images**
```css
/* Background image with cover */
.banner-section {
  background-image: url(images/background.png);
  background-size: cover;
  background-position: center;
}
```

### 🎯 **Typography & Design**
```css
/* Google Fonts import */
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@400;700&display=swap');

/* Advanced typography */
.maintitle h1 {
  font-weight: 700;
  font-size: 120px;
}
```

### 🎨 **Colors & Effects**
```css
/* Buttons with effects */
.maintitle button {
  background-color: #c271ff;
  box-shadow: 4px 4px 5px 4px rgba(0, 0, 0, 0.5);
  border-radius: 50px;
  transition: all 0.3s ease;
}
```

## 📁 Files in This Project

- 📄 `index.html` - Main HTML file with semantic structure
- 🎨 `styles.css` - Main CSS file (448 lines) with:
  - Google Fonts import
  - CSS Reset
  - Flexbox and Grid layouts
  - Responsive design
  - Animations and transitions
  - Advanced typography
- 📂 `images/` - Directory containing all website images:
  - 🏷️ `logo.png` - Website logo
  - 🖼️ `background.png` - Banner background image
  - 👤 `pro_1.png`, `pro_2.png`, `pro_3.png`, `pro_4.png` - Instructor images
  - 🎬 `preview.png`, `preview_2.png`, `preview_3.png`, `preview_4.png` - Video previews
  - ⭐ `Stars.png` - Rating stars
  - 😊 `smile.png` - Smile icons
  - 🖼️ `image.png` - Testimonial image
  - 📱 `social_icons.png` - Social media icons

## 🚀 Want to Check It Out?

1. 📋 Clone the repository
2. 🌐 Open `index.html` in your web browser
3. 🔍 Explore the website with its advanced CSS styling!

## 📚 What I Learned

This project helped me master:
- **CSS Flexbox and Grid** for modern layouts
- **Advanced Typography** with Google Fonts
- **Background images** and their properties
- **CSS Animations and transitions**
- **Responsive design** principles
- **CSS Reset** and best practices
- **Absolute and relative positioning**
- **Box-shadow** and visual effects
- **Color theory** and color palettes

---

<div align="center">

**✨ Project Holberton ✨**

</div>
