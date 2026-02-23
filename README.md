# Multimodal-Deep-Learning-Based-Precision-Treatment-for-Lung-Cancer
This project presents a multimodal deep learning framework for lung cancer classification by integrating CT scan images and clinical data. EfficientNetB0 is used for image feature extraction, and a neural network processes clinical features. Both features are fused to improve classification accuracy, achieving up to 96.86% accuracy.



# Dataset includes:
1. CT Scan Images
2. Clinical Features
## Data Setup
This project uses a dataset hosted on Kaggle. To download it:

1. Install the library: `pip install kagglehub`
2. Run this snippet in your notebook:

```python
import kagglehub
# Download latest version
path = kagglehub.dataset_download("jitinrnair/new-dataset")
print("Path to dataset files:", path).

