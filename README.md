<div align="center">

# 🌿 AgriFreshNet

### AI-Powered Fruit Detection & Freshness Classification System

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)
[![License](https://img.shields.io/badge/License-Academic-green?style=for-the-badge)](./LICENSE)

> A deep learning application that classifies fruit types and detects freshness using EfficientNet-based CNN models — built for smart agriculture and food quality monitoring.

</div>

---

## 📸 Overview

**AgriFreshNet** is a computer vision system designed to help farmers, retailers, and researchers quickly identify fruit types and assess their freshness using state-of-the-art deep learning. Upload an image and get instant predictions powered by two specialized EfficientNet models.

---

## ✨ Features

- 🍎 **Fruit Classification** — Identifies the type of fruit from an image
- 🟢 **Freshness Detection** — Determines whether the fruit is fresh or spoiled
- ⚡ **Real-time Inference** — Fast predictions via an interactive Streamlit UI
- 🧠 **Dual-Model Architecture** — Two separate EfficientNet models for improved accuracy
- 🖼️ **Standard Input Pipeline** — 224×224 ImageNet-normalized preprocessing

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/your-username/AgriFreshNet.git
cd AgriFreshNet
```

**2. Install dependencies**

```bash
pip install -r requirements.txt
```

**3. Run the application**

```bash
streamlit run app.py
```

**4. Open in your browser**

```
http://localhost:8501
```

---

## 📁 Project Structure

```
AgriFreshNet/
│
├── app.py                        # 🌐 Streamlit web application
├── EfficientNet_fruit.pth        # 🍊 Fruit classification model weights
├── EfficientNet_freshness.pth    # 🌿 Freshness detection model weights
├── requirements.txt              # 📦 Python dependencies
├── runtime.txt                   # 🐍 Python version specification
└── README.md                     # 📖 Project documentation
```

---

## 🧠 Model Details

| Property | Details |
|----------|---------|
| **Framework** | PyTorch 🔥 |
| **Architecture** | EfficientNet-based CNN |
| **Input Size** | 224 × 224 pixels |
| **Preprocessing** | ImageNet normalization |
| **Model 1** | Fruit type classification |
| **Model 2** | Freshness classification |

Both models are trained independently to ensure specialized and accurate predictions for each task.

---

## 🧪 Tech Stack

| Technology | Purpose |
|-----------|---------|
| **Python** | Core programming language |
| **PyTorch** | Deep learning framework |
| **Torchvision** | Model architectures & transforms |
| **OpenCV** | Image processing |
| **Pillow (PIL)** | Image loading & manipulation |
| **Streamlit** | Interactive web interface |

---

## 📌 Future Improvements

- [ ] 🍉 Add support for more fruit categories
- [ ] 📊 Improve accuracy with a larger and more diverse dataset
- [ ] ☁️ Deploy on AWS / GCP / Azure for scalable access
- [ ] 🦠 Integrate a fruit disease detection module
- [ ] 💅 Improve UI responsiveness and mobile support

---

## 👨‍💻 Author

<div align="center">

**Md Jakir Hossain**

*Researcher*
**IntelliSphere Lab, Dhaka, Bangladesh**
*MSc in Computer Science and Engineering*
**East West University, Dhaka, Bangladesh**

</div>

---

## 📜 License

This project is developed for **academic and research purposes only**.
Redistribution or commercial use requires explicit permission from the author.

---

<div align="center">

Made with ❤️ for smarter agriculture 🌾

</div>
