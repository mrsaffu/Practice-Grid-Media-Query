# CSS Grid Practice Layout

This project presents a responsive web layout built using **CSS Grid**, designed as an educational resource for exploring key Grid properties and layout techniques. The implementation demonstrates a structured approach to grid-based design with responsive adaptation for larger viewports.


---

## 🖼️ Layout Overview

The layout consists of six grid items:
- **Header**
- **Sidebar**
- **Container 1**
- **Container 2**
- **Container 3**
- **Footer**

These elements are managed within a `.container` grid wrapper and are visually distinguished by class-specific stylings and responsive grid placements.

---

## 🔧 CSS Grid Properties Utilized

The following CSS Grid properties are employed throughout the stylesheet:

| Property                      | Description |
|------------------------------|-------------|
| `display: grid`              | Activates grid layout mode on the container. |
| `grid-template-columns`      | Defines column structure (`repeat(1, 1fr)` by default; `repeat(3, 1fr)` on larger screens). |
| `grid-template-rows`         | Intended to define row structure (correct usage: `repeat(6, 1fr)`). |
| `gap`                        | Specifies uniform spacing (`1rem`) between both columns and rows. |
| `grid-column-start/end`      | Explicitly places elements across multiple columns (e.g., header and footer spanning all columns). |
| `grid-row-start/end`         | Defines vertical span for elements such as the sidebar. |
| `@media (min-width: 768px)`  | Implements responsive behavior, adapting the grid to a multi-column layout on wider screens. |

---



## 📐 Responsive Behavior

On small screens (default), the layout collapses into a single-column flow:


Header
Sidebar
Container 1
Container 2
Container 3
Footer


On devices with a minimum width of 768px, the grid restructures into a 3-column layout with 4 defined rows:

| Header (spans 3 cols)         |                |
| ----------------------------- | -------------- |
| Sidebar                       | Container 1    |
|                               | (spans 2 cols) |
| ----------------------------- |                |
| Sidebar                       | Container 2    |
| ----------------------------- |                |
| Footer (spans 3 cols)         |                |
| ----------------------------- |                |
 


 
---

## 🧪 Implementation Notes

- **Flexbox** is used within individual grid items for content alignment (`display: flex`, `align-items`, and `justify-content`).
- **Box-sizing** is globally set to `border-box` to ensure predictable sizing across elements.
- There is a minor issue in the original code:
  - The footer's class should be corrected from `class="items , footer"` to `class="items footer"` for proper styling and placement.
  - The property `grid-template-rows: (6, 1fr);` should be corrected to `grid-template-rows: repeat(6, 1fr);` for valid CSS syntax.

---

## 📚 Purpose

This project serves as a focused exercise in CSS Grid layout principles, targeting developers seeking to enhance their proficiency in modern CSS layout strategies. It can be extended or modified for more complex layout use cases or integrated into larger front-end projects.

---

## 🚀 How to Run

1. Clone or download the project files.
2. Open `index.html` in any modern web browser.
3. Resize the window or inspect using DevTools to observe responsive behavior.

---

## ✅ Author's Note

This layout is developed purely for educational and practice purposes. Feedback, improvements, or extensions are encouraged to further refine understanding and proficiency in CSS Grid.



