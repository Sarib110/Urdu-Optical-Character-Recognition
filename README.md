# Urdu OCR  

This repository provides resources for generating Urdu words, creating images, and applying deep learning models for **Optical Character Recognition (OCR)**.  

---

## 📌 Project Overview  

The Urdu OCR project focuses on developing a system for recognizing Urdu characters using deep learning techniques.  

**Key components include:**  
- **Dataset Creation** – Generate a diverse set of Urdu words and corresponding images.  
- **Model Training** – Train deep learning architectures to improve recognition accuracy.  

---

## 📝 Word Generation  

**Purpose**: Build a comprehensive dataset of Urdu words for training OCR models.  

**Methodology**:  
- Uses defined sets of Urdu characters (start, middle, end).  
- Generates words with lengths ranging from **1 to 5 characters**.  
- Saves generated words and labels in **CSV format** for easy access.  

---

## 🖼️ Image Generation  

**Purpose**: Convert generated Urdu words into images for model training.  

**Methodology**:  
- Renders each generated word in a Microsoft Word document.  
- Captures screenshots of the words to create images.  
- Saves images in a structured directory for further processing.  

---

## 👀 Preview  

Examples of generated images:  

![Sample Urdu Word 1](https://github.com/user-attachments/assets/bf89e89a-8e0e-4f04-801f-bd73114fb2b4)  

<br>  

![Sample Urdu Word 2](https://github.com/user-attachments/assets/c30e191f-a0b2-4e63-8b92-385a0f91c487)  

---

## 🤖 Deep Learning Models  

This project implements multiple deep learning architectures for OCR:  

- **Hybrid CNN + LSTM**  
  - CNN extracts visual features.  
  - LSTM captures sequential dependencies for character recognition.  

- **VGG16**  
  - A widely used deep CNN model.  
  - Adapted for Urdu OCR to leverage its image classification performance.  

- **Custom Deep CNN**  
  - Designed specifically for complex Urdu characters.  
  - Focuses on improving recognition accuracy for challenging patterns.  

---

## ⚙️ Getting Started  

### 1. Clone the Repository  
```bash
git clone https://github.com/yourusername/Urdu-OCR.git
cd Urdu-OCR
```
### **Note**: To get the downloaded dataset, email at gardazisarib@gmail.com
