# 🎨 AI Image Generator

A modern, responsive AI-powered image generator web app that uses Hugging Face API to generate high-quality images based on your imagination and prompts.

---

## 🚀 Features

- 💡 Generate images from text prompts using Hugging Face models.
- 🎛️ Select from various image generation models.
- 🖼️ Customize aspect ratio and image count.
- 🌓 Light/Dark theme toggle.
- 📱 Fully responsive on mobile and desktop.
- 📥 Download generated images.

---

## 🔗 Live Demo

👉 [Visit the AI Image Generator](https://adarshabhishek.github.io/AI-Image-Generator/)

> Hosted via GitHub Pages

---

## ⚙️ Technologies Used

- HTML, CSS (Responsive with media queries)
- JavaScript (Vanilla)
- [Font Awesome](https://fontawesome.com/)
- [Hugging Face Inference API](https://huggingface.co/inference-api)

---

## 🧠 Hugging Face API Integration

This project uses the Hugging Face Inference API to generate images via different diffusion models like:

- `stabilityai/stable-diffusion-x1-base-1.0`
- `black-forest-labs/FLUX.1-dev`
- `runwayml/stable-diffusion-v1-5`
- `prompthero/openjourney`

> Note: You need a Hugging Face **access token** to use the API.

---

## 🔐 How to Add Your Hugging Face Token

1. Go to [Hugging Face Tokens](https://huggingface.co/settings/tokens) and generate a new token.
2. Replace the token in your JavaScript (`script.js`) file:

```js
const HUGGING_FACE_API_TOKEN = "your_actual_token_here"; // ⚠️ Never expose in public repos
