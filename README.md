# Responsive Landing Page — Scroll-Responsive Navigation

Welcome to **Task 1** of the Web Development Project at **SkillCraft Technology**. This project demonstrates the implementation of a scroll-sensitive, responsive landing page that enhances user experience through dynamic visual feedback.

## 📌 Project Overview

The objective of this task is to create a modern, responsive landing page that includes:

- A fixed navigation bar that changes background and shadow on scroll
- A hero section introducing the page’s purpose
- Clean, minimal, and modular code for clarity and scalability

## 🌐 Technologies Used

- **HTML5**
- **CSS3** (with custom properties / variables)
- **JavaScript (Vanilla JS)**

## 🚀 Features

- 🔝 Fixed Navigation Bar
- 🎯 Scroll-triggered UI Enhancements
- 🧱 Simple & Clean UI Design
- 💡 Uses `window.scrollY` for smooth interaction
- 💬 Inline styling and reusable layout structure

## 🔧 How It Works

The script listens for a scroll event on the `window` object and adds/removes the `scrolled` class to/from the navbar depending on the scroll position.

```javascript
const scrollThreshold = 10; 
if(window.scrollY > scrollThreshold) {
  nav.classList.add('scrolled');
} else {
  nav.classList.remove('scrolled');
}
