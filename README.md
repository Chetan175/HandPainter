# 🖌️ AI HandPainter – Virtual Drawing with Hand Gestures

AI Painter is a fun and interactive project that lets you **draw on your screen using your hands** — no mouse, no stylus, just gestures.  
It is built with **OpenCV** for computer vision and **Mediapipe** for real-time hand tracking.

---

## ✨ What It Does
- Detects your **hand landmarks** in real time using Mediapipe.
- Lets you **select colors and tools** (pen, eraser) by raising two fingers and tapping on the header bar.
- Draws on a virtual canvas when you raise your **index finger** (like a brush).
- Includes an **eraser mode** when the black color is selected.
- Merges your drawing with the live camera feed.

---

## 📂 Project Structure
HandPainter/
│-- HandTrackingModule.py # Custom module for detecting hands & fingers
│-- VirtualPainter.py # Main script (run this to start painting)
│-- Header/ # Toolbar images for colors & eraser
│-- requirements.txt # List of dependencies
│-- .gitignore # Git ignore rules
│-- README.md # Project documentation


---

## 🛠️ Tech Stack
- **Python 3.x**
- **OpenCV** – image processing & drawing
- **Mediapipe** – hand landmark detection
- **NumPy** – numerical operations

---

## 🚀 Installation & Setup

1. Clone the repository:-
   ```bash
   git clone https://github.com/Chetan175/HandPainter.git
   cd HandPainter

2. Install dependencies:-
  pip install -r requirements.txt


3. Run the HandPainter:-
  python VirtualPainter.py


How to Use-

Selection Mode: Raise index + middle finger to select colors/tools from the header bar.
Drawing Mode: Raise only the index finger to draw on the screen.
Eraser: Select the black color from the header to erase.
Change brush thickness or eraser thickness by editing variables in the code:

brushThickness = 15

eraserThickness = 100

Developed by Chetan Ahuja
