# 🏋️‍♂️ Fitnessense-GymRep-Counter

Fitnessense-GymRep-Counter is a computer vision–based fitness tracking system that uses real-time pose estimation to automatically count workout repetitions through a webcam. Built using Python, OpenCV, and MediaPipe, it enables hands-free performance monitoring for multiple gym exercises.

---

## 🏋️ Supported Exercises

| Exercise        | File                |
|-----------------|---------------------|
| Bicep Curls     | bicep_curl.ipynb     |
| Bench Press     | bench_press.ipynb    |
| Push-ups        | push_ups.ipynb       |
| Lateral Raises  | lateral_raise.ipynb  |
| Shoulder Press  | shoulder_press.ipynb |

---

## 🚀 How It Works

1. Captures live video from the webcam  
2. Detects human body landmarks using MediaPipe Pose  
3. Computes joint angles using vector mathematics  
4. Tracks movement phases using angle thresholds  
5. Counts repetitions based on motion patterns  
6. Displays live feedback on screen  

---

## 📁 Project Structure

```text
Fitnessense-GymRep-Counter/
│
├── bicep_curl.ipynb
├── bench_press.ipynb
├── push_ups.ipynb
├── lateral_raise.ipynb
├── shoulder_press.ipynb
└── README.md
