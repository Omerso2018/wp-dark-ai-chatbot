# 🧠 WP Dark AI Chatbot

A sleek, modern, and fully responsive AI-powered chatbot designed for **WordPress** websites. This chatbot is styled for **dark mode** themes and integrates with **OpenRouter** to utilize powerful LLMs (Large Language Models) like Mistral, Claude, GPT, and more.


# 📷 UI Previews

| Theme  | Preview |
|----|---------|
|Purple| purple Chatbot UI <img width="1920" height="1080" alt="purple" src="https://github.com/user-attachments/assets/6d637f12-1b2e-424d-8147-2a9bc7801966" />|
|Blue| Blue Chatbot UI <img width="2560" height="1440" alt="blueUI" src="https://github.com/user-attachments/assets/fd995d70-2a7b-49ee-8682-b79b5dc1f298" />|
Fully responsive, dark-themed AI chatbot for WordPress — integrates seamlessly with OpenRouter LLMs using just one HTML file.


---

# 🔥 Features

- ✨ **Minimal setup** – just copy & paste into WordPress
- 🎨 **Dark theme design** – perfect for dark-themed websites
- 🤖 **OpenRouter AI support** – use any OpenRouter-compatible model
- ⚙️ **Customizable system prompt** – control the chatbot's personality
- 📁 **File uploads** – support for images, PDFs, docs, zips, etc.
- 💾 **Local memory** – keeps recent conversation context
- 📝 **Markdown rendering** – code formatting, bullet lists, and more
- 📱 **Mobile responsive** – works great on any screen size

---

## 📥 Installation & Usage

## ✅ WordPress Integration

1. Open your WordPress admin panel.
2. Go to **Plugins** > **WPCode** (or any other Code Snippet manager).
3. Create a new **HTML snippet**.
4. Copy the content of `WP-Chatbot-Dark.html` into the snippet.
5. Save and enable the snippet on the frontend.

> 💡 The chatbot widget will appear as a floating bubble on the bottom-right corner of your website.

---

# ⚙️ Configuration

Open the HTML file and locate the `CONFIG` object in the JavaScript section to customize:

### 🔐 API Key & Model

Replace the following with your OpenRouter credentials:

```javascript
API: {
        KEY: 'YOUR_OPENROUTER_API_KEY', // Replace with your actual API key

        MODEL: 'mistralai/mistral-small-3.2-24b-instruct:free', // Default model
```
-------------------------------------------------------------
## 🧠 System Prompt
Update the system prompt to match your business needs:
```javascript
role: 'system',
content: `You are a helpful AI assistant for [Your Company]. You should...`
```
-------------------------------------------------------

## 🛠 Technologies Used

📄 Pure HTML, CSS, JS (Vanilla)

🧠 OpenRouter.ai for LLM interaction

🛡️ DOMPurify (XSS-safe)

✍️ Marked.js (Markdown rendering)

------------------------------------------

# 📜 License

- This project is open-source under the MIT License.

--------------------------------------------------------------

# 🤝 Contributions

- Feel free to open issues, suggest features, or submit pull requests. Let’s build smarter web experiences together!

  



