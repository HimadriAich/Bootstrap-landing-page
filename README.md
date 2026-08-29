# 💻 CodeCraft Academy — Bootstrap Landing Page

CodeCraft Academy is a responsive **web development academy landing page** built as a learning project while exploring **Bootstrap 5**.

The project started as a way to follow along with a Bootstrap tutorial and was later customized with my own branding, content, layout changes, responsive improvements, and a **MapLibre interactive map**.

The main goal of this project was to understand how Bootstrap's grid system, utility classes, components, and responsive features can be used to build a modern website without making the project unnecessarily complex.

## 🚀 Live Demo

🔗 **[View the Live Website](https://bootstrap-landpage.netlify.app/)**


## ✨ Features

* 📱 Fully responsive layout for mobile, tablet, and desktop
* 🧭 Responsive navigation bar with hamburger menu
* 🦸 Hero section with call-to-action buttons
* 📩 Newsletter subscription section
* 📚 Course cards for different learning paths
* 🎓 Fundamentals and React learning sections
* ❓ FAQ section using Bootstrap Accordion
* 👨‍💻 Instructor section with profile cards
* 📍 Contact information section
* 🗺️ Interactive MapLibre map
* 📝 Bootstrap enrollment modal with form
* 🔝 Back-to-top button
* 🔗 Bootstrap Icons throughout the website
* ✨ Custom hover effects and styling

## 🛠️ Technologies Used

* **HTML5** — Page structure and semantic markup
* **CSS3** — Custom styling and responsive enhancements
* **Bootstrap 5.3.8** — Layout, components, utilities, and responsiveness
* **Bootstrap Icons** — Icons used throughout the website
* **MapLibre GL JS** — Interactive map
* **OpenFreeMap** — Map tiles and map styling

## 📖 Bootstrap Concepts Practiced

This project was mainly created to practice and understand Bootstrap's core features, including:

* Containers
* Rows and columns
* Responsive grid system
* Breakpoints
* Flexbox utilities
* Spacing utilities
* Responsive display utilities
* Cards
* Buttons
* Badges
* Navbar and responsive navigation
* Accordion
* Modal
* Forms
* Input groups
* Responsive images
* Position utilities
* Bootstrap Icons

Some custom CSS was also added where Bootstrap utilities alone weren't enough, such as hover animations, map styling, and a few responsive adjustments.

## 🗂️ Project Structure

```text
CodeCraft/
│
├── images/
│   ├── showcase.svg
│   ├── fundamentals.svg
│   └── react.svg
│
├── index.html
├── style.css
└── README.md
```

## 🗺️ Map Integration

The contact section includes an interactive map powered by **MapLibre GL JS**.

The map is centered around Boston and uses OpenFreeMap's Liberty map style.

```javascript
const map = new maplibregl.Map({
    container: 'map',
    style: 'https://tiles.openfreemap.org/styles/liberty',
    center: [-71.0589, 42.3601],
    zoom: 12
});
```

Navigation controls are also included to allow users to zoom and interact with the map.

## 📱 Responsive Design

The website uses Bootstrap's responsive grid and utility classes to adapt the layout to different screen sizes.

For example:

```html
<div class="col-md-6 col-lg-3">
```

This allows the instructor cards to automatically adjust their layout depending on the screen size.

Custom media queries were also added for a few specific responsive improvements.

## 🎯 Purpose of the Project

This project was created primarily as a **Bootstrap learning project**.

Instead of simply copying an existing tutorial website, I customized the original idea by changing the:

* Branding
* Content
* Course structure
* Color usage
* Instructor information
* Contact section
* Map integration
* Responsive behavior
* Overall visual styling

The goal was to gain practical experience using Bootstrap while still keeping the project simple enough to understand and modify.

## 🔮 Future Improvements

Some possible improvements for future versions include:

* Add functional newsletter and enrollment forms
* Add individual course pages
* Add course filtering
* Add a dark/light theme toggle
* Add animations and scroll effects
* Connect the forms to a backend
* Add authentication for students
* Replace static instructor data with dynamic data
* Add more interactive features using JavaScript

## 👨‍💻 Author

**Himadri Aich**

Built as part of my journey learning **Frontend Development, Bootstrap, and modern web technologies**.

---

⭐ If you found this project useful, feel free to explore the code and experiment with it!
