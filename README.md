# Menu Reader 🍽️📸

**Menu Reader** identifies restaurant menus from images and extracts text to create a virtual menu.  
Leveraging a pretrained Deep Learning model to classify images as menus or non-menus and Google Tesseract for OCR.

---

## 🚀 Features

- **Image classification**: Recognizes if an uploaded picture is a restaurant menu.
- **OCR extraction**: Converts menu images into structured text.

---

## 📂 Project Structure
Menu_Reader/ ├── data/ │ └── raw_images/ # Input images │ ├── notebooks/ │ ├── 1_menu_detection_ocr.ipynb │ └── [other notebooks] │ ├── models/ │ └── [saved models and embeddings] │ ├── api/ │ ├── app.py │ └── requirements.txt │ └── README.md
