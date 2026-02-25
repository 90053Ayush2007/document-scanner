# 📄  Document Scanner using OpenCV

A Python-based document scanning tool that allows **manual ROI cropping** on high-resolution images using OpenCV, followed by optional image enhancement and **multi-page PDF generation**.

This project mimics the core functionality of apps like CamScanner, with full user control over cropping and output format.

---

## ✨ Features

- 🖱️ Manual document cropping using OpenCV (`cv2.selectROI`)
- 📐 Supports high-resolution images with scaled preview
- 🎨 Output modes:
  - Color (original)
  - Grayscale
  - Binary (scanner-style)
- 🧾 Multi-image PDF generation
- 🧠 Intelligent file naming (`scanned.png`, `scanned(1).png`, `test.pdf`, `test(1).pdf`)
- 💻 Works reliably in Jupyter Notebook and Python scripts

---

## 📂 Project Structure
document-scanner/
│
├── input_images/ # Place raw images here (ignored by git)
├── scans/ # Generated images and PDFs (ignored by git)
├── scanner.ipynb # Main notebook
├── requirements.txt
├── README.md
└── .gitignore

---

## 🛠️ Tech Stack

- Python 3
- OpenCV
- NumPy
- Pillow
- Jupyter Notebook

---

## 🚀 How to Run

### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt
