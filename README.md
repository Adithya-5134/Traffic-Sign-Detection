# 🚦 Traffic Sign Detection using Deep Learning 🧠

## 📌 **Project Overview**
Welcome to the **Traffic Sign Detection** project! This deep learning-based system identifies and classifies traffic signs from road images, aiming to enhance autonomous driving and driver-assistance systems with real-time recognition.

## 📂 **Dataset Information**

📄 **Dataset Source:** Custom image dataset with annotated traffic signs  
🧷 **Classes:43**  
- 0: 'Speed Limit 20 kmph'  
- 1: 'Speed Limit 30 kmph'  
- 2: 'Speed Limit 50 kmph'  
- 3: 'Speed Limit 60 kmph'  
- 4: 'Speed Limit 70 kmph'  
- 5: 'Speed Limit 80 kmph'  
- 6: 'End of Speed Limit 80 kmph'  
- 7: 'Speed Limit 100 kmph'  
- 8: 'Speed Limit 120 kmph'  
- 9: 'No Passing'  
- 10: 'No Passing vehicle over 3.5 ton'  
- 11: 'Right-of-way at intersection'  
- 12: 'Priority road'  
- 13: 'Yield'  
- 14: 'Stop'  
- 15: 'No vehicles'  
- 16: 'Veh > 3.5 tons prohibited'  
- 17: 'No entry'  
- 18: 'General caution'  
- 19: 'Dangerous curve left'  
- 20: 'Dangerous curve right'  
- 21: 'Double curve'  
- 22: 'Bumpy road'  
- 23: 'Slippery road'  
- 24: 'Road narrows on the right'  
- 25: 'Road work'  
- 26: 'Traffic signals'  
- 27: 'Pedestrians'  
- 28: 'Children crossing'  
- 29: 'Bicycles crossing'  
- 30: 'Beware of ice/snow'  
- 31: 'Wild animals crossing'  
- 32: 'End speed + passing limits'  
- 33: 'Turn right ahead'  
- 34: 'Turn left ahead'  
- 35: 'Ahead only'  
- 36: 'Go straight or right'  
- 37: 'Go straight or left'  
- 38: 'Keep right'  
- 39: 'Keep left'  
- 40: 'Roundabout mandatory'  
- 41: 'End of no passing'  
- 42: 'End no passing vehicle > 3.5 tons'  

## 🖼️ **Image Features**

Each image contains one or more traffic signs labeled with bounding boxes. The model detects:
- Sign location (object detection)
- Sign category (classification)

## 🔍 **Model Implementation**

📜 **File:** `PRAICP_1002_TrafSignDetc.ipynb`

🛠️ **Steps Followed:**
- 🧹 **Data Preprocessing** – Annotation parsing, image resizing
- 🏷️ **Label Encoding** – Converting XML to YOLO/COCO format
- 🧠 **Model Training** – Using YOLO or similar object detection model
- 🎯 **Evaluation** – Detection accuracy, bounding box performance
- 📷 **Inference** – Detecting traffic signs on new images

## 🤖 **Deep Learning Architecture**

- 📦 Convolutional Neural Networks (CNN)
- 🧱 YOLO (You Only Look Once) or similar real-time object detector
- 🌀 Feature Extraction Layers
- 📏 Bounding Box Regression Head
- 📚 Softmax/Logits Layer for Classification

## 📉 **Metrics Used**

- 📌 mAP (mean Average Precision)  
- 📌 IoU (Intersection over Union)  
- 📌 Precision & Recall  
- 📌 Inference Time

## 🧪 **Technologies Used**

- TensorFlow / Keras / PyTorch  
- OpenCV  
- Pandas & NumPy  
- LabelImg / XML Parsers  
- Jupyter Notebook

## 🔑 **Key Insights**

- 🚀 Real-time detection is achievable with lightweight models.  
- 🧠 Data quality and diverse sign examples are critical for performance.  
- ✅ The model is capable of generalizing to various lighting and road conditions.

## 🎯 **Conclusion**

This project showcases how deep learning enables robust and fast traffic sign detection, a key component in self-driving vehicles. With further tuning and larger datasets, this model can be deployed in smart transportation systems for enhanced road safety.

