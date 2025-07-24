# -Proactive-Package-Damage-Detection-with-AI
 Proactive Package Damage Detection with AI

In this project, we used deep learning to proactively detect damaged packages **before they are shipped** from a warehouse, using image classification with explainability.

## 🔍 Problem
Manual inspections are slow and error-prone. Our goal: shift damage detection upstream using AI, minimizing reverse logistics costs and improving customer satisfaction.

## 🧪 Solution
- Model: MobileNetV2 with transfer learning
- Data: Kaggle dataset (~600 labeled images: Damaged vs. Intact)
- Tools: TensorFlow, Keras, Grad-CAM, Google Colab
- Explainability: Grad-CAM overlays to highlight decision zones
- Risk scoring: Confidence × 100 to produce interpretable alerts

## 🧠 Model Results
- Validation Accuracy: **85.83%**
- F1 Score (Damaged): **0.44**
- AUC: **0.74**
- Real-time Grad-CAM explainability
- Risk-based alerting system

## 📊 Business Value
- Reduces reverse logistics cost
- Improves quality control and packaging strategy
- Enables human-in-the-loop inspections in warehouse settings

## 🚀 Next Steps
- Expand training with diverse real-world data
- Use GANs to simulate rare damage cases
- Deploy a field app/dashboard for image uploads + AI feedback

## 📁 Files
- `notebook/`: Model training & evaluation in Jupyter Notebook
- `docs/`: Final presentation and detailed report
- `sample_images/`: Input images with output overlays
