# PERSONAL-PORTFOLIO-WEBPAGE
*COMPANY* : CODTECH IT SOLUTIONS
*NAME*: BELGE TEJASWINI ASHOK
*INTERN ID*:CTIS2651
*DOMAIN*:FRONTEND DEVELOPMENT
*DURATION*:4 WEEKS
*MENTOR*:NEELA SANTOSH




## 🔹 1️⃣ HTML Code Description (Structure)

This **HTML code** creates the **structure of a Personal Portfolio Website**.

* `<!DOCTYPE html>` defines the document as an HTML5 page.
* The `<head>` section:

  * Sets character encoding using `UTF-8`
  * Defines the page title as *Personal Portfolio*
  * Links the external CSS file
* `<nav>` section:

  * Displays the website logo
  * Contains navigation links (Home, About, Projects, Contact)
  * Includes a **dark mode toggle button**
* `<section>` elements:

  * `#home` → Introduction, name, role, buttons, and social links
  * `#about` → Short description about skills and interests
  * `#projects` → List of projects with brief descriptions
  * `#contact` → Contact form with name, email, message, and submit button
* `<footer>`:

  * Displays copyright information
* The JavaScript file is linked at the end of the body.

👉 **Purpose of HTML:**
To define the **layout and content structure** of the portfolio website.

---

## 🔹 2️⃣ CSS Code Description (Styling & Design)

This **CSS code** is used to style the portfolio and make it responsive and attractive.

* Universal selector `*` resets margin, padding, and sets a common font.
* `body`:

  * Sets background color
  * Adds smooth transition for theme change
* **Dark Mode Styling**:

  * `.dark` class changes background and text color
* **Navbar Styling**:

  * Sticky navigation bar with flex layout
  * Styled links and dark mode toggle button
* **Section Styling**:

  * Adds padding and center alignment
  * Different background for Home section
* **Buttons & Links**:

  * Rounded buttons with highlight color
  * Styled resume download and social links
* **Project Boxes**:

  * Card-style project layout with shadow and rounded corners
* **Contact Form**:

  * Styled inputs, textarea, and submit button
* **Animations**:

  * `.fade` and `.fade.show` for smooth scroll animation
* **Responsive Design**:

  * Media query adjusts navbar layout on small screens

👉 **Purpose of CSS:**
To enhance **visual appearance**, **dark mode support**, **animations**, and **responsive layout**.

---

## 🔹 3️⃣ JavaScript Code Description (Functionality & Interactivity)

This **JavaScript code** adds interactivity and dynamic behavior to the portfolio.

### ✔ Smooth Scrolling

* `scrollToSection()` smoothly scrolls to a selected section when a button is clicked.

### ✔ Dark Mode Toggle

* Clicking the moon button toggles the `dark` class on the body.
* This switches between light and dark themes.

### ✔ Scroll Animation

* Detects when sections enter the viewport.
* Adds the `show` class to apply fade-in animation while scrolling.

👉 **Purpose of JavaScript:**
To provide **smooth navigation**, **dark mode functionality**, and **scroll-based animations**.


