
# Text-to-Image Generation using Hugging Face & Stable Diffusion

A **Text-to-Image Generation** project that transforms natural language prompts into high-quality AI-generated images using **Hugging Face Diffusers**, **Stable Diffusion**, and **PyTorch**. This project demonstrates practical applications of **Generative AI**, **Deep Learning**, and **Computer Vision**.

---

## 🚀 Project Overview

This project allows users to input a text prompt (e.g., *"a futuristic city at sunset"*) and generates visually realistic or artistic images using **diffusion-based generative models**.

It is designed as a **learning-focused Generative AI project**, ideal for students and developers exploring **text-to-image models**.

---

## ✨ Features

* Generate AI images from text prompts
* Powered by **Stable Diffusion**
* Uses **Hugging Face Diffusers** pipeline
* Customizable image resolution & styles
* Fast inference with GPU support (optional)
* Beginner-friendly project structure

---

## 🧠 Technologies Used

* Python
* Hugging Face Diffusers
* Transformers
* PyTorch
* Stable Diffusion
* Generative AI

---

## 📂 Project Structure

```
Text-To-Image-Generation/
│
├── requirements.txt        # Dependencies
├── outputs/                # Generated images
├── README.md               # Project documentation

```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Ujjval009/TEXT-TO-IMAGE-GEN.git
cd text-to-image-gen
```

### 2️⃣ Create Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---



## 🧩 Example Code Snippet

```python
from diffusers import StableDiffusionPipeline
import torch

pipe = StableDiffusionPipeline.from_pretrained(
    "runwayml/stable-diffusion-v1-5"
).to("cuda")

prompt = "A futuristic robot painting art"
image = pipe(prompt).images[0]
image.save("output.png")
```

---

## 💡 Use Cases

* AI Art & Creativity
* Graphic Design Assistance
* Content Creation
* Concept Visualization
* Generative AI Learning

---

## 🧠 Learning Outcomes

* Understand diffusion-based generative models
* Learn Hugging Face pipelines
* Apply deep learning for image synthesis
* Gain practical Generative AI experience

---

## 📌 Future Improvements

* Add web UI (Streamlit / Gradio)
* Support multiple artistic styles
* Prompt enhancement using LLMs
* Batch image generation

---

## 👨‍💻 Author

**Ujjval Sharma**
Engineering Student | Generative AI Learner

