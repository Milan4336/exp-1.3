# Experiment: Basic Admin Dashboard with CSS Grid

## 1. Personal Information
* **Name:** Milan Jindal
* **UID:** 24BCY70158
* **Group:** 24BCY-1 (B)

## 2. Title
**Develop an admin dashboard with CSS Grid layout and dynamic theme switching**

## 3. My Defined Approach

I focused on creating a clear, easy-to-understand layout without complex mobile code.

* **Grid Layout:** * I used `display: grid` with `grid-template-columns: 200px 1fr` to create a fixed sidebar and a flexible main area.
    * The main content area also uses grid to align the cards in a row (`repeat(3, 1fr)`).

* **Theme Switching:** * I used CSS variables (`--bg-color`) to store colors.
    * A simple JavaScript function `toggleTheme()` swaps the class `dark-mode` on the body, which updates these variables instantly.

* **Interactivity:**
    * I added two interactive buttons using basic JavaScript:
        1. **Counter:** Increases the number of views when clicked.
        2. **Status Toggle:** Changes text from "Online" to "Offline" and changes the text color.