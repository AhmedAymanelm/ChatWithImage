# 🖼️ Chat with an Image (Non-API)

This project enables you to **interact with images directly** — generate captions, detect objects, and even ask questions about the content of an image — **without relying on any external API**.  

It leverages **LangChain**, **Hugging Face Transformers (BLIP & DETR)**, and a simple **Streamlit** interface for seamless user experience.

---

## ✨ Features
- 📷 **Image Captioning**: Automatically describe an image using BLIP.
- 🕵️ **Object Detection**: Identify and label objects within an image using DETR.
- 💬 **Conversational Interface**: Ask questions about images with LangChain and conversation memory.
- 🖥️ **Interactive Web App** powered by Streamlit.
- ⚡ Runs locally without any external API dependencies.

---

## 🏗️ Architecture
- **LangChain Tools**: Wrappers for image captioning and object detection.
- **Transformers**: BLIP and DETR models for vision-language processing.
- **PyTorch**: Backend framework for model execution.
- **Streamlit**: User-friendly web interface.
- **LangChain Groq**: High-performance conversational AI integration.
- **Pillow (PIL)**: Image handling.
- **OpenCV**: Additional image processing support.

---

## 📂 Project Structure


---

## 🛠️ Requirements
- Python 3.9+
- Dependencies listed in `requirements.txt`

---

## 🚀 Getting Started

### 1. Clone the repository
``` bash
git clone https://github.com/<AhmedAymanelm>/<ChatWithImagee>.git
```

### 2.Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the Streamlit app
``` bash
streamlit run src/app.py
```


---

Do you want me to also prepare a **ready `app.py` Streamlit script** so that when you run `streamlit run src/app.py`, you instantly get the upload + Q&A interface?

