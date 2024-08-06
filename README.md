# 🚀 Drag and Drop Feature

This project features a sleek and intuitive drag-and-drop functionality, implemented using HTML, CSS, and JavaScript. It enables users to effortlessly drag items from one container to another, demonstrating the power and simplicity of the drag-and-drop API.

## 📋 Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Technologies Used](#technologies-used)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## 🌟 Introduction

The **Drag and Drop Feature** project showcases a fundamental aspect of modern web applications—allowing users to interactively move elements around a page. This basic implementation serves as a great starting point for understanding the drag-and-drop API in JavaScript, with a simple interface that demonstrates dragging items between two containers.

## 🚀 Getting Started

### Prerequisites

- 🌐 A modern web browser (e.g., Chrome, Firefox, Safari)
- 📚 Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd drag-and-drop-feature
   ```

2. **Open the Project**:

   Simply open the `index.html` file in your web browser to explore the drag-and-drop functionality.

## 💻 Usage

1. **Drag Items**:

   - Click and hold any item within the "left" container.
   - Drag the item to the "right" container and release it to drop.

2. **Move Items Back**:

   - Items can also be dragged from the "right" container back to the "left" container, demonstrating flexibility in item positioning.

## 🛠️ Code Overview

### 1. HTML Structure

The `index.html` file sets up the core structure, featuring two main containers—`left` and `right`. Each draggable item is assigned the `draggable="true"` attribute, enabling the drag capability.

### 2. CSS Styling

The styles in `style.css` (not included here) define the visual layout, ensuring a clean and user-friendly interface for the containers and list items.

### 3. JavaScript Functionality

JavaScript powers the drag-and-drop interactions:

- **Element Selection**: Utilizes `document.getElementsByClassName("list")` and `document.getElementById()` to target draggable items and drop zones.
- **Drag Events**: Event listeners for `dragstart`, `dragover`, and `drop` are employed to handle the dragging process smoothly.
- **Drag and Drop Logic**: The `dragstart` event stores the dragged item, `dragover` prevents default behavior to allow dropping, and `drop` finalizes the item transfer between containers.

## 🛠️ Technologies Used

- **HTML5**: Provides the structural foundation of the application.
- **CSS3**: Styles and arranges the visual elements.
- **JavaScript**: Implements the core drag-and-drop functionality.

## 📸 Screenshots

- ![Drag and Drop Demo](https://github.com/shamshubham/Drag-And-Drop-Feature/blob/master/screenShots/Capture.JPG)
- ![Drag and Drop in Action](https://github.com/shamshubham/Drag-And-Drop-Feature/blob/master/screenShots/Capture1.JPG)

## 🤝 Contributing

Contributions are warmly welcomed! To contribute:

1. **Fork the Repository**: Create your own copy of the project.
2. **Create a Branch**: Work on your feature or fix in a new branch.
3. **Commit Your Changes**: Clearly describe your modifications.
4. **Push to GitHub**: Push your changes to your forked repository.
5. **Submit a Pull Request**: Propose your changes for inclusion in the project.

For substantial changes, please open an issue to discuss your ideas before implementation.

## 📜 License

This project is open-source and available under the MIT License.

## 🙏 Acknowledgments

- Thanks to the developers and designers whose insights and creativity inspired this project.
- A special shoutout to the open-source community for their invaluable resources and continuous support.
