# 🚦 Traffic Sign Recognition using Hybrid Deep Learning and Model Fusion

A deep learning-based Traffic Sign Recognition (TSR) system that accurately classifies traffic signs using multiple CNN models and an attention-based model fusion approach. This project improves recognition accuracy by combining the strengths of different neural network architectures, making it suitable for Intelligent Transportation Systems (ITS), Advanced Driver Assistance Systems (ADAS), and autonomous vehicles.

---

## 📌 Features

* ROI (Region of Interest) extraction using bounding box annotations
* Image preprocessing and normalization
* Data augmentation for improved generalization
* Dataset balancing to reduce class imbalance
* Transfer learning with multiple CNN architectures
* Average Fusion and Attention-Based Fusion techniques
* Performance evaluation using Accuracy, Precision, Recall, F1-Score, ROC Curve, and Confusion Matrix
* Achieved **98.33% classification accuracy**

---

## 🛠️ Technologies Used

* Python
* PyTorch
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Torchvision

---

## 📂 Dataset

This project uses the **LISA Traffic Sign Dataset**.

Dataset Link:
[https://cvrr.ucsd.edu/LISA/lisa-traffic-sign-dataset.html](https://cvrr.ucsd.edu/LISA/lisa-traffic-sign-dataset.html)

---

## 🧠 Models Used

* ResNet18
* ResNet50
* EfficientNet-B0
* DenseNet121

### Fusion Techniques

* Average Fusion
* Attention-Based Fusion (AFRNet)

---

## 📁 Project Structure

```text
Traffic-Sign-Recognition/
│── dataset/
│── models/
│── src/
│   ├── preprocessing.py
│   ├── train.py
│   ├── test.py
│   ├── fusion.py
│── results/
│── notebooks/
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Traffic-Sign-Recognition.git
cd Traffic-Sign-Recognition
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Train the model:

```bash
python train.py
```

Test the model:

```bash
python test.py
```

---

## 📊 Results

| Model                         |   Accuracy |
| ----------------------------- | ---------: |
| ResNet18                      |     97.78% |
| ResNet50                      |     95.00% |
| EfficientNet-B0               |     97.22% |
| DenseNet121                   |     95.56% |
| **AFRNet (Attention Fusion)** | **98.33%** |



## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC Curve



## 🚀 Applications

* Autonomous Driving
* Advanced Driver Assistance Systems (ADAS)
* Intelligent Transportation Systems (ITS)
* Smart Traffic Monitoring
* Road Safety Solutions



## 🔮 Future Improvements

* Real-time traffic sign detection using YOLO
* Support for larger datasets like GTSRB
* Mobile deployment using TensorFlow Lite or ONNX
* Vision Transformer (ViT) integration
* Real-time webcam/video inference



## 👩‍💻 Authors

* **Abhinaya Mothukuri**
* **Bhavyaratna Kanneganti**
* **Bhargavi Maridu**



## 📄 License

This project is intended for **academic and research purposes**. Feel free to use and modify it with proper attribution.


