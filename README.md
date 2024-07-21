# Calorie Counter Application using Diffusion Model and Vision Transformer

## Overview

This project is a web application designed to estimate the calorie content of food items from images. It leverages a diffusion model and Vision Transformer (ViT) to identify food items and fetches their nutritional information using an external API. The application is built with Gradio for the user interface and is deployed on Hugging Face Spaces.

## Features

- Automated food item identification from images
- Real-time fetching of nutritional information using an external API
- User-friendly interface for uploading images and displaying nutritional data

## Technologies Used

- Python
- PIL (Python Imaging Library)
- Vision Transformer (ViT)
- Gradio
- Transformers
- Torch
- Torchvision
- Requests
- Hugging Face Spaces

## Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/calorie-counter-app.git
   cd calorie-counter-app
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
.
├── app.py                   # Main application file
├── requirements.txt         # List of required packages
├── .env                     # File for storing environment variables (API key)
└── README.md                # This README file
Usage
Upload an image of the food item.
The application identifies the food item and fetches its nutritional information.
The nutritional information is displayed in a user-friendly format.
Deployment
The application is deployed on Hugging Face Spaces and can be accessed here.

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Hugging Face for providing the Vision Transformer model and deployment platform
Gradio for the easy-to-use interface
API Ninjas for the nutritional information API
