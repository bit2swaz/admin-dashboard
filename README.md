# Admin Dashboard with CSS Grid

This project implements a complex admin dashboard layout using CSS Grid exclusively, demonstrating the power and flexibility of Grid for building intricate user interfaces. It features nested grids to manage various sections and components, ensuring a robust and maintainable structure.

## Project Description

This project is a detailed mockup of an admin dashboard interface. The primary goal was to achieve a multi-sectional layout, including a sidebar, header, and main content area, with extensive use of CSS Grid for positioning and responsiveness of internal components.

Key aspects and features include:

* **Holy Grail Layout:** The foundational structure uses Grid for the main sidebar, header, and content areas.
* **Nested Grids:**
    * The **Sidebar** uses Grid to arrange branding, navigation links, and settings/support sections.
    * The **Header** employs Grid for precise placement of the search bar, user profile, and action buttons.
    * The **Main Content** area utilizes Grid to organize "Your Projects," "Announcements," and "Trending" sections.
* **Responsive Project Cards:** The "Your Projects" section dynamically adjusts the number of project cards using `grid-template-columns` with `repeat(auto-fit, minmax(250px, 1fr))`, ensuring a flexible and responsive display.
* **Material Design Icons:** Integration of Material Design Icons for a clean and modern icon set.
* **Custom Typography:** Uses the 'Roboto' font from Google Fonts for consistent and readable text.
* **Dummy Content & Styling:** Includes placeholder content and styling to visually represent a complete dashboard.

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/bit2swaz/admin-dashboard.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd [your-project-folder-name]
    ```
3.  **Open `index.html`:** Simply open the `index.html` file in your web browser.

This project is built purely with HTML and CSS, so no server setup or additional dependencies are required.

## Credits

* **Icons:** [Material Design Icons](https://fonts.google.com/icons)
* **Font:** 'Roboto' from [Google Fonts](https://fonts.google.com/specimen/Roboto)

---

Enjoy exploring the Grid-powered dashboard!