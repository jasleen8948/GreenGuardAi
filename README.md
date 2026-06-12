# 🌿 GreenGuard AI – Plant Disease Detection

> AI-powered crop disease detection in seconds, not days.

GreenGuard AI is a deep learning web application that analyzes leaf images to detect plant diseases instantly. Upload a photo of any affected leaf and receive a detailed diagnosis, confidence score, treatment plan, and prevention tips — powered by Claude AI vision.

---

## ✨ Features

- **Instant Disease Detection** — Analyze leaf images in under 5 seconds
- **38 Disease Classes** — Trained on 54,000+ labeled plant images
- **14 Crops Supported** — Tomato, corn, grape, apple, potato, and more
- **99% Classification Accuracy** — State-of-the-art CNN model
- **Treatment Guidance** — Step-by-step treatment plans for detected diseases
- **Prevention Tips** — Actionable prevention cards for each disease
- **AI Chat Assistant** — Ask GreenGuard AI farming questions in real time
- **Demo Mode** — Try with pre-loaded disease examples (no image needed)
- **Responsive Design** — Works on desktop and mobile

---

## 🖥️ Demo

Open `index.html` in your browser or host it on any static server. No build step required.

### Demo Disease Examples
| Disease | Crop | Severity |
|---|---|---|
| Tomato Early Blight | Tomato | 🔴 High |
| Common Corn Rust | Corn / Maize | 🟡 Moderate |
| Downy Mildew | Grapevine | 🔴 High |
| Apple Scab | Apple | 🟡 Moderate |
| Late Blight | Potato | 🔴 Critical |
| Healthy Leaf | Any | ✅ None |

---

## 🚀 Getting Started

### Option 1 — Open directly
```bash
# Clone the repo
git clone https://github.com/jasleen8948/GreenGaurdAi.git
cd GreenGaurdAi

# Open in browser
open index.html
```

### Option 2 — Serve locally
```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx serve .
```

Then visit `http://localhost:8080` in your browser.

---

## 🔑 AI Analysis Setup

To enable **real image analysis** (beyond demo mode), add your Anthropic API key:

1. Open `index.html` in a text editor
2. Find the line:
   ```js
   const ANTHROPIC_API = ...;
   ```
3. Replace the value with your Anthropic API key from [console.anthropic.com](https://console.anthropic.com)

> **Note:** Without an API key, the app works fully in **Demo Mode** with pre-loaded disease results.

---

## 🌱 Supported Crops

| Crop | Scientific Name |
|---|---|
| Tomato | *Solanum lycopersicum* |
| Corn / Maize | *Zea mays* |
| Grapevine | *Vitis vinifera* |
| Apple | *Malus domestica* |
| Potato | *Solanum tuberosum* |
| Pepper | *Capsicum annuum* |
| Strawberry | *Fragaria × ananassa* |
| Peach | *Prunus persica* |
| Cherry | *Prunus avium* |
| Blueberry | *Vaccinium corymbosum* |
| Raspberry | *Rubus idaeus* |
| Soybean | *Glycine max* |
| Squash | *Cucurbita pepo* |
| Orange | *Citrus sinensis* |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Vision | Claude Sonnet (Anthropic) |
| Typography | Inter + Playfair Display (Google Fonts) |
| Hosting | Any static file server |

---

## 📁 Project Structure

```
GreenGaurdAi/
└── index.html       # Complete single-file application
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for:
- New crop or disease support
- UI/UX improvements
- Additional language support
- Mobile app version

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

<p align="center">Made with 🌿 by GreenGuard AI</p>
