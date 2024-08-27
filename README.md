# Image Captioning and Object Detection App

This project is an AI-powered web application that generates captions for images and detects objects within them using state-of-the-art machine learning models. Built with Streamlit, LangChain, and Transformers, the app offers a user-friendly interface for seamless interaction.

## Features

- **Image Captioning:** Automatically generates descriptive captions for images using the BLIP model.
- **Object Detection:** Identifies and lists objects in the image with bounding box coordinates and confidence scores using the DETR model.
- **Context-Aware Descriptions:** Utilizes LangChain to provide context-enhanced captions and object detection results.
- **Web Interface:** Streamlit-powered UI for easy input of image URLs and display of results.

## Technologies Used

- **Streamlit:** Web application framework for building the interface.
- **LangChain:** Framework for creating interactive agents and managing memory.
- **Transformers:** Hugging Face models used for image captioning and object detection (BLIP and DETR).
- **PIL (Pillow):** For image processing.
- **Requests:** For fetching images from provided URLs.

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/image-captioning-object-detection-app.git

   ```

2. Navigate to the project directory:

   ```bash
   cd image-captioning-object-detection-app

   ```

3. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use      `venv\Scripts\activate`

   ```

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

   ```

5. Create a .env file in the root directory and add your OpenAI API key:
   ```text
   OPENAI_API_KEY=your_openai_api_key
   ```

## Usage

1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Open your browser and go to http://localhost:8501.
3. Enter an image URL and optionally add some context in the text area.
4. Click "Generate Image Caption" to see the caption and detected objects.
