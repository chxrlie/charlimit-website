# IT Apprentice Portfolio - Neovim Terminal Theme

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

A personal portfolio for an IT apprentice, designed with the aesthetic of a retro CRT terminal running the Neovim text editor. The project is a single-page application built with vanilla HTML, CSS, and JavaScript, focusing on a unique user interface and thoughtful design choices.

**Live Demo:** [https://charlimit.com/](https://charlimit.com/)

---

## Preview

![A screenshot of the portfolio website, showing the dark terminal background, magenta text, Neovim ASCII art logo, and CRT scanline effect.](https://raw.githubusercontent.com/chxrlie/static-webpage/refs/heads/main/Screenshot%202025-06-08%20at%2002-17-40%20%7E%24%20IT%20Apprentice%20Portfolio%20nvim.png)

---

## ✨ Features

This portfolio is not just a static page; it includes several key features to create an immersive and functional experience:

* **Retro Terminal Aesthetic:** The entire design is wrapped in a terminal emulator style, complete with:
    * CRT scanline and noise effects.
    * Glowing text and pulse animations to mimic an old monitor.
    * A colour scheme inspired by popular code editor themes.
* **Neovim-Inspired UI:** The user interface borrows elements from the Neovim text editor, including:
    * A large ASCII art logo.
    * Navigation links styled as `:Commands`.
    * A call-to-action button styled as `:wq!` (the save and quit command).
* **Dynamic Content via API:** The Neovim version number in the status bar is not hard-coded. It is fetched live from the **GitHub API**, ensuring it always displays the latest release version of Neovim.
* **Interactive Contact Section:** To make contacting simple and reduce errors, the contact section includes:
    * A "Copy Email" button that instantly copies the email address to the user's clipboard.
    * Clear visual feedback to confirm that the address has been copied.
* **Accessibility-Focused Design:** Readability was a primary concern. The portfolio uses the **Atkinson Hyperlegible** font, which is specifically designed to improve character recognition and readability for all users, especially those with low vision.
* **Responsive Layout:** The design adapts smoothly to different screen sizes, providing a consistent experience on both desktop and mobile devices.

---

## 🛠️ Tech Stack

This project was built from the ground up using fundamental web technologies, with no external frameworks.

* **HTML5:** For the core structure and content.
* **CSS3:** For all styling, animations, and the responsive layout. Makes heavy use of Custom Properties (CSS Variables) for easy theme management.
* **Vanilla JavaScript:** For all interactive elements, including:
    * The GitHub API call to fetch the Neovim version.
    * The "Copy to Clipboard" functionality.
    * Handling of disabled links and other small UI details.
* **APIs:**
    * **GitHub API:** To retrieve repository release data.
    * **Google Fonts API:** To serve the Atkinson Hyperlegible font.

---

## 🚀 Setup and Usage

As this is a self-contained front-end project, no complex setup is required.

1.  Clone or download the repository.
2.  Open the `index.html` file in any modern web browser.

An active internet connection is required for the Neovim version number and the custom font to load correctly.

---

## 🗺️ Future Roadmap

The portfolio is designed to be easily expandable. The disabled navigation links hint at future sections to be added:

* **:Progress:** A section to detail ongoing projects, learning milestones, and skills currently being developed.
* **:Certification:** A dedicated area to list and showcase completed IT certifications and qualifications.
* **:Home:** Could be expanded into a more detailed "About Me" section.

---

## AcknowledGements

* **Neovim:** For the inspiration behind the project's theme and branding.
* **Google Fonts:** for providing the highly legible Atkinson Hyperlegible font.
