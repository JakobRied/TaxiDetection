# Namibian Taxi Registration Validator

This web application was developed as my **final project for Harvard's CS50 – Introduction to Computer Science**.  
It provides an automated **validity check for Namibian taxi registration numbers** using computer vision and deep learning.

---

## Project Overview

The application utilizes a **YOLO (You Only Look Once)** neural network trained on a **custom dataset** of Namibian taxi registration numbers.  
Its primary goal is to detect, extract, and verify taxi numbers against an official database to determine whether a taxi’s registration is valid.

---

## How It Works

1. **Image Detection:**  
   The YOLO model processes an uploaded image to detect regions containing taxi registration numbers.

2. **Number Extraction:**  
   The detected regions are passed to a language recognition module that extracts the textual registration number.

3. **Database Verification:**  
   The extracted number is compared against an **official database** of registered Namibian taxis.  
   Based on this comparison, the system determines whether the taxi number is **valid or invalid**.

---

## Dataset

- Collected and labeled **250+ images** of Namibian taxis.  
- Each image was **manually annotated** to mark the position of the taxi registration number.  
- The dataset was used to train the YOLO model for high-accuracy number detection.
- 

## 🧑‍💻 User Interface

The frontend was intentionally kept **minimalistic** and **functional**, as the primary focus of the project was on training and implementing the YOLO model rather than frontend design.

---

## 📚 Acknowledgements

- [Harvard CS50](https://cs50.harvard.edu/) for the foundational knowledge and inspiration  
- Open-source contributors for YOLO and supporting libraries
