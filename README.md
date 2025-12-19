# TaskFlow — Just Do It

> A simple, elegant todo application built with HTML, CSS & JavaScript

A clean, modern to-do list that helps you organize tasks effortlessly with local persistence, multiple themes, and responsive design.

![TaskFlow Banner](https://img.shields.io/badge/TaskFlow-Just_Do_It-4CAF50?style=for-the-badge)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Usage](#-usage)
- [Technology Stack](#️-technology-stack)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)
- [Acknowledgments](#-acknowledgments)

## 🎯 About

**TaskFlow** is a lightweight, client-side to-do list application built with vanilla JavaScript. It requires no backend, no frameworks, and no complexity—just a clean interface to help you get things done efficiently.

**Key Highlights:**
- 🚀 Zero dependencies - pure vanilla JavaScript
- 💾 Browser-based storage - your data stays private
- ⚡ Instant loading - no server calls required
- 📱 Mobile-friendly - works on all devices

Perfect for students, professionals, or anyone seeking a straightforward task manager without unnecessary bloat.

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📝 **Simple Task Management** | Add, complete, and remove tasks with intuitive controls |
| 💾 **Local Persistence** | Tasks automatically saved in browser Local Storage |
| 🕒 **Live Clock** | Real-time date and time display to keep you on track |
| 🎨 **Multiple Themes** | Choose from various color themes to match your style |
| 📱 **Fully Responsive** | Seamlessly adapts to desktop, tablet, and mobile devices |
| ⚡ **Lightning Fast** | No loading screens, instant interactions |
| 🔒 **Privacy First** | Your data never leaves your device |

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have:
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Optional: A local web server for development

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/karriprathyusha/TaskFlow-Todo-App.git
   ```

2. **Navigate to project directory**
   ```bash
   cd TaskFlow-Todo-App
   ```

3. **Launch the application**

   **Method 1: Direct Open**
   - Simply double-click `index.html` or open it in your browser
   
   **Method 2: Local Server (Recommended)**
   
   Choose your preferred method:
   
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server -p 8000
   
   # Using PHP
   php -S localhost:8000
   ```
   
   Then open `http://localhost:8000` in your browser.

4. **Start organizing!** ✅

## 📁 Project Structure

```
TaskFlow-Todo-App/
│
├── index.html              # Main application page
│
├── CSS/
│   ├── main.css           # Core styles and theme definitions
│   └── corner.css         # Layout and positioning styles
│
├── JS/
│   ├── main.js            # Task management logic & UI handlers
│   └── time.js            # Real-time date and time display
│
├── README.md              # Project documentation
└── LICENSE                # MIT License file
```

## 🎯 Usage

### Adding a Task
1. Type your task in the input field
2. Press **Enter** or click the **Add** button
3. Your task appears instantly in the list

### Managing Tasks
- **✅ Complete** - Click the checkbox to mark a task as done
- **🗑️ Delete** - Click the delete button to remove a task
- **💾 Auto-save** - All changes are automatically saved to Local Storage

### Customizing Your Experience
- **🎨 Theme Selection** - Use the theme selector to switch between color schemes
- **📱 Responsive Design** - The layout automatically adapts to your screen size

### Data Persistence
Your tasks are stored locally in your browser using the Local Storage API. This means:
- Tasks persist across browser sessions
- No internet connection required
- Complete privacy - data never leaves your device
- Works offline by default

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic markup and structure |
| **CSS3** | Styling, themes, and responsive layout |
| **JavaScript (ES6+)** | Application logic and interactivity |
| **Local Storage API** | Client-side data persistence |

**Why Vanilla JavaScript?**
- Zero external dependencies
- Lightweight and fast
- Easy to understand and modify
- No build process required

## 🤝 Contributing

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**!

### How to Contribute

1. **Fork the Project**
2. **Create your Feature Branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your Changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the Branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Development Guidelines

- Use meaningful variable and function names
- Comment complex logic for clarity
- Follow the existing code style and formatting
- Test thoroughly across different browsers
- Update documentation for new features
- Keep commits atomic and well-described

### Reporting Issues

Found a bug or have a feature request? Please open an issue with:
- Clear description of the problem/suggestion
- Steps to reproduce (for bugs)
- Expected vs actual behavior
- Browser and OS information

## 📄 License

Distributed under the MIT License. See `LICENSE` file for more information.

This means you can use, modify, and distribute this project freely, even for commercial purposes.

## 👤 Author

**Karri Prathyusha**

- GitHub: [@karriprathyusha](https://github.com/karriprathyusha)
- Project Link: [TaskFlow-Todo-App](https://github.com/karriprathyusha/TaskFlow-Todo-App)

## 🌟 Show Your Support

If TaskFlow helps you stay organized and productive, please consider:
- ⭐ Starring this repository
- 🐛 Reporting bugs or suggesting features
- 🔀 Contributing to the codebase
- 📢 Sharing with others who might find it useful

Your support motivates continued development and improvement!

## 💡 Acknowledgments

- Inspired by the need for a simple, distraction-free task manager
- Built with modern web standards and best practices
- Thanks to the open-source community for continuous inspiration
- Special thanks to all contributors who help improve TaskFlow

---

<div align="center">

**Made with ❤️ and Vanilla JavaScript**

*Just do it. One task at a time.*

[⬆ Back to Top](#taskflow--just-do-it)

</div>
