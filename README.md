![alt text](<readme image.jpg>)

# FLUX.1 Image Generation

This Python script demonstrates how to use the FLUX.1 AI model from Black Forest Labs to generate images based on text prompts.

## Prerequisites

Before you begin, ensure you have the following installed:
- **Python 3.7+**: Make sure you have Python 3.7 or higher installed on your system.
- **PyTorch**: A powerful library for machine learning and deep learning.
- **diffusers library**: A library for diffusion models, required for image generation.

## Installation

Follow these steps to get your environment set up:

1. **Clone this Repository**: Use the command below to clone the repository to your local machine:
    ```bash
    git clone https://github.com/WanjaoColins/GenAI-FluxModel.git
    ```

2. **Navigate to the Directory**: Change your working directory to the repository folder:
    ```bash
    cd flux1-image-generation
    ```

3. **Install Dependencies**: Install the required Python packages using pip:
    ```bash
    pip install torch diffusers
    ```

## Usage

To generate images using the FLUX.1 model, follow these steps:

1. **Prepare Your Text Prompt**: Write a descriptive text prompt for the image you want to generate.

2. **Run the Script**: Execute the Python script with your text prompt as an argument:
    ```bash
    python generate_image.py "Your descriptive text prompt here"
    ```

   Replace `"Your descriptive text prompt here"` with your actual prompt.

3. **View the Output**: The generated image will be saved in the `output` directory by default. Check the `output` folder to view your image.

## Troubleshooting

- **Issue: `ModuleNotFoundError`**: Ensure all dependencies are installed correctly. Try reinstalling the packages with `pip install --upgrade torch diffusers`.
- **Issue: Model not loading**: Check your internet connection and ensure you have access to the FLUX.1 model files.


## Contact

For any questions or support, please contact:

- **Author**: [Colins Wanjao]
- **Email**: [Colins.Wanjao@outlook.com](mailto:Colins.Wanjao@outlook.com)

---

Happy image generation with FLUX.1!
