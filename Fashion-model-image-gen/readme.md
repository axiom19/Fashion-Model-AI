# FMIG - Fashion Model Image Generator

## Description

**FMIG** (Fashion Model Image Generator) is a Jupyter Notebook that implements a text-to-image generation app specifically for fashion modeling. It allows brands and designers to create realistic images of models wearing specific clothing styles based on a given text prompt.

This project leverages **diffusion models** to transform text descriptions into high-quality, photorealistic images, providing a virtual environment to visualize fashion concepts without the need for physical photoshoots. Users can specify attributes like model appearance, clothing, and surroundings, and the system will generate an image that matches the description.

This tool is highly beneficial for fashion designers and marketing teams looking to bring ideas to life in a digital form quickly.

## Notebook Workflow

The notebook follows these main steps:

1. **Introduction**: Overview of the Fashion Model Image Generator and how it operates.
2. **Setup & Installation**: Install required libraries (`diffusers`, `transformers`, and `torch`).
3. **Model and Data Preparation**: The notebook utilizes **Stable Diffusion** models, which are popular for generating high-quality, photorealistic images from textual descriptions.
4. **Image Generation**: Generates photorealistic images of fashion models based on user-provided text prompts, such as descriptions of clothing, style, and appearance.
5. **Visualization**: Displays the generated images for review, adjustment, or further creative exploration.

## Demo

![Demo Screenshot](https://github.com/axiom19/Fashion-Model-AI/blob/main/Fashion-model-image-gen/demo_img.png)
![Demo Video]((https://github.com/axiom19/Fashion-Model-AI/blob/main/Fashion-model-image-gen/demo_vid.png))


## Requirements

The notebook requires the following dependencies:
- Python 3.x
- Jupyter Notebook
- `diffusers`: For handling diffusion models.
- `transformers`: For text input handling and processing.
- `torch`: The deep learning framework used to run the model.
- `gradio`: To create an easy front end


## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/axiom19/Fashion-Model-AI/Fashion-model-image-gen.git

2. Launch Jupyter Notebook
3. Open the FMIG.ipynb file and run the cells to generate fashion model images from text prompts.
