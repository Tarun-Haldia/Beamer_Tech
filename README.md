# 🎤 Beamer Tech - SMB Transaction Voice Agent

A simple, responsive web application that integrates the **ElevenLabs Conversational AI Widget** to provide a voice-enabled financial assistant for Small and Medium Businesses (SMBs).

The application offers a clean user interface where users can interact with an AI-powered voice agent using their microphone.

---

## ✨ Features

- 🎙️ Voice-enabled AI assistant
- 📱 Responsive design for desktop and mobile
- 🎨 Modern gradient UI
- ⚡ Lightweight single-page application
- 🤖 Powered by ElevenLabs Conversational AI
- 💼 Designed for SMB transaction and financial assistance

---

## 📂 Project Structure

```
.
├── index.html      # Main application
└── README.md       # Documentation
```

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Internet connection
- A valid ElevenLabs Conversational AI Agent

---

## Installation

1. Clone the repository.

```bash
git clone https://github.com/yourusername/beamer-tech.git
```

2. Navigate into the project directory.

```bash
cd beamer-tech
```

3. Open `index.html` in your browser.

Or use a simple local server:

### Using Python

```bash
python -m http.server
```

Visit:

```
http://localhost:8000
```

---

## Configuration

The application embeds the ElevenLabs widget using:

```html
<elevenlabs-convai agent-id="agent_8nmxc15mk"></elevenlabs-convai>
```

To use your own agent, replace:

```html
agent_8nmxc15mk
```

with your own **ElevenLabs Agent ID**.

Example:

```html
<elevenlabs-convai agent-id="YOUR_AGENT_ID"></elevenlabs-convai>
```

---

## ElevenLabs Widget

The widget is loaded using:

```html
<script src="https://elevenlabs.io/convai-widget/index.js"></script>
```

This enables:

- Voice conversations
- Speech recognition
- AI responses
- Interactive microphone interface

---

## User Interface

The application consists of:

### Header

- Beamer Tech branding
- Application title
- Subtitle

### Voice Assistant

Embedded ElevenLabs conversational widget.

### Information Section

Provides instructions for users:

> Click the microphone to start talking with your financial assistant.

---

## Responsive Design

The application is optimized for:

- Desktop
- Tablet
- Mobile devices

Features include:

- Flexible layout
- Adaptive spacing
- Responsive typography

---

## Technologies Used

- HTML5
- CSS3
- JavaScript
- ElevenLabs Conversational AI Widget

---

## Browser Support

Works on modern browsers including:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

---

## Customization

You can easily modify:

### Colors

Update the gradient in the CSS:

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Title

```html
<h1>🎤 Beamer Tech</h1>
```

### Subtitle

```html
<p>SMB Transaction Voice Agent</p>
```

### Instructions

```html
💡 Click the microphone to start talking with your financial assistant
```

---

## Deployment

This project can be deployed on:

- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting
- AWS S3
- Any static web hosting service

No backend is required.

---

## Security Notes

- The application relies on the ElevenLabs hosted widget.
- Users must grant microphone permissions to use voice interactions.
- Keep your ElevenLabs Agent ID updated if you rotate or recreate your agent.

---

## Future Improvements

Potential enhancements include:

- Dark mode
- Chat transcript
- User authentication
- Transaction history
- Dashboard integration
- Custom branding
- Analytics
- Multi-language support

---

## License

This project is provided for educational and demonstration purposes.

---

## Acknowledgements

- ElevenLabs for the Conversational AI Widget
- Modern browser APIs for microphone access

---

## Author

**Beamer Tech**

Building AI-powered solutions for smarter SMB financial interactions.
