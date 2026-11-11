# Windows Nostalgia — Retro 90s Desktop Web Simulation

<div align="center">

[![HTML5](https://img.shields.io/badge/HTML-5-E34F26?style=for-the-badge&logo=html5&logoColor=white)]()
[![CSS3](https://img.shields.io/badge/CSS-3-1572B6?style=for-the-badge&logo=css3&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)]()

**A nostalgic, lightweight recreation of the classic Windows 95/98 desktop interface built entirely in vanilla HTML, CSS, and JavaScript.**

</div>

---

## 🖥️ Interactive Desktop Features

- **Icon Grid**: Draggable retro icons with authentic pixel art.
- **Classic Start Menu**: Cascading hierarchical start menu with nostalgic sound effects.
- **Window Management**: Movable, minimizable, and maximizable window frames.

```mermaid
graph TD
    classDef os fill:#eff6ff,stroke:#1e40af,stroke-width:2px;
    classDef win fill:#f0fdf4,stroke:#15803d,stroke-width:2px;

    Desktop[Desktop Canvas & Wallpaper] --> Taskbar[Start Menu & System Tray]
    Desktop --> Windows[Active Window Frames]
    Taskbar --> Apps[Notepad, Minesweeper, Control Panel]
    Apps --> Windows

    class Desktop,Taskbar os;
    class Windows,Apps win;
```

---

## 🚀 Run Locally

Simply open `index.html` in any web browser!

---

## 📬 Authors

- **Collaborators**: Waleed & Sayan Bhattacharya ([sayanpm17@gmail.com](mailto:sayanpm17@gmail.com))
