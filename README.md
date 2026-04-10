# 💖 Lovr: The Interactive Proposal Deployment Tool

> **The ultimate Open Source solution for "merging" hearts.** An interactive, responsive, and playful web application designed for developers to propose to their partners.

**Live Demo:** [zelvior.github.io/lovr/](https://zelvior.github.io/lovr/)

---

## 🚀 Overview

**Lovr** is a high-end, glassmorphic web application built using **Tailwind CSS** and **Vanilla JavaScript**. It streamlines the proposal process through a thematic "Love Protocol" initialization and a playful user interface designed to ensure a successful "Accept PR" outcome.

### ✨ Key Features

* **💌 Dynamic Parameter Detection**: Automatically extracts `to` and `from` names from the URL endpoints for instant personalization.
* **🕹️ Interactive "No" Button**: Features a sophisticated avoidance algorithm that makes the button dodge the cursor/finger, while simultaneously scaling the "Yes" button larger with every attempt.
* **📱 Universal Responsiveness**: Utilizes `100dvh` (Dynamic Viewport Height) to ensure a flawless experience across all mobile and desktop browsers.
* **🎉 Celebration Engine**: Triggers high-performance confetti and romantic success animations upon a positive response.
* **🫧 Glassmorphism UI**: Employs advanced backdrop-blur filters and soft gradients for a modern, premium aesthetic.

---

## 🛠️ Usage & Personalization

You can personalize the experience without changing a single line of code by using URL parameters.

### URL Endpoint Structure:
`https://zelvior.github.io/lovr/?to=[RECIPIENT_NAME]&from=[SENDER_NAME]`

### Parameters Reference:
| Parameter | Description | Required | Example |
| :--- | :--- | :--- | :--- |
| `to` | The recipient's name | No | `to=Sarah` |
| `from` | The sender's name | No | `from=Alex` |

---

## 💻 Technical Stack

* **Structure**: HTML5 Semantic Markup
* **Styling**: Tailwind CSS (JIT CDN)
* **Typography**: Google Fonts (Dancing Script & Quicksand)
* **Logic**: Vanilla JavaScript (ES6+)
* **Animations**: CSS Keyframes & Web Animations API

### The "No-Dodger" Algorithm
The application calculates a safe boundary within the viewport to ensure the button remains visible but unreachable:
```javascript
const x = Math.random() * (window.innerWidth - btnWidth - padding * 2) + padding;
const y = Math.random() * (window.innerHeight - btnHeight - padding * 2) + padding;
```

---

## 📂 Installation

1.  **Clone the Repository**:
    ```bash
    git clone https://github.com/zelvior/lovr.git
    ```
2.  **Local Development**:
    Simply launch `index.html` via a local server (e.g., Live Server) or open the file directly in any modern browser.
3.  **Deployment**:
    Optimized for **GitHub Pages**, **Vercel**, or **Netlify** with zero configuration required.

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for new themes, music integration, or custom animations, please open an issue or submit a Pull Request.

---

## 📜 License

Distributed under the **MIT License**.

<p align="center">
  Made with ❤️ by the Developer Community.
</p>
