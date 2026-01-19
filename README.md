# Experiment: Admin Dashboard with CSS Grid & Theme Switching

## 1. Personal Information
* **Name:** Milan Jindal
* **UID:** 24BCY70158
* **Group:** 24BCY-1 (B)

## 2. Title
**Develop an admin dashboard with CSS Grid layout and dynamic theme switching**

## 3. My Defined Approach

To complete this experiment, I focused on writing clean, beginner-friendly code that keeps structure, style, and logic separate but easy to understand.

* **Structure (HTML):**
    * I used a main container `div` to hold everything.
    * Inside, I divided the page into three main sections: Sidebar (navigation), Header (top bar), and Content (main area).
    * I used standard semantic tags like `div`, `h3`, and `button` to keep the markup simple.

* **Layout (CSS Grid):**
    * I used `display: grid` on the main container.
    * I defined columns using `220px 1fr` (fixed sidebar, flexible content) and rows using `60px 1fr` (fixed header, flexible content).
    * This ensures the layout stays stable even when the screen size changes.

* **Dynamic Theme Switching (JavaScript):**
    * Instead of complex CSS variables, I used a class-based approach.
    * I defined a specific CSS class `.dark-mode` that overrides the background and text colors.
    * I wrote a simple JavaScript function `toggleTheme()` that toggles this class on the `<body>` element when the button is clicked.

* **Interactivity:**
    * I added a `selectMenu()` function that highlights the active menu item by adding/removing an `.active` class.
    * I implemented a `addVisitor()` function using `parseInt()` to demonstrate basic DOM manipulation and data updating.
