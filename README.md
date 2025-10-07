# Async Image Processing (Java)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Design](#design)
- [Installation & Setup](#installation--setup)
- [Console (Threads running)](#console-threads-running)
- [RGB to grayscale image](#RGB-to-grayscale-image)
- [Future Enhancements](#future-enhancements)


## Overview
**Async Image Processing** is a Java-based asynchronous image processing system that efficiently converts images (e.g., RGB to grayscale) using multithreading.  
It features a user-friendly GUI built with JavaFX, allowing users to upload, process, and save images quickly.

---

## Features
- Upload and preview images  
- Convert RGB images to grayscale  
- Asynchronous (multi-threaded) image processing for faster performance  
- Error handling and upload resume support  
- GUI built with JavaFX  
- Easily extendable for additional filters (contrast, brightness, etc.)

---

## Tech Stack
- **Language:** Java  
- **Framework:** JavaFX  
- **Concepts:** Multithreading, Asynchronous Programming, Exception Handling  

---

## Design

<img width="1703" height="918" alt="Untitled diagram-2025-10-07-121415" src="https://github.com/user-attachments/assets/790ae8db-0b59-4732-a874-09612e70f834" />

## Installation & Setup

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/yourusername/async-image-processing.git
2. Open the project in IntelliJ IDEA or Eclipse.
3. Make sure JavaFX is properly configured.
4. Run Main.java.
5. Upload an image and click Process to see the result.



## console ()Threads running):
<img width="1919" height="1079" alt="Screenshot 2025-10-07 162422" src="https://github.com/user-attachments/assets/cace0f01-4af7-4e0c-9f5c-8833fb740b85" />

<img width="1919" height="1079" alt="Screenshot 2025-10-07 162435" src="https://github.com/user-attachments/assets/5cb42ec9-4e51-45e1-80e4-814421cdf0ab" />

## RGB to grayscale image
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4e41bfac-2193-46c0-b0cf-73e1ab789da3" />

<img width="1919" height="1079" alt="Screenshot 2025-10-07 162234" src="https://github.com/user-attachments/assets/6ec5e58b-a0ac-41ca-92a2-4aba01cbaa31" />

## Future Enhancements

1. Add more filters like contrast, brightness, and sepia
2. Support for multiple image formats (PNG, JPEG, BMP)
3. Real-time preview of applied filters


