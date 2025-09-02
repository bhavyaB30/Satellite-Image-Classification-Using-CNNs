# 🌍 Satellite-Image-Classification-Using-CNNs  

## 📌 Overview  
This project applies **deep learning models** to classify satellite images from the **EuroSAT dataset** into **10 land cover categories**.  
We implemented and compared **CNN-based architectures** and **Vision Transformers** to evaluate their effectiveness in remote sensing tasks.  

---

## 📊 Dataset  
- **EuroSAT (Sentinel-2)** → 27,000 RGB images (64×64 px, 10m resolution)  
- **Dataset Link**: [EuroSAT GitHub Repository](https://github.com/phelber/eurosat)  
- **Classes**:  
  - Annual Crop  
  - Forest  
  - Herbaceous Vegetation  
  - Highway  
  - Industrial  
  - Pasture  
  - Permanent Crop  
  - Residential  
  - River  
  - Sea/Lake  

---

## ⚙️ Approach  
- **Preprocessing** → normalization, augmentation, cloud & noise removal  
- **Models** → ResNet-50, ResNet-101, DenseNet-121, EfficientNetV2-S, Vision Transformer  
- **Evaluation** → Accuracy, Precision, Recall, F1-score, Confusion Matrix, Grad-CAM & LIME  

---

## 🏆 Results  
| Model              | Accuracy |
|--------------------|---------:|
| ResNet-50          | 69%      |
| ResNet-101         | 73%      |
| DenseNet-121       | 88%      |
| Vision Transformer | 73%      |
| **EfficientNetV2-S** | **90%**  |  

➡️ **EfficientNetV2-S achieved the best performance.**  

---

## 👨‍💻 Contributors  

- [**Bhavya Bhambhani**](https://github.com/bhavyaB30)  

- [**Himank Xavier Soren**](https://github.com/himank111)
<!-- - [**Kumar Divyanshu**](https://github.com/kumardivyanshu21)  -->

