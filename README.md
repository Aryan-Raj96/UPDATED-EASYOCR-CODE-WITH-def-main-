# EasyOCR Image-to-Text with `main()` Function

## 📌 Project Overview

This project demonstrates an **Image-to-Text (OCR) pipeline** using **EasyOCR** and **OpenCV** in Python.
The code is structured using a **`main()` function** to clearly define the program entry point, following **industry-standard Python practices**.

This repository was created as part of an **AI/ML internship task** to show:

* Clean code structure
* Proper program flow
* Practical OCR implementation

---

## 🚀 Features

* Image preprocessing for better OCR accuracy
* Text extraction using EasyOCR
* Dictionary-based text cleaning (Indian English support)
* Bounding box visualization for detected text
* Clean and readable Python structure using `def main()`

---

## 🛠️ Technologies Used

* **Python 3**
* **EasyOCR**
* **OpenCV (cv2)**
* **NumPy**
* **Matplotlib**
* **PyEnchant (en_IN / en_GB dictionary)**

---

## 📁 Project Structure

```
UPDATED-EASYOCR-CODE-WITH-def-main/
│
├── def ocr.py        # Main OCR script with main() function
├── pointer.jpg      # Sample input image
├── README.md        # Project documentation
```

---

## ▶️ How to Run

### 1️⃣ Install Dependencies

```bash
pip install easyocr opencv-python matplotlib numpy pyenchant
```

### 2️⃣ Run the Program

```bash
python "def ocr.py"
```

> Make sure `pointer.jpg` is present in the same directory.

---

## 🧠 Why `def main()` is Used

The `main()` function:

* Clearly shows **where program execution starts**
* Separates helper functions from execution logic
* Prevents accidental execution when the file is imported
* Improves readability and maintainability

```python
if __name__ == "__main__":
    main()
```

This is a **standard Python best practice** followed in real-world projects.

---

## 🔄 OCR Pipeline

1. Load input image
2. Convert to grayscale
3. Apply flattening and contrast enhancement
4. Perform OCR using EasyOCR
5. Clean extracted text using dictionary rules
6. Display detected text with bounding boxes

---

## 📊 Output

* Raw OCR text
* Cleaned text output
* Total detected text regions
* Visual output with bounding boxes

---

## 🎯 Learning Outcomes

* Understanding OCR workflows
* Importance of preprocessing in computer vision
* Writing clean and structured Python code
* Using `main()` as a program entry point

---

## 🔮 Future Improvements

* Web interface using Flask
* Image upload from frontend
* Confidence-based text filtering
* Deployment as an OCR service

---

## 👤 Author

**Aryan Raj**
AI/ML Intern Aspirant | Computer Vision Learner

---

## 📜 Note

This project is created for **educational and internship evaluation purposes**.

---

⭐ *Feel free to star the repository if you find it useful!*
