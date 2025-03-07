# detectLive: Real-Time Object Detection with YOLOv5 

detectLive is a real-time object detection system using **YOLOv5** and your **laptop webcam**. It can detect multiple objects live and highlight them on-screen.  

## Features  
✅ Uses **YOLOv5** for accurate detection  
✅ Runs in **real-time** on CPU/GPU  
✅ Works with a **laptop webcam** or external cameras  
✅ Detects **common objects** (people, phones, keys, etc.)  


## Installation & Setup  
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
