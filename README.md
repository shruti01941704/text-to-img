 # Text2Image – AI Powered Image Generator

**Text2Image** is a Python-based application that generates images from text prompts using Stable Diffusion.
It provides a simple graphical interface where users can enter a description and the AI model generates an image based on the prompt.

This project demonstrates the power of Generative AI and diffusion models to convert natural language descriptions into visual content.

---

## 📑 Table of Contents

- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
  - [Usage](#usage)
- [Example Outputs](#example-outputs)
- [Contributing](#contributing)

---

## 🚀 Key Features
- **Text-to-Image Generation**: Generate images directly from natural language prompts.

- **Stable Diffusion Integration**: Uses the Stable Diffusion model through the Diffusers library to create high-quality images.

- **Simple GUI Interface**:User-friendly graphical interface built using Tkinter / CustomTkinter.

- **Fast Image Generation**:Supports GPU acceleration using PyTorch for faster generation.

- **Prompt-Based Control**:Users can generate different styles of images by changing the text prompt.

- **Real-Time Image Display**:Generated images are displayed instantly inside the application window.

---

## 🛠️ Technology Stack

### Programming Language
- **Python**: Primary language used for developing the application and implementing the AI model.

### AI / Machine Learning
- **Stable Diffusion**: Deep learning model used to generate images from text prompts.
- **PyTorch**: Machine learning framework used for loading and running the diffusion model.
- **Diffusers (Hugging Face)**: Library that provides pre-trained diffusion models and pipelines.

### GUI
- **Tkinter**: Built-in Python library used to create the graphical user interface.
- **CustomTkinter**: Enhanced version of Tkinter used to design a modern and attractive UI.

### Image Processing
- **Pillow**: Python imaging library used for handling and displaying generated images.

---

## 📁 Project Structure

```
text-to-image-generator
│
├── imagegenerator.py
├── main.py
├── requirements.txt
├── README.md
└── generated_images
```
--- 

## 🏁 Getting Started

Follow these steps to run the project locally.

### 📌 Prerequisites

Ensure the following are installed:

- **Python 3.6 or later**
- **pip package manager**
- **GPU (recommended for faster generation)**

### 📚 Required Libraries

Install the following Python libraries:

- **torch**
- **diffusers**
- **pillow**
- **tkinter**
- **customtkinter**

---

## ⚙️ Installation

### 1️. Clone the Repository

```bash  
https://github.com/your-username/text-to-image-generator.git
cd text-to-image-generator

```
### 2️. Create a Virtual Environment

```bash
python -m venv venv

```
Activate the virtual environment:

Windows: 

```bash
venv\Scripts\activate
```
Mac / Linux:

```bash
source venv/bin/activate
```

### 3️. **Install Dependencies**:

pip install torch torchvision diffusers pillow customtkinter

---

## Running the Application:
  
  Run the following command:
  
  ```bash
  python imagegenerator.py
  ```
---

## 💡 Usage

1. Run the application.

2. Enter a text prompt describing the image.

3. Click the Generate Image button.

4. The Stable Diffusion model generates an image based on the prompt.

5. The generated image will appear in the GUI window.

---

## 🤝 Contributing

Contributions are welcome!

### Steps to contribute:

1. Fork the repository

2. Clone the forked repository

3. Make your changes

4. Commit and push the changes

5. Create a Pull Request

---

## Example Outputs:

Explore this stunning architectural layout that brings your dream home to life! This image intricately details each room's dimensions and flow, offering a clear vision for a beautifully functional living space

![LINE PLAN](https://github.com/user-attachments/assets/babcf006-6ce1-4b02-bce3-fb8a5b0b4233)

---

**Rich Image Generation Example**:

![rich img 1](https://github.com/user-attachments/assets/0b502b0c-9752-4e02-9dd2-9ecab1e82d2d)

Prompt: A mystical castle floating in the sky.

Original image

![WhatsApp Image 2024-10-18 at 11 37 04_6d67f01a](https://github.com/user-attachments/assets/e284706f-03c6-4c29-9078-5ec04c06b210)


Modified images

![Grayscale](https://github.com/user-attachments/assets/750b5186-7d9d-4310-ad13-2112eaddec7a)


