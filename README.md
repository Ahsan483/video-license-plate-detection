# 🎥 Video License Plate Detection (Python + OpenCV)

This project attempts to **extract and read vehicle license plates from video footage**
using **OpenCV image processing techniques and Tesseract OCR**.

It is designed for **CCTV / dashcam / surveillance videos**, especially where
license plates are partially visible and require enhancement.

> ⚠️ Important: This project does **not guess or reconstruct** missing plate numbers.
It only extracts text if readable pixel data exists.

---

## 🚀 Features

- Frame-by-frame video processing
- License plate region detection using contours
- Contrast enhancement with CLAHE
- Noise reduction and edge detection
- OCR using Tesseract
- Debug mode that saves detected plate images
- Works on videos (not only images)

---

## 🧠 How It Works

1. Loads a video file
2. Extracts frames sequentially
3. Converts frames to grayscale
4. Enhances contrast and reduces noise
5. Detects rectangular contours (license plate candidates)
6. Applies OCR to detected regions
7. Prints detected plate numbers (if any)
8. Saves plate images for manual inspection

---

## 📁 Project Structure

