# Real-Time Face Detection Using OpenCV

This project demonstrates real-time face detection using OpenCV and a webcam. It uses Haar Cascade classifiers to detect faces and draws rectangles around them live on your webcam feed.

## 📁 Files Included

- `face_detection.py` – Python script for real-time face detection

## 🚀 Requirements

- Python 3.x
- OpenCV

### 🔧 Install Dependencies

```bash
pip install opencv-python
````

## ▶️ How to Run

1. Clone or download this repository.
2. Run the script:

```bash
python face_detection.py
```

3. A window will open showing your webcam feed with detected faces highlighted.

## 🎯 Features

* Real-time face detection using Haar Cascades
* Clean and simple OpenCV implementation
* Works on standard webcams

## 🧠 How It Works

* Loads Haar Cascade XML from OpenCV's pre-trained models
* Converts webcam frames to grayscale
* Detects and highlights all visible faces
* Exits when the `q` key is pressed

## 🔒 License

This project is licensed under the MIT License.

## 🙋‍♂️ Author

Created by Kalpesh Prajapati

````

---

### 🗃️ Uploading to GitHub (Step-by-Step)

1. **Create a folder** and add your Python file:
   ```bash
   mkdir real-time-face-detection
   cd real-time-face-detection
````

2. **Save your script as** `face_detection.py`

3. **Add the README.md file** (from above)

4. **Initialize Git and push to GitHub**:

   ```bash
   git init
   git add .
   git commit -m "Initial commit: Add real-time face detection script"
   git branch -M main
   git remote add origin https://github.com/<your-username>/real-time-face-detection.git
   git push -u origin main
   ```
