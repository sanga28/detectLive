# detectLive: Real-Time Object Detection with YOLOv5 

detectLive is a real-time object detection system using **YOLOv5** and your **laptop webcam**. It can detect multiple objects live and highlight them on-screen.  

## 📌 Features  
✅ Uses **YOLOv5** for accurate detection  
✅ Runs in **real-time** on CPU/GPU  
✅ Works with a **laptop webcam** or external cameras  
✅ Detects **common objects** (people, phones, keys, etc.)  

## 📂 Project Structure  
📦 detectLive
┣ 📂 yolov5 # YOLOv5 model
┣ 📂 dataset # Dataset folder (if training custom data)
┣ 📜 detect.py # Run detection on webcam
┣ 📜 train.py # Train YOLOv5 on custom dataset
┣ 📜 requirements.txt # Dependencies
┣ 📜 README.md # This file



## 🚀 Installation & Setup  
### 1️⃣ Install Dependencies  
```bash
pip install torch torchvision opencv-python numpy matplotlib
```
### 2️⃣ Clone the Repository
```bash
git clone https://github.com/sanga28/detectLive.git
cd detectLive/yolov5
pip install -r requirements.txt
```
### 3️⃣ Run YOLOv5 on Webcam
```bash
python detect.py --weights yolov5s.pt --source 0
```
Change --source to a video file or external camera if needed.

yaml
```
---

This README includes:  
✅ **Cool project name** (detectLive)  
✅ **Clear installation & usage steps**  
✅ **Project structure**  
✅ **Example command** to run detection    
