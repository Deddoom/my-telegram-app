# 🤖 AI Multi-Tool Telegram Mini App

![Language](https://img.shields.io/badge/Language-HTML5-E34F26?style=for-the-badge&logo=html5)
![CSS](https://img.shields.io/badge/CSS-Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript)
![Platform](https://img.shields.io/badge/Platform-Telegram-2CA5E0?style=for-the-badge&logo=telegram)

This repository contains the frontend source code for a feature-rich Telegram Mini App. It provides a dynamic and responsive user interface for an AI-powered bot, allowing users to interact with various tools directly within the Telegram app instead of using text commands.

---

## 📸 App Preview


<img src="https://github.com/Deddoom/my-telegram-app/blob/main/Screenshot.PNG" alt="App Preview" width="300"/>


---

## ✨ Features

This Mini App serves as a graphical interface for a variety of backend functionalities, including:

* **💬 AI Chat**: A shortcut to switch to the bot's conversational AI mode.
* **🖼️ Background Remover**: Upload an image to automatically remove its background.
* **🔍 Product Comparison**: Input two products to get a side-by-side comparison.
* **📰 Article Generation**: Provide a topic to generate a complete article using AI.
* **ℹ️ Image Analyzer**: Upload a picture to get technical details and information about it.
* **🌄 Image Enhancer**: Improve the quality and resolution of low-quality photos.
* **🎑 Artistic Style Transfer**: Convert your photos into a unique artistic style.
* **✨ AI Image Generation**: Create images from a text prompt.
* **🌐 Text Translation**: Translate text from any language into Persian.
* **💹 Currency Rates**: Get the latest exchange rates for currencies and gold.
* **🔎 Advanced Search**: Perform a semantic search within a public Telegram channel.

---

## 🛠️ Technology Stack

* **Frontend**:
    * HTML5
    * [Tailwind CSS](https://tailwindcss.com/) for rapid, utility-first styling.
    * Vanilla JavaScript (ES6) for client-side logic and API calls.
* **Platform**:
    * [Telegram Web App API](https://core.telegram.org/bots/webapps) for integration with the Telegram client.

---

## 🚀 How to Use

This is a **frontend-only** repository. To make it functional, you need to connect it to its corresponding backend API server.

1.  **Host the Frontend**:
    * Clone this repository and host the `index.html` file on a static hosting service like **GitHub Pages**, **Vercel**, or **Netlify**.

2.  **Configure the Backend API**:
    * In the `index.html` file, update the `API_BASE_URL` JavaScript variable to point to the public URL of your backend server.
    ```javascript
    const API_BASE_URL = '[https://your-backend-api-url.com](https://your-backend-api-url.com)'; // 👈 Update this
    ```

3.  **Link to Telegram Bot**:
    * Open `@BotFather` in Telegram.
    * Select your bot and go to `Bot Settings` -> `Menu Button`.
    * Set the URL to the address where you hosted your `index.html` file (e.g., your GitHub Pages URL).

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
