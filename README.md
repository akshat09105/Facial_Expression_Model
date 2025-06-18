# Facial Expression Recognition Model 🤖📸

A deep learning model for recognizing facial expressions using **LandingAI Lens** – a powerful platform for computer vision development. This project detects human emotions from images or webcam input and is useful in areas like smart surveillance, customer behavior analysis, and HCI.

---

## 🧠 Features

* Trained on more than 420+ labeled images
* Emotion classification: Happy, Sad, Angry, Surprise, Fear, Disgust, Neutral
* Trained via LandingAI's intuitive UI and robust cloud infrastructure
* Easy deployment with LandingAI APIs
* Real-time emotion prediction with webcam
* Clean, modular code to integrate with other applications

---

## 🛠️ Tech Stack

* **LandingAI Lens** (Model training, deployment)
* Python
* OpenCV (for image handling and webcam)
* Requests (to call LandingAI API)
* Streamlit (optional – for UI)

---

## 📁 Project Structure

```
facial_expression_model/
├── landingai_config.json     # LandingAI project config
├── src/
│   ├── predict.py            # API call to LandingAI for prediction
│   └── utils.py              # Helper functions
├── assets/                   # Sample images/videos
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/facial_expression_model.git
cd facial_expression_model
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure LandingAI

* Go to [LandingAI](https://www.landing.ai/)
* Create a project and train your facial expression model using the Lens UI
* Copy your `endpoint_id` and `API key`
* Create a `landingai_config.json` file:

```json
{
  "endpoint_id": "your-endpoint-id",
  "api_key": "your-api-key"
}
```

### 4. Run Prediction

```bash
python src/predict.py --image assets/test_face.jpg
# OR
python src/predict.py --webcam
```

---

## 📊 Sample Prediction Output

```bash
Expression: Happy
Confidence: 97.4%
```

Or for webcam:

```
[INFO] Capturing video stream...
[INFO] Predicted: Angry (84.6%)
```

---

## ✅ Example Use Cases

* Retail store customer emotion analysis
* Virtual classroom student feedback
* Smart advertising panels
* Wellness monitoring systems

---

## 📌 Roadmap

*

---

## ✨ Made Using

---

## 👤 Author

**Akshat Gupta**
[LinkedIn](https://www.linkedin.com/in/akshat-gupta-6a27a331a/) • [GitHub](https://github.com/akshat09105)

---
---

## ⭐ Show Support

If you found this helpful, please give the repo a ⭐ — it helps others discover the project and keeps development going!
