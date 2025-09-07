🐾 Animal Classification

This project uses deep learning with transfer learning to classify images of animals into 15 categories.
Built in Google Colab using PyTorch and a MobileNetV2 backbone.



📂 Dataset

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


📈 Results

Accuracy: ~85–90% (MobileNetV2, 10 epochs).

Works interactively with files.upload() in Colab.
