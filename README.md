## YOLOv5 for traffic sign recognition

## Pretrained Checkpoints
Checkpoints based on RTSD-2000:  
- [yolov5s_rtsd2000.pt](https://drive.google.com/file/d/1u0_kmVlPW8t_ObRn2wBq7dZvVZu6ugHt/view?usp=sharing); mAP = 0.71
- [yolov5m_rtsd2000.pt](https://drive.google.com/file/d/1OQEvDg_FyXME0H9aDS6Q62Bu4JHyUX4V/view?usp=sharing); mAP = 0.65
- [yolov5l_rtsd2000.pt](https://drive.google.com/file/d/1bEG_RUWb26WHmvukpXJpqPTekExe0r7W/view?usp=sharing); mAP = 0.72


## Requirements
Python 3.8 or later with all [requirements.txt](https://github.com/anastasiyaperk/yolov5_traffic_sign_recognition/blob/master/requirements.txt) dependencies installed, including `torch>=1.7`. To install run:
<!-- $ sudo apt update && apt install -y libgl1-mesa-glx libsm6 libxext6 libxrender-dev -->
```bash
$ pip install -r requirements.txt
```

## Dataset

Dataset based on [Russian Traffic Sign Dataset](https://graphics.cs.msu.ru/ru/node/1266) and
contains 2000 images from RTSD.
Click [here](https://drive.google.com/drive/folders/1HB5liX3oxdvNZKKBW7vA2FU-FwmDHRd4?usp=sharing) to download RTSD-2000.

## Tutorials

Google Colab for **yolov5s model** notebook with free GPU:  
<a href="https://colab.research.google.com/github/anastasiyaperk/yolov5_traffic_sign_recognition/blob/master/tutorials/Train_300_yolov5s.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>  
Google Colab for **yolov5m model** notebook with free GPU:  
<a href="https://colab.research.google.com/github/anastasiyaperk/yolov5_traffic_sign_recognition/blob/master/tutorials/Train_300_yolov5m.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>  
Google Colab for **yolov5l model** notebook with free GPU:  
<a href="https://colab.research.google.com/github/anastasiyaperk/yolov5_traffic_sign_recognition/blob/master/tutorials/Train_300_yolov5l.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>  











