# 😊 Facial Expression Recognition System

This project is a real-time facial expression recognition system that classifies human emotions into **seven categories**:  
`Angry`, `Disgust`, `Fear`, `Happy`, `Neutral`, `Sad`, and `Surprised`.

Built with a **lightweight 4-layer CNN**, the model was trained on the **FER-2013** dataset using **TensorFlow/Keras** and achieves approximately **63% accuracy** after 50 epochs.

---

## 🧠 Model Architecture

- **Input:** 48x48 grayscale facial images  
- **Model:** 4-layer Convolutional Neural Network  
- **Training Dataset:** [FER-2013](https://www.kaggle.com/datasets/msambare/fer2013) (~35k images)  
- **Framework:** TensorFlow, Keras  
- **Accuracy Achieved:** ~63% after 50 epochs  

---

## 🛠️ Tools & Libraries Used

- Python  
- TensorFlow / Keras  
- OpenCV (for real-time webcam integration)  
- FER-2013 Dataset

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/akatsuki-uchiha-itachi/emo.git
   cd emo

## demo images

![happy](imgs/happy.jpg)
![disgust](imgs/disgust/jpg)
![sad](imgs/sad.jpg)
![angry](imgs/angry.jpg)
![neutral](imgs/neutral.jpg)
![surprised](imgs/surprised.jpg)
![fearful](imgs/fearful.jpg)
