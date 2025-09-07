🐾 Animal Classification

This project uses deep learning with transfer learning to classify images of animals into 15 categories.
Built in Google Colab using PyTorch and a MobileNetV2 backbone.

📂 Dataset

Located at: .../animal_classification/Animal Classification/dataset

Contains 15 class folders (Dog, Cat, Tiger, etc.).

Auto-splits into train (70%) / val (15%) / test (15%) if not already split.

🛠️ Tech Stack

Python, Google Colab, Google Drive

PyTorch (torch, torchvision)

scikit-learn (metrics, dataset splitting)

Matplotlib & Seaborn (visualizations)

PIL (image handling)

🧠 Model

MobileNetV2 (final model)

Lightweight & fast (~3.5M params).

Trained with AMP (Mixed Precision).

(ResNet-50 was tested but slower).

🚀 Usage

Open notebook in Google Colab.

Mount Google Drive and set dataset path.

Install dependencies:

!pip install torch torchvision scikit-learn matplotlib tqdm seaborn


Train model (EPOCHS = 10, increase for better accuracy).

Evaluate with classification report & confusion matrix.

Run inference:

predict_image("dog.jpg")
# [('Dog', 0.87), ('Wolf', 0.10), ('Cat', 0.02)]

📈 Results

Accuracy: ~85–90% (MobileNetV2, 10 epochs).

Works interactively with files.upload() in Colab.

📌 Future Work

Train longer for higher accuracy.

Try EfficientNet for stronger performance.

Deploy with Streamlit for real-time predictions.
