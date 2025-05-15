
# Diffusion Model from Scratch

This repository contains the implementation of a diffusion model built from scratch. The project involves designing the architecture, modifying weights, and training the model for image generation and related tasks.

## Project Structure

- `model/`  
  Contains all the code of the model.

- `Data/`  
  Contains the vocab and merge file.


## Installation


```bash
git clone https://github.com/09-prince/StableDiffusion.git
cd StableDiffusion
```

```bash
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
uv pip install -r requirements.txt
```

Download v1-5-pruned-emaonly.ckpt and add into the Data folder
```bash
https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5/tree/main 

```


## How to use

- Use model/generate_image.ipynb for generating images. 
- Give the prompt according to you there are 2 code file one for text-text and other for image-image
- For understanding the Hyperparameters use the model/pipleline.py