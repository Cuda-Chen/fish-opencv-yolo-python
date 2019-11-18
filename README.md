# fish-opencv-yolo-python
Fish object detection with YOLOv3 on opencv-python.

# Set up and Run Demo
First, download the pretrained weights from [here](https://drive.google.com/file/d/1L6JgzbFhC7Bb_5w_V-stAkPSgMplvsmq/view?usp=sharing) and put it to `yolo-fish`
directory.

Then type the following commands (assuming you are using `conda`):
```
$ conda create -n fish-opencv-yolo-python python=3.6 pip
$ conda activate fish-opencv-yolo-python
$ pip install -r requirements.txt
$ python yolo.py --image ./images/DSC_0061.JPG --yolo yolo-fish
```

# Reference
This project is originated from below pyimagesearch article:
- https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/
