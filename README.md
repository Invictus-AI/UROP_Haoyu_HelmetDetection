# UROP_Haoyu_HelmetDetection

## Set up a virtual environment

In the yolov5-master folder, use the following command to create a virtual environment env1:

```bash
python3 -m venv env1
```

After setting up env1, activate it:

```bash
source env1/bin/activate
```

## Install all dependencies

In the yolov5-master folder, with env1 activated, use the following command to install all dependencies:

```bash
python3 -m pip install -r requirements.txt
```

## Try out the detector on photos:

In the yolov5-master folder, with env1 activated, use this command:

```bash
python detect.py --source test.png --weights 300epochs.pt --img 640
```
![alt text](https://github.com/Invictus-AI/UROP_Haoyu_HelmetDetection/blob/main/photo_test.png?raw=true)

## Try out the detector on YouTube videos:

In the yolov5-master folder, with env1 activated, use this command:

```
python detect.py --source [any youtube link such as: https://www.youtube.com/watch?v=oHEWcefPWws] --weights 300epochs.pt
```
![alt text](https://github.com/Invictus-AI/UROP_Haoyu_HelmetDetection/blob/main/video_test.png?raw=true)

## Try out the detector on camera streaming:

In the yolov5-master folder, with env1 activated, use this command:

```
python detect.py --source 0 --weights 300epochs.pt
```


## Metrics during training
![alt text](https://github.com/Invictus-AI/UROP_Haoyu_HelmetDetection/blob/main/screenshot.png?raw=true)

