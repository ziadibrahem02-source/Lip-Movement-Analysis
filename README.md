# 🧠 AI Speech Therapy & Lip Movement Assessment

An AI-powered speech therapy project that compares a child's lip movements with a doctor's reference pronunciation using computer vision and audio analysis.

## ✨ Features

- 🎥 Side-by-side comparison between doctor and child videos.
- 👄 Lip movement analysis using Google MediaPipe Face Landmarker.
- 🎙️ Automatic speech detection (Voice Activity Detection).
- 🔄 Dynamic Time Warping (DTW) for accurate speech alignment.
- 📊 Live speech matching score.
- 🎬 Automatic synchronized comparison video generation.
- 🔊 Audio extraction, synchronization, and merging.

---

## 🛠️ Technologies Used

- Python
- OpenCV
- Google MediaPipe
- NumPy
- Librosa
- FastDTW
- SciPy
- FFmpeg
- Google Colab

---

## 📂 Project Workflow

1. Upload the doctor's reference video.
2. Upload the child's pronunciation video.
3. Detect speech regions.
4. Extract facial landmarks.
5. Compare lip movements using DTW.
6. Generate a similarity score.
7. Export a synchronized comparison video.

---

## 📦 Installation

Install the required packages:

```bash
pip install mediapipe fastdtw librosa scipy opencv-python numpy
```

FFmpeg must also be installed.

---

## ▶️ Usage

Run the notebook in Google Colab.

Upload:

- `doctor.mp4`
- `child.mp4`

The notebook will automatically:

- Analyze speech
- Compare lip movements
- Generate a synchronized output video
- Display the speech matching score

---

## 📸 Output

- Side-by-side comparison video
- Speech Match Percentage
- AI Assessment Panel
- Lip synchronization analysis

---

## 📁 Project Structure

```
.
├── AI_Speech_Therapy.ipynb
├── doctor.mp4
├── child.mp4
├── face_landmarker.task
└── README.md
```

---

## 🚀 Future Improvements

- Real-time webcam assessment
- Better phoneme-level scoring
- Arabic speech support
- Deep Learning based lip reading
- Mobile application integration

---

## 👨‍💻 Author

**Ziad Ibrahim**

Computer Science Student

GitHub: https://github.com/ziadibrahem02-source
