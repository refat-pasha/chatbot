# Refat’s Chatbot

Welcome to Refat’s Chatbot! This is a visually appealing, full-featured web-based chatbot built with HTML, JavaScript, and CSS, utilizing the Perplexity AI or OpenAI-compatible API for AI-powered chatting. Users can:
- Upload images or text files to enrich the conversation,
- Easily toggle between Light and Dark themes,
- Enjoy a modern, responsive, and interactive glassmorphic interface.

## 🌐 Live Demo

Try it online: [https://refat-pasha.github.io/chatbot/](https://refat-pasha.github.io/chatbot/)

---

## 🚀 Features

- **Multimodal Input:** Upload images (JPG, PNG, GIF, WEBP) or plain text files and reference them in your chat.
- **Base64 Image Handling:** Images are converted to base64 and sent in the message for multimodal AI support.
- **Dynamic Theming:** Switch between Light and Dark modes with a single click.
- **Responsive Design:** Clean, glassmorphic UI looks sharp on mobile and desktop.
- **Chat History:** Messages alternate perfectly between user and assistant, following API requirements.
- **Footer Branding:** “Made by Refat” visible on all devices and both themes.
- **No frameworks needed:** 100% vanilla HTML/CSS/JS.

---

## 🛠️ Setup & Usage

1. **Clone the repository:**
    ```
    git clone https://github.com/refat-pasha/chatbot.git
    cd chatbot
    ```

2. **Get your API Key:**
   - Register and get your API key from [Perplexity AI](https://www.perplexity.ai/) or compatible service.

3. **Insert API Key:**
   - Open `index.html` in a code editor.
   - Replace the `API_KEY` variable with your API key:

     ```
     const API_KEY = "YOUR_API_KEY_HERE";
     ```

4. **Run locally:**
   - Simply open `index.html` in your browser.

5. **Or deploy:**
   - You can publish to GitHub Pages or any static hosting service.

---

## 📸 Screenshots

![Light Mode](docs/screenshot-light.png)
![Dark Mode](docs/screenshot-dark.png)

---

## 💡 How it Works

- Compose your message (and optionally upload an image or text file).
- Click "Send". The message, plus any file/image as string, is sent to the API.
- The assistant's reply appears just below.
- All conversations are local to your browser (no logging or tracking).

---

## ⚡ Customization

- You can change colors or tweak the CSS for your preferred style.
- Upload limits: By default, text files are truncated to 12,000 characters and images are sent as base64 URL strings.
- Footer and header text can be customized in `index.html`.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Acknowledgments

- Powered by [Perplexity](https://www.perplexity.ai/) APIs.
- UI inspired by modern glassmorphism and conversational design trends.

---

> **Made by Refat**
