# 🚘 License Plate Detection using YOLOv8 (Jupyter Notebook)

This project demonstrates license plate detection using the YOLOv8 object detection model. The entire implementation is done in a Jupyter Notebook, making it easy to understand, visualize, and modify. The model processes a video input, detects license plates in each frame, and saves the annotated result as a new video file.

## 🙏 Acknowledgements
This project was built with reference and inspiration from the following GitHub repository:

### 🔗 Arijit1080/Licence-Plate-Detection-using-YOLO-V8
Credit to Arijit1080 for sharing the dataset reference and implementation ideas that helped guide this notebook.

## 📌 Features

- ✅ Built using [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- 📗 Implemented entirely in a Jupyter Notebook
- 🎥 Accepts video input (`demo.mp4`)
- 💾 Outputs annotated video (`output_video.mp4`)
- 🧠 Easily extendable for other object detection tasks

## 📁 Project Files

- `License_Plate_detection.ipynb` — Main notebook with the detection logic  
- `demo.mp4` — Sample video file for input  
- `output_video.mp4` — Output video with detected license plates  
- `best.pt` — Trained YOLOv8 model weights (optional; add if available)  
- `README_License.md` — This documentation file  

## ⚙️ Setup Instructions

1. **Install dependencies**

Make sure you have Python 3.8+ installed, then install the required packages:

```bash
pip install ultralytics
pip install opencv-python
```


