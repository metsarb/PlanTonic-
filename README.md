🌱 PlanTonic: AI-Powered Houseplant Identification App

PlanTonic is a lightweight mobile application designed to identify ornamental houseplants from images and provide care recommendations based on their needs. The model is trained using TensorFlow and MobileNetV3Large, and optimized for mobile deployment via TFLite.

🚀 Features
🌿 Detects indoor ornamental plant species from images
💡 Offers care tips: light requirements, watering frequency, temperature needs
⚡ Mobile-optimized model (TFLite format, CPU-compatible)
🔁 External data augmentation for better generalization
📊 Balanced training with real-time validation and overfitting prevention
🧠 Technologies Used
TensorFlow / Keras
MobileNetV3Large (pre-trained & fine-tuned)
Python (3.9+)
PIL / OpenCV
ImageDataGenerator
TFLite conversion
NumPy / Matplotlib / Scikit-learn
📁 Directory Structure
PlanTonic/
│
├── train.py                  # Model training script
├── test.py                   # Inference script (optional)
├── model/
│   └── plant_model.tflite    # Converted TFLite model
├── images/
│   ├── accuracy_plot.png     # Training performance graph
│   └── app_ui.png            # App interface screenshot
├── json/
│   └── label_map.json        # Mapping of class indices to plant names
├── requirements.txt          # Python package requirements
└── data/
    ├── train/
    ├── val/
    └── test/
🛠️ Installation & Requirements
Python Environment:

We recommend using a virtual environment:

python3 -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
Install Required Libraries:

pip install -r requirements.txt
Example requirements.txt

tensorflow==2.13.0
numpy
pillow
scikit-learn
matplotlib
opencv-python
🧪 Running the Training
Make sure your dataset is placed correctly inside the data/ folder.

python train.py
This script:

Preprocesses images (resizing, normalization)
Loads augmented data via ImageDataGenerator
Trains a MobileNetV3Large model with your configuration
Saves the model and converts it to TFLite
📲 TFLite Deployment
The trained model plant_model.tflite can be easily integrated into Android or iOS apps using TensorFlow Lite APIs.

🖼️ Screenshots
Model Training Accuracy	App Interface
📄 License
This project is licensed under the MIT License.

