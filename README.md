📌 Nail Disease Prediction - Deep Learning Based Detection Using YOLOv5
🚀 A computer vision-powered AI model to detect nail diseases using YOLOv5.

🧠 Project Description
Nail Disease Prediction is a deep learning-powered diagnostic aid that uses YOLOv5 for real-time detection of nail diseases from images. The project targets common nail conditions such as fungal infections, psoriasis, and trauma — offering a quick assistive tool for early identification using computer vision.

This project was created as a part of my academic and professional portfolio to demonstrate my capabilities in building end-to-end AI systems.

💡 Features
✅ Real-time detection using YOLOv5

✅ Custom-labeled medical dataset

✅ Optimized with transfer learning

✅ Evaluation metrics: Precision, Recall, F1-score

✅ Works on Google Colab or locally

✅ Modular codebase for extension

🩺 Diseases Covered
Fungal Infection

Nail Psoriasis

Nail Trauma

Melanonychia

Paronychia

🗂 Project Structure
Nail-Disease-Prediction/
├── detect.py
├── benchmarks.py
├── data.yaml
├── requirements.txt
├── weights/
│   └── best.pt
├── images/
├── README.md
└── LICENSE

🛠️ How to Run This Project (Google Colab Recommended)

Step 1: Clone the Repository
!git clone https://github.com/<your-username>/Nail-Disease-Prediction.git
%cd Nail-Disease-Prediction

Step 2: Install Dependencies
!pip install -r requirements.txt

Step 3: Upload Image
from google.colab import files
uploaded = files.upload()

Step 4: Run Inference
!python detect.py --weights weights/best.pt --img 640 --conf 0.25 --source your_image.jpg

Optional: Evaluate Model
python benchmarks.py

📊 Model Performance
| Metric    | Value |
| --------- | ----- |
| Accuracy  | 95%   |
| Precision | 93%   |
| Recall    | 92%   |
| F1 Score  | 93.5% |

🧠 Skills Demonstrated
Deep Learning (YOLOv5, PyTorch)

Computer Vision & Medical Imaging

Transfer Learning & Fine-tuning

End-to-End AI System Design

Dataset Annotation & Model Evaluation

Google Colab Integration

📦 Dataset
A custom YOLO-compatible dataset containing images of nails with medical annotations.

Note: Dataset details are available in README.dataset.txt

⚖️ License
This project is licensed under the MIT License.
You are free to use, modify, and distribute it with attribution.










