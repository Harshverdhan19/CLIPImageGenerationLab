# CLIP Image Generation Lab

A toolkit for creating detailed images using CLIP and VQGAN, harnessing the power of transformers for image synthesis.

## Overview
This project combines OpenAI's CLIP and CompVis's VQGAN models to generate detailed images based on textual descriptions. It demonstrates the intersection of natural language processing and image generation, showcasing the capabilities of transformer models in creative applications.

## Setup
- Clone the repository
- Install required dependencies
- Follow the setup instructions for CLIP and VQGAN submodules

## Usage
- Prepare your text prompts
- Run the image generation script
- View the generated images

## Example
Here's a quick start example to generate an image:
```python
from image_gen import generate_image
image = generate_image("A painting of a pineapple in a bowl")
