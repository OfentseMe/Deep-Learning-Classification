🛣️ Road Classification from Aerial Imagery using Deep Learning

This project implements a deep learning model for segmenting roads from high-resolution aerial imagery. Built on the U-Net architecture, the model was trained using the DeepGlobe 2018 Road Extraction Dataset. It forms part of ongoing research into automating road infrastructure analysis through machine learning.

🧠 Project Highlights

- Semantic segmentation using U-Net
- Trained on satellite images from DeepGlobe
- Augmentation techniques to improve generalization
- Evaluated using Intersection over Union (IoU), precision, and recall

Visual output includes mask overlays on original images

📥 Dataset

DeepGlobe 2018 Road Extraction Dataset

- Includes 8,570 RGB satellite images with pixel-wise road masks.
- Images: 1024×1024 resolution, 50 cm/pixel.

📖 Reference Paper

U-Net: Convolutional Networks for Biomedical Image Segmentation: https://arxiv.org/pdf/1505.04597

Originally designed for biomedical segmentation, U-Net has proven highly effective for general semantic segmentation tasks such as road extraction from aerial images.


🔧 Prerequisites

python 3.9+
tensorflow 2.19.0
numpy 2.2.5
opencv-python 4.11.0.86
matplotlib 3.10.1
scikit-learn 1.6.1


📄 License

This project is licensed under the MIT License.

