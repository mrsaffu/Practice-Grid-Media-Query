# 🎨 Responsive Web Design Practice: Media Queries & CSS Grid

Welcome to the **Responsive Web Design Practice Repository**!  
This repo is your hands-on guide to mastering **Media Queries** and **CSS Grid** — two essential tools for building modern, responsive websites that look great on all devices. 📱💻🖥️

---

## 🚀 What's Inside?

This repository is built to help you:

- 💡 Understand **Media Queries** for responsive design
- 🧱 Practice building layouts using **CSS Grid**
- 🛠️ Learn and apply all related properties with examples

---

## 📘 Media Queries: Make Your Design Responsive

### 🔍 What is a Media Query?

A **media query** lets you apply CSS styles based on the user's device screen size, resolution, or orientation. It's the key to making your websites responsive.

### ✅ Syntax:

```css
@media (condition) {
  /* CSS styles here */
}



## 🛠 Common Media Features:


| Feature       | Description                                                            |
| ------------- | ---------------------------------------------------------------------- |
| `max-width`   | Applies styles if screen width is **less than or equal to** a value    |
| `min-width`   | Applies styles if screen width is **greater than or equal to** a value |
| `orientation` | Detects **portrait** or **landscape** mode                             |
| `resolution`  | Targets screen resolution (e.g. `300dpi`)                              |
```

### Example :

@media (max-width: 768px) {
.container {
flex-direction: column;
}
}
