<div align="center">

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Light+View+Login+Page&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=A+modern+glassmorphism+login+form+with+a+fun+moving+button&descAlignY=60&descSize=15&descColor=94a3b8" width="100%"/>

<br/>

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Boxicons](https://img.shields.io/badge/Boxicons-2.1.4-f97316?style=flat-square)](https://boxicons.com/)
[![MIT License](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)](LICENSE)
[![Deployed](https://img.shields.io/badge/Deployed-GitHub%20Pages-0ea5e9?style=flat-square&logo=github)](https://safin313-stack.github.io/light-view-login-page/)

<br/>

<a href="https://safin313-stack.github.io/light-view-login-page/">
  <img src="https://img.shields.io/badge/-%F0%9F%94%90%20%20LIVE%20DEMO%20%20%E2%86%92-302b63?style=for-the-badge&logoColor=white" alt="Live Demo" height="42"/>
</a>

<br/>
<sub>✦ No login &nbsp;·&nbsp; No install &nbsp;·&nbsp; Opens instantly in your browser ✦</sub>

<br/><br/>

</div>

---

<div align="center">

### 🔐 Features

| 🪟 Glassmorphism | 👤 Username Field | 🔒 Password Field | 🏃 Moving Button | ☑️ Remember Me | 📱 Responsive |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Frosted glass card with backdrop blur | Username input with Boxicons user icon | Password input with lock icon | Login button runs away when hovered | Remember me checkbox + forgot password link | Works beautifully on all screen sizes |

</div>

---

## 🖥️ UI Preview

```
╔══════════════════════════════════════════════════════════╗
║                                                          ║
║         ┌────────────────────────────────┐               ║
║         │                                │               ║
║         │           Login                │               ║
║         │                                │               ║
║         │  ┌──────────────────────────┐  │               ║
║         │  │ 👤  Username             │  │               ║
║         │  └──────────────────────────┘  │               ║
║         │                                │               ║
║         │  ┌──────────────────────────┐  │               ║
║         │  │ 🔒  Password             │  │               ║
║         │  └──────────────────────────┘  │               ║
║         │                                │               ║
║         │  ☑ Remember me  Forgot pwd?   │               ║
║         │                                │               ║
║         │         [ Login ]  ←runs away  │               ║
║         │                                │               ║
║         │  Don't have an account? Register│              ║
║         └────────────────────────────────┘               ║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

> ✦ Try hovering the Login button — it moves away before you can click it!

---

## 🎨 Design Highlights

### Glassmorphism Card

```css
.wrapper {
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.2);
  border-radius: 16px;
  box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
  padding: 2.5rem;
}
```

### Moving Login Button

```css
/* Button runs away on hover — fun interaction! */
.btn {
  position: relative;
  transition: transform 0.2s ease;
}

.btn:hover {
  transform: translate(
    calc(var(--move-x) * 1px),
    calc(var(--move-y) * 1px)
  );
}
```

### Input Fields with Boxicons

```html
<!-- Username field with icon -->
<div class="input-box">
  <input type="text" placeholder="Username" required>
  <i class='bx bxs-user'></i>
</div>

<!-- Password field with lock icon -->
<div class="input-box">
  <input type="password" placeholder="Password" required>
  <i class='bx bxs-lock-alt'></i>
</div>
```

### Gradient Background

```css
body {
  background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
```

---

## 📁 Project Structure

```
light-view-login-page/
│
├── 📄 index.html    ← Login form structure with Boxicons
├── 🎨 style.css     ← Glassmorphism · moving button · full styling
└── 📄 README.md     ← Project documentation
```

---

## 🚀 Run It Yourself

**Option 1 — Live (instant, no setup)**

> 🔗 **[https://safin313-stack.github.io/light-view-login-page/](https://safin313-stack.github.io/light-view-login-page/)**

**Option 2 — Clone and open locally**

```bash
git clone https://github.com/Safin313-stack/light-view-login-page.git
open index.html
```

**Option 3 — VS Code Live Server**

```
1. Install Live Server extension
2. Right-click index.html → Open with Live Server ✅
```

---

## 🛠️ Tech Stack

```
┌──────────────────────────────────────────────────────┐
│           Frontend · Zero Dependencies               │
├─────────────────┬────────────────────────────────────┤
│  HTML5          │  Semantic form structure           │
│  CSS3           │  Glassmorphism · animations        │
│  Boxicons 2.1.4 │  User and lock icons (CDN)         │
│  Technique      │  backdrop-filter for glass effect  │
└─────────────────┴────────────────────────────────────┘
```

---

## 📚 Key CSS Concepts Used

```
backdrop-filter: blur()   → frosted glass effect on the card
rgba() background         → semi-transparent glass overlay
box-shadow                → depth and glow on the card
linear-gradient           → rich deep purple background
position: relative        → allows button to move on hover
transform: translate()    → button runs away from cursor
border-radius             → rounded card and input styling
transition                → smooth hover and focus effects
```

---

## 💡 Credits & Inspiration

Special thanks to **TCW - AI & coding resources** (Telegram Community)
for ideas, guidance, and coding support throughout this project. 🙏

---

<div align="center">

## 👤 Developer

<br/>

**Saharia Hassan Safin**
Front-end Developer

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-Safin313--stack-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Safin313-stack)
&nbsp;
[![Live Project](https://img.shields.io/badge/Live%20Project-Visit%20Now-302b63?style=for-the-badge&logo=vercel&logoColor=white)](https://safin313-stack.github.io/light-view-login-page/)

<br/>

*"A login page where the button has trust issues"* 🔐

<br/>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>

<sub>MIT License · © 2025 Saharia Hassan Safin · ⭐ Star this repo if it made you smile!</sub>

</div>
