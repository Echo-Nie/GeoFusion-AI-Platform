# 🌍 GeoFusion AI Platform

<p align="center">
  <img src="https://raw.githubusercontent.com/Echo-Nie/GeoFusion-AI-Platform/main/GeoFusion.png" width="500px"/>
</p>

> An intelligent remote sensing image processing platform integrating classification, super-resolution, and colorization.

## 🔧 Project Overview

**GeoFusion AI Platform** is a multi-functional remote sensing image processing system developed by the **YNU Deep Learning Course Group**. The platform integrates three core tasks in remote sensing image processing:

- ✅ Image Classification  
- ✅ Image Super-Resolution  
- ✅ Image Colorization  

Using advanced deep learning techniques, GeoFusion helps users quickly enhance and semantically understand grayscale or low-resolution remote sensing images. It is suitable for various fields such as scientific research, urban planning, and environmental monitoring.

## 📦 Key Features

| Feature | Description |
|--------|-------------|
| Remote Sensing Image Classification | Automatically identify the scene category of an image (e.g., farmland, airport, port) |
| Remote Sensing Image Super-Resolution | Enhance low-resolution images and improve detail visibility |
| Remote Sensing Image Colorization | Automatically add colors to grayscale images for better visualization |

## 🧰 Technology Stack

- Python (3.8+)
- Flask / FastAPI (backend services)
- HTML5 + CSS3 + JavaScript (frontend interface)
- TensorFlow / PyTorch (AI model support)
- Supports multiple pre-trained models (MobileNetV2, ResNet, SRResNet, DeOldify, etc.)

## 📁 Dataset Support

The platform supports the following common remote sensing image formats and public datasets:

### Supported Image Formats:
- `.jpg`, `.jpeg`, `.png`, `.tif`

### Compatible Datasets:
- UCAS-AOD
- NWPU VHR-10
- RSSCN7 Dataset
- RSOD-Dataset
- UC Merced Land-Use Dataset
- SIRI-WHU

## 🚀 Usage Instructions

### Local Deployment (Development Environment)

```bash
# Clone the repository
git clone https://github.com/YNU-RemoteSensing/geofusion.git
cd geofusion

# Install dependencies
pip install -r requirements.txt

# Start the service
python app.py
```

Visit `http://localhost:5000` to use the platform interface for image upload and processing.

## 📝 License

This project is licensed under the [MIT License](LICENSE).

## 📬 Contact Us

For collaboration, feedback, or suggestions, please contact:  📧 Email: nyxchaoji123@163.com

