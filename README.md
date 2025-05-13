# MRI Brain Tumor Classification (ResNet-18 vs. Hybrid (Resnet-18 + AdaBoost)

This project explores how combining deep learning (ResNet-18) with traditional machine learning (AdaBoost) can improve classification performance on brain MRI scans, especially when labeled data is limited.

---

## 🧠 Problem
Classify brain MRI scans into one of four categories:
- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

---

## 🧪 Models Compared

| Model | Description |
|-------|-------------|
| ResNet-18 | End-to-end deep neural network |
| Hybrid (ResNet-18 + AdaBoost) | ResNet feature extractor + decision tree ensemble |

---

## 📊 Key Results

| Data Fraction | Hybrid Accuracy | ResNet Accuracy |
|---------------|------------------|------------------|
| 1%            | 64.52%           | 53.90%           |
| 5%            | 71.91%           | 72.55%           |
| 10%           | 75.19%           | 72.43%           |
| 50%           | 83.17%           | 81.82%           |
| 100%          | 83.75%           | **84.57%**       |

🔍 **Takeaway**: The hybrid model performs better when data is limited. Pure ResNet eventually overtakes it when trained on the full dataset.

---

## 💡 What I Learned
- Hybrid models can outperform deep learning in low-data settings.
- AdaBoost helps when ResNet doesn’t have enough data to generalize well.
- Model choice should depend on available data and compute resources.

---

## 📄 Full Report
📎 [View the full PDF report](./Project_Title.pdf)

