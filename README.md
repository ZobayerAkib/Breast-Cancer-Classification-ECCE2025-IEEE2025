# 🧬 Breast Cancer Classification Using Pre-trained CNNs with Explainable AI for Enhanced Decision Support

[![DOI](https://zenodo.org/badge/DOI/10.1109/ECCE64574.2025.11012958.svg)](https://doi.org/10.1109/ECCE64574.2025.11012958)
[![Conference](https://img.shields.io/badge/ECCE-2025-blue)](https://ieeexplore.ieee.org/document/11012958)
[![Paper](https://img.shields.io/badge/View%20Paper-ResearchGate-green)](https://www.researchgate.net/publication/392217392_Breast_Cancer_Classification_Using_Pre-trained_CNNs_with_Explainable_AI_for_Enhanced_Decision_Support)
[![Python](https://img.shields.io/badge/Python-3.8%2B-yellow)](https://www.python.org/)
[![Model: EfficientNetV2S](https://img.shields.io/badge/Best%20Model-EfficientNetV2S-ff69b4)]()

---

🎓 **Accepted at:**  
📌 *2025 International Conference on Electrical, Computer and Communication Engineering (ECCE)*  
🔗 [**IEEE Xplore**](https://ieeexplore.ieee.org/document/11012958)  
📄 [**ResearchGate**](https://www.researchgate.net/publication/392217392_Breast_Cancer_Classification_Using_Pre-trained_CNNs_with_Explainable_AI_for_Enhanced_Decision_Support)

---

## 📌 Abstract

> Early detection of breast cancer is crucial for effective treatment. This study proposes a deep learning approach using pre-trained CNNs to classify breast cancer and improve decision transparency through Explainable AI (XAI). We utilized an imbalanced BUSI dataset, applied augmentation and preprocessing, and evaluated four advanced CNNs: **EfficientNetV2S**, **InceptionResNetV2**, **EfficientNetV2M**, and **XceptionNet**.  
>  
> To enhance model interpretability, we used **Faster ScoreCAM** and **LIME**. Among all models, **EfficientNetV2S** achieved the highest accuracy of **91.02%**, demonstrating the potential of explainable deep learning models in medical imaging.

---

## 🚀 Highlights

- 🩺 **Medical Domain:** Breast Cancer Ultrasound Images (BUSI Dataset)
- 📈 **Model Accuracy:** EfficientNetV2S - **91.02%**
- 🤖 **Deep Learning Models:** EfficientNetV2S, InceptionResNetV2, EfficientNetV2M, XceptionNet
- 🧠 **Explainable AI:** LIME, Faster ScoreCAM
- ⚙️ **Balanced Training via Augmentation**
- 📊 **Transparency in Clinical Decision Support**

---

## 🧠 CNN Architectures Used

| Model               | Accuracy |
|--------------------|----------|
| EfficientNetV2S    | **91.02%** ✅ |
| InceptionResNetV2  | 89.65%   |
| EfficientNetV2M    | 88.74%   |
| XceptionNet        | 87.93%   |

---

## 🧪 Explainability (XAI)

We leveraged **LIME** and **Faster ScoreCAM** to visualize which regions of the ultrasound image influenced the model’s prediction:

- ✅ Improves transparency and clinical trust.
- 🎯 Highlights critical regions contributing to the classification.
> 🌐 Transparency = Trust.

### 🔹 EfficientNetV2M + Faster ScoreCAM
![EfficientNetV2M + Faster ScoreCAM](https://raw.githubusercontent.com/ZobayerAkib/Breast-Cancer-Classification-ECCE2025-IEEE2025/main/v2mFaster.png)

---

### 🔹 EfficientNetV2S + LIME
![EfficientNetV2S + LIME](https://raw.githubusercontent.com/ZobayerAkib/Breast-Cancer-Classification-ECCE2025-IEEE2025/main/v2sLime.png)
---

## 🖼️ Sample Output

![Output Prediction](https://raw.githubusercontent.com/ZobayerAkib/Breast-Cancer-Classification-ECCE2025-IEEE2025/main/output.png)

---
```bibtex
@INPROCEEDINGS{11012958,
  author={Kabir, Md. Zobayer Ibna},
  booktitle={2025 International Conference on Electrical, Computer and Communication Engineering (ECCE)}, 
  title={Breast Cancer Classification Using Pre-trained CNNs with Explainable AI for Enhanced Decision Support}, 
  year={2025},
  volume={},
  number={},
  pages={1-6},
  keywords={Deep learning;Training;Accuracy;Explainable AI;Source coding;Prevention and mitigation;Decision making;Breast cancer;Data models;Feeds;Medical Imaging;Breast Cancer Classification;CNN;BUSI Dataset;Explainable Artificial Intelligence (XAI);Faster ScoreCAM;LIME;Explainability;Deep Learning},
  doi={10.1109/ECCE64574.2025.11012958}}


