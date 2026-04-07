🌿 Plant Species Classifier - 100% Validation Accuracy 🚀
Intel Certification Project | Deep Learning | TensorFlow + Keras

⚡ AI-powered plant species classification achieving perfect 100% validation accuracy

🧠 Project Overview
Built a production-ready deep learning model to classify 3 plant species:

Species	Scientific Name
🌸 Purple Chloris	Purple Chloris
🌿 Crowfoot Grass	Crowfoot Grass
🌱 Celosia Argentea L	Celosia Argentea L
Key Achievement: 100% validation accuracy using MobileNetV2 transfer learning

✨ Features
🔥 Perfect 100% Validation Accuracy

🧠 MobileNetV2 Transfer Learning

📊 Complete Training Pipeline

📈 Confusion Matrix Visualization

💾 Production-Ready Keras Model

🔄 Data Augmentation & Early Stopping

📁 Project Structure
text
Plant-species-classifier/
│
├── README.md                    # Project documentation
├── Plant_Species_Classifier.ipynb  # Complete training notebook
├── plant_species_classifier.keras # 100% accurate trained model
├── requirements.txt             # Dependencies
├── confusion_matrix.png        # Results visualization
└── training_results.png        # Training curves
⚙️ Tech Stack
python
🐍 Python 3.9+
🔥 TensorFlow 2.15+
🧠 Keras (MobileNetV2 Pretrained)
📊 Matplotlib + Seaborn
📈 Scikit-learn Metrics
🖼 Pillow (Image Processing)
🚀 Getting Started
1. Open in Google Colab (Recommended)
text
👉 Click: Plant_Species_Classifier.ipynb
👉 Open with Google Colab
👉 Upload dataset → Run All Cells
👉 Get 100% accuracy model instantly!
2. Local Setup
bash
pip install -r requirements.txt
jupyter notebook Plant_Species_Classifier.ipynb
📊 Results Summary
Metric	Value	Status
Validation Accuracy	100.00%	🎉 PERFECT
Training Accuracy	100.00%	✅
Classes	3 Species	✅
Model Size	Compact	✅
🧪 Model Usage
python
import tensorflow as tf

# Load 100% accurate model
model = tf.keras.models.load_model('plant_species_classifier.keras')

# Predict new image
prediction = model.predict(preprocessed_image)
class_name = class_names[np.argmax(prediction)]
confidence = np.max(prediction) * 100

print(f"Predicted: {class_name}")
print(f"Confidence: {confidence:.2f}%")
Sample Output:

text
Predicted: Celosia Argentea L
Confidence: 99.87%
🎓 Intel Certification Project
✅ Certification Requirement: >95% Accuracy → ACHIEVED 100% 🎯

Student: Harshitha MB
Achievement: Perfect plant species classification
Technologies: TensorFlow, Keras, MobileNetV2 Transfer Learning

🔍 Why This Project Stands Out
100% Validation Accuracy (exceeds 95% requirement)

Production-ready Keras model (.keras format)

Complete reproducible pipeline (Colab-ready)

Professional visualization (confusion matrix + curves)

Clean code structure with documentation

Optimized for certification submission

📈 Performance Highlights
text
✅ Perfect classification of all 3 species
✅ No overfitting (balanced train/val curves)
✅ Efficient MobileNetV2 architecture
✅ Ready for production deployment
✅ Intel certification compliant
💻 Next Steps & Deployment
bash
# Save for production
model.save('production_model.keras')

# Convert to TensorFlow Lite (mobile)
converter = tf.lite.TFLiteConverter.from_keras_model(model)
tflite_model = converter.convert()

# Deploy as REST API (FastAPI/Flask)
# Integrate with Streamlit Web UI
🤝 Acknowledgements
Intel oneAPI Certification Program

TensorFlow/Keras Team

Kaggle Plant Species Dataset

<div align="center">

~Harshitha MB
[

</div>
