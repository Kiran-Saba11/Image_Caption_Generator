# 🖼️ BLIP Image Captioning

## 📌 Project Overview

This project uses **BLIP (Bootstrapping Language-Image Pre-training)** to generate natural-language captions for images using a pretrained deep learning model from Hugging Face.

The project is built with Python and allows users to generate captions in two ways: **conditional image captioning**, where a text prompt guides the model, and **unconditional image captioning**, where the model generates a caption directly from the image.

## 🎯 Objectives

- Generate meaningful descriptions of images.
- Explore computer vision and multimodal AI.
- Learn how pretrained transformer models work.
- Practice using Hugging Face Transformers.

## 🛠️ Technologies Used

- Python
- Hugging Face Transformers
- Salesforce BLIP Image Captioning Base
- PyTorch
- Pillow (PIL)
- Requests

## 🤖 Model Information

**Model:** `Salesforce/blip-image-captioning-base`

BLIP is a vision-language model that understands image content and generates text descriptions.

Model page: https://huggingface.co/Salesforce/blip-image-captioning-base

## ⚙️ Installation

Install the required Python libraries:

```bash
pip install requests pillow transformers torch
```

## 🚀 How to Run

1. Open your Jupyter Notebook or Python environment.
2. Install the required libraries.
3. Run the Python code.
4. The pretrained BLIP model will load automatically.
5. The image will be downloaded from the provided URL.
6. The model will generate and print captions.

Make sure the image URL is publicly accessible.

## 🧠 Captioning Methods

### 1. Conditional Image Captioning

The model receives an image and a text prompt, such as:

```python
text = "a photography of"
```

The prompt guides the model when generating a caption.

### 2. Unconditional Image Captioning

The model receives only the image and generates a description without a text prompt.

## 📂 Project Structure

```text
BLIP-Image-Captioning/
│
├── image_captioning.py
├── README.md
└── requirements.txt
```

If you're using a Jupyter Notebook, you can replace `image_captioning.py` with `image_captioning.ipynb`.

## 💡 Applications

- Automatic image description
- Accessibility support for visually impaired users
- Image organization and search
- Educational AI projects
- Computer vision research
- Image understanding applications

## 📚 Learning Outcomes

Through this project, I explored pretrained vision-language models, image preprocessing, transformer-based text generation, and the use of Hugging Face tools for practical AI applications.

## 🔮 Future Improvements

- Build a simple web interface using Gradio.
- Allow users to upload their own images.
- Compare captions generated from different prompts.
- Add support for multiple images.
- Improve the user experience with an interactive interface.

## 👩‍💻 Author

**Kiran Saba**

AI Student | Exploring Artificial Intelligence, Machine Learning, and Computer Vision.

## 📄 License

This project is intended for educational and learning purposes. Check the model's license and terms before redistributing or deploying it commercially.
