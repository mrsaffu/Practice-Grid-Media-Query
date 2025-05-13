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


---

## 🚀 What is CSS Grid?

**CSS Grid** is a layout system in CSS that allows you to arrange content in **rows and columns**. It gives you full control over layout structure, making it ideal for responsive and complex designs.

---

## 📦 Basic Example

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
```

This example creates a 3-column layout with equal widths and a gap of 20px between grid items.

---

## 🔑 CSS Grid Properties & Definitions

| Property                  | Description |
|---------------------------|-------------|
| `display: grid`           | Enables grid layout on the container |
| `grid-template-columns`   | Defines number and width of columns |
| `grid-template-rows`      | Defines number and height of rows |
| `gap` / `row-gap` / `column-gap` | Adds spacing between rows and columns |
| `grid-column`             | Specifies how many columns an item should span |
| `grid-row`                | Specifies how many rows an item should span |
| `justify-items`           | Aligns items **horizontally** inside their cell |
| `align-items`             | Aligns items **vertically** inside their cell |
| `place-items`             | Shorthand for `justify-items` and `align-items` |
| `justify-content`         | Aligns the entire grid **horizontally** in the container |
| `align-content`           | Aligns the entire grid **vertically** in the container |
| `place-content`           | Shorthand for `justify-content` and `align-content` |
| `grid-area`               | Specifies a grid item’s position using a name or coordinates |
| `grid-template-areas`     | Creates named layout areas |

---

## 🧪 Practice Exercises

Here are some challenges to build your CSS Grid skills:

- ✅ Create a 3x3 image gallery grid
- ✅ Design a pricing table layout
- ✅ Make a blog layout with sidebar, header, main content, and footer
- ✅ Build a card grid that rearranges on small screens

---

## 🧠 Pro Tips

- Use `fr` unit (fractional unit) for flexible layouts: `1fr`, `2fr`
- Combine `minmax()` for responsive sizing: `minmax(200px, 1fr)`
- Use `auto-fit` and `auto-fill` to make grid items wrap automatically
- Test with browser dev tools for different screen sizes

---

## 📁 Suggested Folder Structure

```bash
css-grid-practice/
├── 01-basic-grid.html
├── 02-gallery-layout.html
├── 03-pricing-table.html
├── 04-blog-layout.html
├── styles/
│   └── style.css
├── README.md
```

---

## 🎯 Goal

By the end of this practice, you will be able to:
- Structure responsive pages using **rows and columns**
- Align and space content using **grid properties**
- Build beautiful layouts without external frameworks

---

## 🙌 Happy Coding!

Keep experimenting with layouts and push your creativity!  
CSS Grid makes it easy to design professional-looking pages — all with pure CSS. 💪

---

> Made with ❤️ to help you become a modern web layout master.
