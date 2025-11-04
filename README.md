# 🧠 AI Furniture AR Agent (Prototype)

This project is an experimental **AI-powered Augmented Reality (AR) assistant** that scans a room using a **normal webcam** and visualizes 3D furniture — similar to Pokémon GO but for home interiors.

---

## 🎯 Purpose

The goal is to build a prototype that:
- Detects and labels existing furniture (like sofa, table, lamp)
- Suggests new items to fill empty spaces
- Shows **real-time furniture prices** from **Amazon Product Advertising API**
- Lets users interact via **voice commands**

This project is **for educational and testing purposes only** — not a commercial product.

---

## 🧩 Features

| Mode | Description |
|------|--------------|
| 🟢 **Scan Mode** | Detects existing objects in the room and shows name + Amazon price. |
| 🟣 **Design Mode** | Suggests and renders 3D furniture in AR using Sketchfab models. |

---

## 🧠 AI Models Used

| Model | Purpose |
|--------|----------|
| Depth Anything | Depth & room layout detection |
| SAM2 | Room segmentation |
| YOLOv8 | Object detection |
| Gemini 2.5 Flash | Design suggestions |
| Whisper | Voice command recognition |
| Sketchfab API | Fetching 3D furniture models |
| Amazon Product API | Real-time product data & pricing |
| Three.js / WebXR | Rendering in AR |

---

## 🧰 Tech Stack

- Python 3.10+
- OpenCV
- PyTorch
- FastAPI (backend)
- Three.js / WebXR (frontend)
- AWS / Amazon PA-API integration

---

## 🧪 Testing Notes

This repository is currently used to **test Amazon Product Advertising API** responses for different furniture items.

There is **no live website** yet — development is being done locally (`http://localhost:8000`) to validate data integration.

---

## 🔐 Disclaimer

This project:
- Is non-commercial and for learning/demo purposes.
- Uses Amazon API data only for educational testing.
- Does not redistribute or store Amazon product data.

---

### 🔗 Developer Contact

**Developer:** Your Name  
**GitHub:** https://github.com/yourusername  
**Project:** AI Furniture AR Agent  
**Purpose:** API integration testing & AR visualization prototype
