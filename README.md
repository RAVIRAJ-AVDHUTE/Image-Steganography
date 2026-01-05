# 🖼️ Image Steganography (C# .NET)

> *Hide secrets inside images — invisible to the eye, recoverable with the right key.*

A desktop application built in **C# using .NET Framework and Windows Forms**, designed to embed and extract secret messages within image files using **LSB (Least Significant Bit) steganography**. Perfect for learning data hiding techniques or securely sharing text/data without raising suspicion.

---

## 🔍 How It Works


- **Embed**: Hide text or files inside PNG/JPEG images by subtly altering pixel color values.
- **Extract**: Retrieve hidden data from a stego-image using the same algorithm.
- **Optional Encryption**: Secure your message with AES before embedding (configurable).

---

## ✅ Features

- Simple, intuitive Windows Forms GUI
- Supports common image formats: PNG, JPG, BMP
- Real-time preview of cover & stego images
- Progress tracking during embedding/extraction
- Optional password-based encryption (AES-256)
- Lightweight & standalone — no external dependencies required

---

## 💻 Tech Stack

- **Language**: C#
- **Framework**: .NET Framework 4.7.2+
- **UI**: Windows Forms
- **Libraries**: System.Drawing, System.Security.Cryptography

---

## 🚀 Getting Started

1. Clone this repository
2. Open `.sln` file in Visual Studio
3. Build & Run!
4. Load an image → Enter secret message → Embed → Save stego-image
5. Later, load the stego-image → Extract → Reveal hidden data

---

📌 *Ideal for students, hobbyists, or anyone curious about digital steganography and secure data concealment.*

---

👤 **By**: [Raviraj Avdhute](https://github.com/RAVIRAJ-AVDHUTE)  
📅 **Created**: January 2026

---

> 💡 Tip: Add screenshots or GIFs later to show your app in action!