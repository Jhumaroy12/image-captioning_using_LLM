# Image Caption Generator using LLM (ViT-GPT2)

This project uses a Vision Transformer (ViT) encoder and a GPT2 decoder from Hugging Face to generate captions for images. It's wrapped with a Gradio interface so you can test it out by uploading any image.

---

## Features

- Uses `nlpconnect/vit-gpt2-image-captioning` from Hugging Face
- Gradio-powered UI for easy interaction
- Automatically generates natural language captions for images
- Compatible with CPU and GPU

---

## Model Architecture

- **Encoder**: ViT (Vision Transformer)
- **Decoder**: GPT2
- Trained on the COCO dataset by the model creator

---

## Requirements

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## How to Use

1. Clone this repository:
```bash
git clone https://github.com/your-username/image-caption-generator.git
cd image-caption-generator
```

2. Launch the notebook:
```bash
colab notebook image_caption_generator.ipynb
```

3. Run all cells and use the image uploader to get a caption.

---

## Gradio App (Optional)

If deployed, this could run at Gradio

---


