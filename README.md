# Image Text Extraction using Qwen2-VL

This project extracts text from images using the Qwen2-VL model from Hugging Face. The extracted text is saved as `.txt` files with filenames matching the corresponding input images.

## Features
- Uses Qwen2-VL model for text extraction
- Supports multiple image formats
- Saves extracted text as `.txt` files with matching filenames
- Runs on Google Colab with a T4 GPU

## Installation
No installation is required as this project runs on Google Colab. Ensure that you have a Google account and access to a Colab notebook.

## Data Preparation
1. **Create a `data` Folder**
   - Place all the input images inside the `data` folder.

2. **Input Images**
   - Supported formats: `.jpg`, `.png`, `.jpeg`
   - Ensure that images have clear text for better extraction accuracy.

## Running the Project
1. Upload the project notebook (`text_extraction.ipynb`) to Google Colab.
2. Upload the `data` folder containing input images to your Colab environment.
3. Run the notebook cells sequentially.
4. Extracted text files will be saved in the `output` folder with filenames matching the input images.

## Output
- Extracted text is saved as `.txt` files in the `output` folder.
- Each `.txt` file corresponds to an input image with the same filename.

## Repository Name Suggestion
**image-text-extractor**

## License
This project is open-source and free to use under the MIT License.

