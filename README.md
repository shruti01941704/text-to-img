Text2Image is a Python-based application that generates images from text prompts using Stable Diffusion.
It provides a simple GUI where users can enter a description and the AI model will generate a corresponding image.

This project demonstrates the power of Generative AI and diffusion models to convert natural language descriptions into visual content.

📑 Table of Contents

Key Features

Technology Stack

Project Structure

Getting Started

Prerequisites

Installation

Running the Application

Usage

Contributing

🚀 Key Features

Text-to-Image Generation
Generate high-quality images from natural language prompts.

Stable Diffusion Integration
Uses the powerful Stable Diffusion model through the Diffusers library.

Simple GUI Interface
Built using Tkinter / CustomTkinter for easy user interaction.

Fast Image Generation
Utilizes PyTorch GPU acceleration when available.

Prompt-Based Control
Users can customize images by entering different descriptive prompts.

Real-time Image Display
Generated images are displayed instantly inside the GUI window.

🛠️ Technology Stack
Programming Language

Python

AI / Machine Learning

Stable Diffusion

PyTorch

Diffusers (Hugging Face)

GUI

Tkinter

CustomTkinter

Image Processing

Pillow

📁 Project Structure
text-to-image-generator
│
├── imagegenerator.py       # Main application file
├── requirements.txt        # Project dependencies
├── README.md               # Project documentation
└── generated_images        # Folder for storing generated images
🏁 Getting Started

Follow these steps to run the project locally.

📌 Prerequisites

Make sure you have the following installed:

Python 3.6 or later

GPU (recommended for faster generation)

pip package manager

Required Python libraries:

torch

diffusers

pillow

tkinter

customtkinter

⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/text-to-image-generator.git
cd text-to-image-generator
2️⃣ Create a Virtual Environment
python -m venv venv

Activate the virtual environment:

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate
3️⃣ Install Dependencies
pip install torch torchvision diffusers pillow customtkinter
🔑 Hugging Face API Token Setup

This project requires a Hugging Face API Token.

Steps to generate a token:

Go to https://huggingface.co/

Sign in or create an account

Click on your Profile → Settings

Open the Access Tokens tab

Click Generate New Token

Copy the generated token

Add the token inside your code:

self.authorization_token = "YOUR_HUGGINGFACE_TOKEN"
▶️ Running the Application

Run the following command:

python imagegenerator.py
💡 Usage

Start the application.

Enter a text prompt describing the image you want.

Click the Generate Image button.

The Stable Diffusion model will generate the image.

The generated image will appear in the GUI window.

Example prompt:

A futuristic city at sunset with flying cars and neon lights
🤝 Contributing

Contributions are welcome!

Steps to contribute:

Fork this repository

Clone your forked repository

Make the necessary changes

Commit and push your changes

Create a Pull Request

Explore this stunning architectural layout that brings your dream home to life! This image intricately details each room's dimensions and flow, offering a clear vision for a beautifully functional living space

![LINE PLAN](https://github.com/user-attachments/assets/babcf006-6ce1-4b02-bce3-fb8a5b0b4233)


![rich img 1](https://github.com/user-attachments/assets/0b502b0c-9752-4e02-9dd2-9ecab1e82d2d)

Prompt: A mystical castle floating in the sky.

Original image

![WhatsApp Image 2024-10-18 at 11 37 04_6d67f01a](https://github.com/user-attachments/assets/e284706f-03c6-4c29-9078-5ec04c06b210)


Modified images



![Grayscale](https://github.com/user-attachments/assets/750b5186-7d9d-4310-ad13-2112eaddec7a)
