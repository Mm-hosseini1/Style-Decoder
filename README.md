# 🎨 Style Decoder

**Style Decoder** is a browser-based tool that extracts and decodes the **visual style** of images using Google's Gemini API.  
It analyzes color palettes, composition, lighting, artistic influences, and more, then outputs a structured **JSON style profile** along with a simplified **style description** and **style code**.  

This project is built with **vanilla JavaScript**, **TailwindCSS**, and **Highlight.js**, with bilingual support (**English** & **Persian**) and light/dark themes.

---

## ✨ Features

- 🖼️ **Upload Images** – Drag & drop or select up to 10 images (JPEG, PNG, WebP).  
- ⚡ **Processing Power Options** – Choose between **Flash (Fast)** or **Pro (Accurate)** models.  
- 🔑 **API Key Management** – Add multiple **Google Gemini API keys**, auto-fallback on errors.  
- 🌍 **Language Toggle** – Switch seamlessly between **English** and **Persian**.  
- 🌗 **Theme Toggle** – Dark & light mode with smooth transitions.  
- 📜 **Structured Output** – JSON schema including artistic intent, composition, color, mood, etc.  
- 📋 **One-Click Copy** – Copy JSON or style code directly to clipboard.  
- 💾 **Local Persistence** – API keys and settings stored in `localStorage`.  

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/style-decoder.git
cd style-decoder
