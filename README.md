# Real-Time Object Detection using YOLOv3

This project implements real-time object detection using the YOLOv3 (You Only Look Once) algorithm. It detects and labels objects in images or video streams, providing bounding box coordinates and class labels.

## Classes Detected

The YOLOv3 model can detect a wide variety of objects, including but not limited to:
- Person
- Car
- Bicycle
- Motorbike
- Bus
- Truck
- Traffic Light
- Stop Sign
- ...

For a full list of classes, refer to the `coco.names` file in the `data` directory.

## Setup

1. **Download Pre-trained Weights**: Download the pre-trained weights for YOLOv3 from the official website: [YOLO: Real-Time Object Detection](https://pjreddie.com/darknet/yolo/).

2. **Install Dependencies**: Install the required dependencies by running `pip install -r requirements.txt`.

3. **Run the Object Detection Script**: Use the `detect_objects.py` script to perform object detection on images or video streams. You can customize the input source and output format using command-line arguments.

4. **Example Usage**:
   - Detect objects in an image: `python detect_objects.py --image path/to/image.jpg`
   - Detect objects in a video: `python detect_objects.py --video path/to/video.mp4`

## Customization

You can customize the YOLOv3 model by adjusting the configuration files (`yolov3.cfg`), weights, and classes (`coco.names`). Training on custom datasets is also possible, but it requires significant computational resources.

## Acknowledgements

This project uses the YOLOv3 implementation from the [darknet](https://github.com/AlexeyAB/darknet) repository and is based on the work by Joseph Redmon and Ali Farhadi.

![Screenshot 2024-03-13 at 12 08 17 PM](https://github.com/Rahulraonimbalkar/Real-Time-object-detection/assets/117708809/027ad549-95f8-46c2-9cef-f05c3480065b)

![image](https://github.com/Rahulraonimbalkar/Real-Time-object-detection/assets/117708809/03a1c8e5-859c-443a-9c03-cf8a4dfc4cf4)



