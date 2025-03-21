# YOLOv5 Object Detection with Pandas Logging 🚀

This project uses **YOLOv5** by Ultralytics for object detection, customized to log results using **Pandas** and save them in a file. 

## Features
- Perform object detection on images, videos, directories, or streams.
- Log detection results with timestamps, detected objects, confidence scores, and processing times.
- Save logs in a structured `.log` file using Pandas.
- Visualize detected objects with bounding boxes.

## Requirements
- Python 3.8+
- PyTorch
- OpenCV
- Pandas

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/yolov5-object-detection-logging.git
    cd yolov5-object-detection-logging
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the object detection using your custom YOLOv5 model:
```bash
python detect.py --weights yolov5s.pt --source path/to/your/image_or_video
```

### Example:
```bash
python detect.py --weights yolov5s.pt --source data/images/img.jpg
```

## Logging
- Detection results are automatically saved to `detection_logs.log` using Pandas.
- Logs include details like:
  - Timestamp
  - Image Name
  - Detected Class
  - Confidence Score
  - Processing Time

## Contributing
Feel free to fork the repository, create pull requests, or report any issues.

## License
This project is licensed under the **GPL-3.0 License**.

## Acknowledgments
- [Ultralytics YOLOv5](https://github.com/ultralytics/yolov5)
