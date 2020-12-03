# pytorch_objectdetecttrack
Object detection in images, and tracking across video frames.
This code is based on tracking based object detection(Yolo V3), i.e) It differs from yolo in the ability to distinguish two objects of same type, by implementing tracking updates on the real-time detection feed.

Full story at:
https://towardsdatascience.com/object-detection-and-tracking-in-pytorch-b3cf1a696a98

References:
1. YOLOv3: https://pjreddie.com/darknet/yolo/
2. Erik Lindernoren's YOLO implementation: https://github.com/eriklindernoren/PyTorch-YOLOv3
3. YOLO paper: https://pjreddie.com/media/files/papers/YOLOv3.pdf
4. SORT paper: https://arxiv.org/pdf/1602.00763.pdf
5. Alex Bewley's SORT implementation: https://github.com/abewley/sort
6. Installing Python 3.6 and Torch 1.0: https://medium.com/@chrisfotache/getting-started-with-fastai-v1-the-easy-way-using-python-3-6-apt-and-pip-772386952d03

# Instructions
The script "object_tracker.py" when run, execites object detection on web cam feed, real-time.

run : python object_tracker.py
