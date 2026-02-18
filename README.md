# Hello World - VS Code Extension

A simple "Hello World" extension for Visual Studio Code, built as a first step into the world of VS Code extension development. This project demonstrates the basic structure of an extension, including command registration and user notifications.

---

## 🚀 Features

* **Hello World Command:** Triggers a standard VS Code information message.
* **Command Palette Integration:** Easily accessible via the command search.

## 🛠️ Tech Stack

* **Language:** TypeScript / JavaScript
* **Tools:** Yeoman (`yo code`), VS Code Extension API
* **Environment:** Node.js & npm

## 🏁 Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) and [VS Code](https://code.visualstudio.com/) installed.

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  Navigate into the project directory:
    ```bash
    cd your-repo-name
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```

## 📖 How to Run

1.  Open this project folder in **Visual Studio Code**.
2.  Press **F5** to open a new **Extension Development Host** window.
3.  In the new window, press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS) to open the Command Palette.
4.  Type **"Hello World"** and press Enter.
5.  You should see a notification popup in the bottom right corner!

## 📂 Project Structure

* `package.json`: The manifest file where the extension and its commands are declared.
* `extension.ts` (or `.js`): The main entry point where the command logic resides.

---
*Created as part of my journey into VS Code Extension Development.*