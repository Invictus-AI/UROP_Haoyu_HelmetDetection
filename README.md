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

## Try out the detector

in the yolov5-master folder, with env1 activated, use this command:

```bash
python detect.py --source test.png --weights 400epochs.pt --img 640
```
