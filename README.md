# FocusGuard AI 👁️🧠

FocusGuard AI is a computer vision system that monitors **visual attentiveness** using a webcam.

The system detects:
- 🟢 Attentive (No visual signs of distraction)
- 🟠 Distracted (Looking away)
- 🔴 Drowsy (Prolonged eye closure)

> ⚠️ Note:  
> "Attentive" does not guarantee cognitive focus.  
> It indicates **absence of visible distraction or drowsiness**.

---

## 🚀 Features
- MediaPipe Face Mesh
- Eye Aspect Ratio (EAR) for drowsiness detection
- Iris-based eye gaze detection
- Personal calibration
- Temporal voting for stable decisions
- Real-time dashboard with percentages

---

## 🛠️ Technologies
- Python
- OpenCV
- MediaPipe
- NumPy

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python main.py



press Q to exit.

📌 Use Cases

Study focus monitoring

Online exam proctoring (visual)

Driver attention research

AI & Computer Vision portfolio project
