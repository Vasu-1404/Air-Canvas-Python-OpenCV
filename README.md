# 🖌️ Air Canvas using Python, OpenCV & Mediapipe

This project enables users to draw virtually in the air using **hand gestures**, with real-time tracking via webcam. By using **Python**, **OpenCV**, and **Mediapipe**, the system captures hand landmarks and translates the fingertip movements into strokes on a digital canvas — allowing contactless drawing with dynamic color options.

---

## 📌 Features

- 🖐️ Real-time hand tracking using **Mediapipe**.
- 🎨 Draw using index finger gestures (without mouse or touchscreen).
- 🔘 Virtual buttons on-screen to:
  - Select drawing color (Blue, Green, Red, Yellow)
  - Clear the canvas
- ✨ Separate drawing window and live camera window.
- 📸 Visual feedback with fingertip circles and hand landmarks.

---

## 🧰 Technologies Used

- **Python 3**
- **OpenCV**
- **Mediapipe**
- **NumPy**
- Webcam (Laptop or USB camera)

---

## 🗂️ Project Structure
AirCanvas/
├── AI canva.py # Main source code
├── README.md # Project documentation
└── sample_output.png # Optional: Screenshot of output window


---

## ⚙️ How It Works

1. **Hand Tracking**: Mediapipe detects landmarks on the hand (especially index finger and thumb).
2. **Drawing Activation**:
   - When index and thumb are apart ➜ draw mode.
   - When fingers touch ➜ stop drawing (used to start a new stroke).
3. **Color Selection**:
   - Hover your fingertip over the top rectangular boxes labeled BLUE, GREEN, RED, or YELLOW to change brush color.
4. **Clear Option**:
   - Move your finger to the "CLEAR" box to reset the canvas.

Drawing is done by appending the fingertip's coordinates to color-specific queues and rendering lines between consecutive points.

---

## 🔧 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/air-canvas-opencv-mediapipe.git
cd air-canvas-opencv-mediapipe


2. Install Required Libraries 
Make sure Python is installed, then run:

pip install opencv-python mediapipe numpy

▶️ Run the Project:

python "AI canva.py"

You’ll see two windows:

📷 Output: Your live webcam feed with hand tracking and control buttons.

🖼️ Paint: The virtual canvas where your drawings appear.




🙋‍♀️ Author
Ch. Vasundara Naga Lakshmi
B.Tech (EIE) | VNRVJIET
✉️ vasundara1314@gmail.com


