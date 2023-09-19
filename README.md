# Background Removal using `rembg`

## Introduction

This Python script demonstrates how to use the `rembg` library to remove the background from an image. This can be useful for various applications, including image processing and graphic design.

## Requirements

Before running the script, make sure you have the following requirements installed:

- Python 3.x
- [rembg](https://pypi.org/project/rembg/): The background removal library.
- [Pillow](https://pypi.org/project/Pillow/): A Python Imaging Library that we use to load and save images.

You can install these packages using `pip`:

```bash
pip install rembg Pillow

Usage
Place the image you want to process in the same directory as the script or provide the path to your image in the input_path variable.

Open the terminal and navigate to the directory containing the script.

Run the script:
python background_removal.py
The script will remove the background from the image and save the result in the same directory as output.png.
Configuration
You can configure the script by modifying the following variables in the script:

input_path: The path to the input image you want to process.
output_path: The path where the processed image will be saved.