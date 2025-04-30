# Menu Reader 🍽️📸

**Menu Reader** identifies restaurant menus from images and extracts text to create a virtual menu.  
Leveraging a pretrained Deep Learning model to classify images as menus or non-menus and Google Tesseract for OCR.

---

## 🚀 Features

- **Image classification**: Recognizes if an uploaded picture is a restaurant menu.
- **OCR extraction**: Converts menu images into structured text.

---


## 📂 Project Structure

```text
Menu_Reader/
├── data/
│   └── raw_images/      # Input images
├── notebooks/
│   ├── 1_menu_detection_ocr.ipynb
│   └── ...
├── models/
│   └── ...
├── api/
│   ├── app.py
│   └── requirements.txt
├── flutter_app/
│   └── ...
└── README.md
```

---

## ⚙️ Installation

**Requirements:**
```bash
pip install tensorflow keras numpy pandas matplotlib pillow pytesseract opencv-python
```

### OCR:

- Install Google Tesseract OCR

- Ensure Tesseract is added to your system PATH.

---


## 🖥️ Usage
1- Place images into data/raw_images.

2- Run notebooks in the notebooks/ directory.

---
## 📌 To-Do & Future Goals
 1 Train menu-item classification model.

 2 Categorize menu items using NLP.

 3 Deploy API with Flask.

 4 Integrate with Flutter for mobile app.

