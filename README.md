# YOLOv5 Helmet and No Helmet Classification

🚀 Welcome to the YOLOv5 Helmet and No Helmet Classification project! This project focuses on training a YOLOv5 model for detecting and classifying images into 'Helmet' and 'No Helmet' categories.

## Getting Started

### Prerequisites

- Python 3.8 or later
- [Git](https://git-scm.com/)
- [YOLOv5 Official Repository](https://github.com/ultralytics/yolov5)

### Installation

1. Clone the YOLOv5 repository:

   ```bash
   git clone https://github.com/ultralytics/yolov5.git
   
2. cd yolov5
3. pip install -U -r requirements.txt


Certainly! Below is a sample README file for your YOLOv5 helmet and no helmet classification project. Feel free to customize it according to your specific project details:

markdown
Copy code
# YOLOv5 Helmet and No Helmet Classification

🚀 Welcome to the YOLOv5 Helmet and No Helmet Classification project! This project focuses on training a YOLOv5 model for detecting and classifying images into 'Helmet' and 'No Helmet' categories.

## Getting Started

### Prerequisites

- Python 3.8 or later
- [Git](https://git-scm.com/)
- [YOLOv5 Official Repository](https://github.com/ultralytics/yolov5)

### Installation

1. Clone the YOLOv5 repository:

   ```bash
   git clone https://github.com/ultralytics/yolov5.git
Navigate to the YOLOv5 directory:

bash
Copy code
cd yolov5
Install the required dependencies:

bash
Copy code
pip install -U -r requirements.txt
    
## Training the YOLOv5 Classification Model 

python train.py --img 640 --batch 16 --epochs 50 --data dataset/data.yaml --cfg models/yolov5s.yaml --weights '' --name helmet_detection
Adjust the parameters according to your dataset and requirements.

## Prediction
Download the trained weights from Google Drive or train your model.

Run inference on test images:

python detect.py --weights path/to/your/weights.pt --img-size 640 --conf 0.5 --source dataset/test/
Replace path/to/your/weights.pt with the path to your trained weights.

View the results in the runs/detect directory.

🎉 Congratulations! Your YOLOv5 Helmet and No Helmet Classification model is ready to go!

## Feel free to modify this README file to suit your project's specifics. Happy coding! 🤖✨


Replace `[Google Drive](your_drive_link)` with the actual link where users can download

