# Text-to-Multiple-Model-Images
# Text-to-Image Generator (Gradio + Hugging Face)

## Overview
This project is a **Gradio-based web interface** for generating images from text prompts using various Hugging Face models. Users can select a model from a dropdown menu or generate images from all available models at once.
# Code file 
## **https://colab.research.google.com/drive/1TyUaQt1aasgAG5sv0YYx_efI70AF4U6C#scrollTo=eBVS__387236**
## Features
- 🔹 **Supports 5 Text-to-Image Models**
- 🔹 **Dropdown Menu** for Model Selection
- 🔹 **Generate Images from a Single or All Models**
- 🔹 **Gallery View for Multiple Outputs**
- 🔹 **Download Option for Generated Images**

## Setup & Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/text-to-image-generator.git
   cd text-to-image-generator
   ```

2. **Install Required Dependencies:**
   ```bash
   pip install gradio huggingface_hub PILLOW
   ```

3. **Run the Gradio Interface:**
   ```bash
   python app.py
   ```

4. **Access the Web Interface:**
   Open the provided `localhost` link in your browser.

## Usage
- Enter a text prompt describing the desired image.
- Select a model from the dropdown list.
- Click **Generate Image** to create an image with the selected model.
- Click **Generate from All Models** to compare outputs from all models.
- Click on an image to download it.

## Models Used
- **FLUX.1-schnell** (`black-forest-labs/FLUX.1-schnell`)
- **FLUX.1-dev** (`black-forest-labs/FLUX.1-dev`)
- **Stable Diffusion 3.5** (`stabilityai/stable-diffusion-3.5-large`)
- **CogView4-6B** (`THUDM/CogView4-6B`)
- **Flux-Midjourney-Mix2-LoRA** (`strangerzonehf/Flux-Midjourney-Mix2-LoRA`)

## License
This project is open-source under the MIT License.

## Author
Developed by **Meruva Peddababu**. Feel free to contribute and enhance the project!

---
🚀 **Happy Image Generating!** 🚀

