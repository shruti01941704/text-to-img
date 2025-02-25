Clone the repository:

git clone https://github.com/your-username/text to img 
cd your-repo-name


Create a virtual environment and install dependencies:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install torch torchvision diffusers pillow tkinter


Run the application:
python main.py

This project uses the Stable Diffusion Pipeline to generate images from text prompts. The Stable Diffusion Pipeline is a machine learning model that uses a diffusion process to generate images from text prompts. This is a simple GUI application for generating images based on user prompts using the StableDiffusionPipeline model from the diffusers module. The application allows users to enter a prompt, click a button to generate an image based on the prompt, and view the generated image in the GUI window.

To get started, you will need to have a GPU and install the following dependencies:

PyTorch
diffusers

Before running this application, you will need to have the following installed:

Python 3.6 or later
tkinter module
customtkinter module
diffusers module
torch module
Pillow module

You can install these dependencies using pip. For example:

pip install tkinter
pip install customtkinter
pip install diffusers
pip install torch
pip install Pillow

To run this file you need a HuggingFace API Token.

Go to the Hugging Face website: https://huggingface.co/
Click on the "Sign In" button in the top-right corner of the page.
Sign in with your Hugging Face account or create a new account if you don't have one.
Once you are signed in, click on your profile picture in the top-right corner of the page and select "Account settings" from the dropdown menu.
On the account settings page, click on the "API token" tab.
Click on the "Generate new token" button to create a new authorization token.
Enter a name for your token in the "Token name" field (e.g. "Image Generator App").
Choose the permissions you want to grant to your token (e.g. "Read-only" or "Full access").
Click on the "Generate" button to create your token.
Copy the generated token and use it in your Python code where it says self.authorization_token = "".
Once you have installed the dependencies, you can run the code by running the following command:

python imagegenerator.py
Usage
When you run the code, you will be prompted to enter a text prompt. Once you have entered a text prompt, the Stable Diffusion Pipeline will generate an image based on the text prompt. The generated image will be displayed using matplotlib.

image

Contributing
We welcome contributions to this project! If you would like to contribute, please follow these steps:

Fork this repository to your own GitHub account.
Clone the forked repository to your local machine.

Make changes to the code as needed.
Test your changes to make sure they work as expected.
Commit your changes and push them to your forked repository.
Create a pull request on the original repository to submit your changes.


Explore this stunning architectural layout that brings your dream home to life! This image intricately details each room's dimensions and flow, offering a clear vision for a beautifully functional living space

![LINE PLAN](https://github.com/user-attachments/assets/babcf006-6ce1-4b02-bce3-fb8a5b0b4233)


![rich img 1](https://github.com/user-attachments/assets/0b502b0c-9752-4e02-9dd2-9ecab1e82d2d)

Prompt: A mystical castle floating in the sky.

Original image

![WhatsApp Image 2024-10-18 at 11 37 04_6d67f01a](https://github.com/user-attachments/assets/e284706f-03c6-4c29-9078-5ec04c06b210)


Modified images



![Grayscale](https://github.com/user-attachments/assets/750b5186-7d9d-4310-ad13-2112eaddec7a)
