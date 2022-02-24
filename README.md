# yolov5-fastapi-demo

This is a demo FastAPI app that allows a user to upload image(s), perform inference using a pretrained YOLOv5 model, and receive results in JSON format. This repo also includes Jinja2 HTML templates, so you can access this interface through a web browser at localhost:8000

This is used from project of master en computer science for FMAT - UADY. For detec facemask with YOLOv5 and FastAPI for made API for consult.

## Requirements
Python 3.8 or later with all requirements.txt dependencies installed, including torch>=1.7 (per https://github.com/ultralytics/yolov5).

To install run:
```
pip install -r requirements.txt
```

## Credits

This repository is a wrapper around YOLOv5 from Ultralytics: https://github.com/ultralytics/yolov5

Repository for FastAPI: https://github.com/tiangolo/fastapi