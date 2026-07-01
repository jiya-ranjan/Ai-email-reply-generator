# ✉️ AI Email Generator Chrome Extension

An AI-powered Chrome Extension that helps users generate professional email replies directly inside Gmail using the **Google Gemini API**. The extension adds an **AI Reply** button to the Gmail compose/reply window, allowing users to create email replies in different tones with a single click.

---

## 🚀 Features

- 🤖 AI-powered email reply generation
- 🎭 Multiple reply tones
  - Professional
  - Friendly
  - Formal
  - Casual
- 📧 Works directly inside Gmail
- ⚡ One-click email generation
- 🎨 Clean and user-friendly interface
- 🔗 Powered by Google Gemini API

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- JavaScript
- Chrome Extension (Manifest V3)

### Backend
- Java
- Spring Boot

### AI
- Google Gemini API

---

## 📂 Project Structure

```text
AI-Email-Generator/
│
├── frontend/
│   ├── manifest.json
│   ├── content.js
│   ├── popup.html
│   ├── popup.js
│   ├── styles.css
│   └── icons/
│
├── backend/
│   ├── src/
│   ├── pom.xml
│   └── application.properties
│
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

### 2. Backend Setup

Navigate to the backend directory:

```bash
cd backend
```

Add your Gemini API key to the `application.properties` file:

```properties
gemini.api.key=YOUR_GEMINI_API_KEY
```

Run the Spring Boot application.

---

### 3. Load the Chrome Extension

1. Open Chrome.
2. Go to:

```
chrome://extensions
```

3. Enable **Developer Mode**.
4. Click **Load Unpacked**.
5. Select the extension folder.

---

## 📖 How to Use

1. Open Gmail.
2. Click **Compose** or **Reply**.
3. Choose your preferred reply tone.
4. Click the **AI Reply** button.
5. The extension sends the request to the Spring Boot backend.
6. The backend uses the **Google Gemini API** to generate an email reply.
7. The generated reply is automatically inserted into the Gmail compose box.

---

## 🔑 Requirements

- Google Chrome
- Java 17+
- Maven
- Google Gemini API Key

---

## 📸 Demo

Add screenshots or a GIF of the extension here.

---


## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch:

```bash
git checkout -b feature-name
```

3. Commit your changes:

```bash
git commit -m "Added new feature"
```

4. Push to your branch:

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Jiya Ranjan**

GitHub: https://github.com/jiya-ranjan

LinkedIn: https://www.linkedin.com/in/jiya-ranjan55

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
