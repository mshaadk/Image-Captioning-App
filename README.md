# Image Captioning App

## Overview

The **Image Captioning App** leverages the power of pre-trained deep learning models to generate descriptive captions for uploaded images. This web application is built using Streamlit and utilizes the VisionEncoderDecoderModel from the Hugging Face Transformers library to provide detailed captions based on image content.

## Features

- **Image Upload**: Allows users to upload an image in JPEG, PNG, or JPG format.
- **Caption Generation**: Uses a pre-trained VisionEncoderDecoderModel to generate descriptive captions for the uploaded image.
- **Display Captions**: Shows the generated captions below the uploaded image.

## Requirements

To run this application, you'll need the following Python packages:
- `streamlit`
- `transformers`
- `torch`
- `PIL` (Pillow)

You can install the required packages using pip:

```bash
pip install streamlit transformers torch pillow
```

## Usage
### 1. Clone the Repository

```bash
git clone https://github.com/mshaadk/Image-Captioning-App.git
cd Image-Captioning-App
```

### 2. Run the Application

Start the Streamlit server by running:

```bash
streamlit run app.py
```

This will open the application in your default web browser.

### 3. Upload an Image

- Click on the "Choose an image..." button to upload an image file.
- The application will process the image and display the generated captions below it.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please submit a pull request or open an issue.

## Contact
For questions or inquiries, please contact [Mohamed Shaad](https://www.linkedin.com/in/mohamedshaad/).
