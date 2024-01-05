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

2. Move to the yolov5 directory:

   ```bash
   cd yolov5
   
3. Install the required dependencies:
   
   ```bash
   pip install -U -r requirements.txt

4. File Structure
   ```Markdown
   dataset/
   ├── train/
   │   ├── helmet/
   │   │   ├── image1.jpg
   │   │   ├── image2.jpg
   │   │   └── ...
   │   ├── no_helmet/
   │   │   ├── image3.jpg
   │   │   ├── image4.jpg
   │   │   └── ...
   └── test/
       ├── helmet/
       │   ├── test_image1.jpg
       │   ├── test_image2.jpg
       │   └── ...
       ├── no_helmet/
       │   ├── test_image3.jpg
       │   ├── test_image4.jpg
       │   └── ...


5. Training the YOLOv5 Classification Model:
   ```bash
   python train.py --img 640 --batch 16 --epochs 50 --data dataset/data.yaml --cfg models/yolov5s.yaml --weights '' --name helmet_detection
   #Adjust the parameters according to your dataset and requirements.


6. Run inference on test images:
   ```bash
   python detect.py --weights path/to/your/weights.pt --img-size 640 --conf 0.5 --source dataset/test/
   #Replace path/to/your/weights.pt with the path to your trained weights.

View the results in the runs/detect directory.

🎉 Congratulations! Your YOLOv5 Helmet and No Helmet Classification model is ready to go!

## Feel free to modify this README file to suit your project's specifics. Happy coding! 🤖✨

