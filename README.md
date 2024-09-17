
# Neural Style Transfer with Gradio Interface

This project implements neural style transfer using TensorFlow and provides a user-friendly interface with Gradio to perform style transfer between two images. The application allows you to upload a content image and a style image and generates a stylized version of the content image based on the style image.

## Features
- Upload your content and style images.
- View and download the stylized image.
- Powered by TensorFlow's VGG19 pre-trained model for style and content extraction.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Required Python packages (see [requirements.txt](requirements.txt))

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/neural-style-transfer.git
   cd neural-style-transfer
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

After installing the dependencies, you can run the Gradio interface:

```bash
python app.py
```

The application will launch in your default web browser. You can now upload a content image and a style image to generate the stylized image.

### Usage

1. Upload the **Content Image** that you want to stylize.
2. Upload the **Style Image** that you want to apply to the content image.
3. Click "Submit" to generate and view the stylized image.
4. You can download the generated image.

### Project Structure

- `app.py`: The main script that runs the Gradio interface.
- `requirements.txt`: List of dependencies required for the project.
- `README.md`: Documentation for the project.

## Acknowledgements

This project uses the VGG19 pre-trained model from TensorFlow for feature extraction. Special thanks to the Gradio team for providing an easy-to-use interface for machine learning applications.
```
