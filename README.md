# Drowsiness Detection System 🚗💤

## Introduction 🌟
The Drowsiness Detection System is a cutting-edge AI-powered solution designed to enhance road safety by detecting driver drowsiness in real-time. Leveraging the power of deep learning and computer vision, this system can identify signs of drowsiness and alert the driver, potentially preventing accidents caused by fatigue. This project is built using the YOLOv5 object detection model and integrates seamlessly with real-time video feeds.

## Features ✨
 📹 **Real-Time Detection**: Utilizes a webcam or external camera to monitor the driver and detect drowsiness in real-time.
 
 🧠 **Custom Model Training**: Train your own custom YOLOv5 model using labeled datasets for specific use cases.
 
 🖼️🎥 **Image and Video Processing**: Supports both image-based and video-based drowsiness detection.
 
 🚘📡 **Future Integration**: Designed for future integration with car sensors and IoT devices to provide a comprehensive safety solution.
 
 💻🖥️ **Cross-Platform Compatibility**: Works on both macOS and Windows systems.

## Installation Guide 🛠️

### macOS 🍎
📥 **Install Python**:
   - Ensure Python 3.8 or higher is installed. You can download it from [python.org](https://www.python.org/).

📦 **Install Dependencies**:
   ```bash
   python3 -m pip install --upgrade pip
   pip install torch torchvision torchaudio matplotlib numpy opencv-python tqdm pandas pyqt5 lxml
   ```

🔗 **Clone the Repository**:
   ```bash
   git clone https://github.com/ultralytics/yolov5.git
   cd yolov5
   pip install -r requirements.txt
   ```

📓 **Run the Application**:
   - Use the provided Jupyter Notebook to execute the code step-by-step.

### Windows 🪟
📥 **Install Python**:
   - Download and install Python 3.8 or higher from [python.org](https://www.python.org/).

📦 **Install Dependencies**:
   ```cmd
   python -m pip install --upgrade pip
   pip install torch torchvision torchaudio matplotlib numpy opencv-python tqdm pandas pyqt5 lxml
   ```

🔗 **Clone the Repository**:
   ```cmd
   git clone https://github.com/ultralytics/yolov5.git
   cd yolov5
   pip install -r requirements.txt
   ```

📓 **Run the Application**:
   - Open the Jupyter Notebook and follow the steps to execute the code.

## Future Integration 🔮
🚗 **Car Sensors**: Integrate with car sensors to monitor driver behavior and vehicle dynamics.

🌐 **IoT Devices**: Connect with IoT devices for enhanced data collection and analysis.

📱 **Mobile App**: Develop a mobile application to provide real-time alerts and analytics.

☁️ **Cloud Integration**: Store and analyze data on the cloud for better insights and predictive analytics.

## Usage 🧑‍💻
🧠 **Load the YOLOv5 Model**:
   - Use the pre-trained YOLOv5 model or train your custom model.

📹 **Run Real-Time Detection**:
   - Use a webcam or external camera to monitor the driver.

🖼️ **Train Custom Model**:
   - Collect and label images for training.
   - Train the model using the provided scripts.

📊 **Analyze Results**:
   - Visualize detections and analyze results using matplotlib.

## Contributing 🤝
🌟 Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

## License 📜
This project is licensed under the MIT License. See the LICENSE file for details.
