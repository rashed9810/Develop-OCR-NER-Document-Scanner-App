## Develop-OCR-NER-Document-Scanner-App

**A web application for intelligently extracting text and data from business cards.**

**Description:**

This web application utilizes Optical Character Recognition (OCR), Named Entity Recognition (NER), and image processing techniques to streamline the process of extracting key information from business cards. Users can upload their business card images, and the app automatically extracts entities such as:

* Person Name
* Designation
* Organization
* Phone Number
* Email
* Website/URL

**Features:**

* Automatic text extraction from business card images
* Entity recognition using a trained NER model
* Visualization of recognized entities with bounding boxes
* Manual adjustment of bounding boxes (using JavaScript canvas)
* User-friendly interface for easy interaction

**Getting Started:**

**Prerequisites:**

* Python 3.x
* pip
* OpenCV
* PyTesseract
* Spacy
* Flask

**Installation:**

1. Clone this repository.
2. Install the required libraries:

```bash
pip install opencv-python pytesseract spacy flask
```

3. Download a pre-trained language model for Spacy (e.g., `en_core_web_sm`).

**Usage:**

1. Run the application:

```bash
python app.py
```

2. Open http://127.0.0.1:5000/ in your web browser.
3. Upload your business card image.
4. Adjust the bounding box coordinates if needed using the provided canvas.
5. Click "Extract Text" to obtain the extracted entities and their locations.

**Contributing:**

We welcome contributions to this project! Please refer to the `CONTRIBUTING.md` file for guidelines.

**License:**

This project is licensed under the MIT License. See the `LICENSE` file for details.

**Authors:**

* Rashed

**Contact:**

Feel free to contact us with any questions or feedback at rashed.bcse.edu@gmail.com

**Additional Information:**

This project is a basic implementation and can be further enhanced with features such as:

* Support for various document formats
* Improved text extraction accuracy with advanced OCR techniques
* Integration with contact management systems
* Multilingual support
