# YOLO Object Detection V9 (with pre-trained models New V9)

![YOLO Logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSkJBn3FSB2gHIcOj3ibbCUuPViLHAh2xqg9VRCwM0Ppg&s)

## Overview

This repository implements YOLO (You Only Look Once) object detection algorithm tailored for video analysis. YOLO is a state-of-the-art, real-time object detection system that can detect multiple objects in an image or frame in one pass.

## Features

- **Video Object Detection**: Detect objects in videos using the YOLO algorithm.
- **Real-Time Processing**: Fast and efficient processing for real-time or near real-time applications.
- **Pre-trained Models**: Support for multiple pre-trained YOLO models for various object detection tasks.
- **Easy Integration**: Simple interface for integrating YOLO into video processing pipelines.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/anjanbudige/yolo-object-detection.git
    ```

2. **Install dependencies:**

   use colab or anaconda to open python notebook file (pynb file)
   
    ```bash
    git clone https://github.com/WongKinYiu/yolov9
    cd yolov9
    pip install -r requirements.txt
    ```

4. **Download pre-trained YOLO weights and configuration files.**
   Below we have given pretrained models, you can use them for object detection

## Usage

To perform object detection on a video, follow these steps:

1. **Ensure dependencies are installed and pre-trained model files are downloaded.**
2. **Run the detection script:**

    ```bash
    python detect_video.py --weights "model.pt file" --conf "0.1 to 1.0" --source path/to/input/video.mp4 --device cpu
    ```

    - Replace `path/to/input/video.mp4` with the path to your input video file.
    - Provide paths to YOLO weights, configuration, and class files.

3. **Adjust parameters as needed.**

## Pre-trained Models

This repository includes links to pre-trained YOLO weights and configuration files for various YOLO versions:

- **YOLOV9 c Converted**: [Download](https://github.com/WongKinYiu/yolov9/releases/download/v0.1/yolov9-c-converted.pt)
- **YOLOV9 e Converted**: [Download](https://github.com/WongKinYiu/yolov9/releases/download/v0.1/yolov9-e-converted.pt)
- **YOLOV9 c**: [Download](https://github.com/WongKinYiu/yolov9/releases/download/v0.1/yolov9-c.pt)
- **YOLOV9 e**: [Download](https://github.com/WongKinYiu/yolov9/releases/download/v0.1/yolov9-e.pt)
- **Gelan c**: [Download](https://github.com/WongKinYiu/yolov9/releases/download/v0.1/gelan-c.pt)
- **Gelan e**: [Download](https://github.com/WongKinYiu/yolov9/releases/download/v0.1/gelan-e.pt)

## Contributing

Contributions are welcome! If you have any ideas, enhancements, or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
