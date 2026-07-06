# CineFlix 🎬

A modern and responsive movie catalog interface built with a focus on clean design, semantic structure, and intuitive user experience, simulating large streaming platforms.

---

## 🚀 Technologies Used

The project was built exclusively with native web technologies, requiring no external frameworks or libraries:

- **HTML5:** Semantic structuring and component organization.
- **CSS3:** Advanced styling utilizing **Flexbox** for dynamic layouts, micro-interactions (`hover`, `scale`, `transitions`), and proportional responsiveness.
- **Google Fonts:** Integrated typography using _Inter_, _Bebas Neue_, and _Orbitron_ fonts.

---

## 🎨 Implemented Layout Features

- **Fixed Centered Sidebar:** A vertical navigation menu that stays fixed during scroll, featuring interactive button boxes.
- **Catalog-Style Layout:** Full-width horizontal movie cards that proportionally adapt to the remaining screen space next to the sidebar.
- **Metadata Block:** Clear display for movie ratings (with colored highlighting), release years, and durations.
- **Smart Image Handling:** Uses `object-fit: cover` to adapt posters cleanly without stretching or distorting the original aspect ratio.
- **Safe Line Truncation:** Long titles and synopses are gracefully cut off with ellipses (`...`) via CSS to maintain strict page alignment.

---

## 🛠️ How to Run the Project

Since the project uses pure static files, no installation or dependency management is required:

1. Clone or download this repository.
2. Open the `index.html` file directly in any modern web browser (or use the _Live Server_ extension in VS Code).

INPORTANT: You need to add banners images, in this path "./assets/img/{name of image, same of images in index.html}"
---

## 🧠 Key Learnings

During the development of this interface, the following front-end architecture concepts were practiced and consolidated:

- Manipulating axes and proportional alignment using **Flexbox** properties.
- Structuring CSS architecture with clean class naming and clear developer comments.
- Preventing broken layouts using overflow safety constraints (`overflow: hidden`).

