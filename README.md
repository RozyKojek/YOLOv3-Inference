# YOLOv3-Inference
This repository is created as the Material for the Professional Ethic Course of FT-UMS.

## Requirements
1. Python 3.6 or aboove
2. Pytorch 1.4.0 or above
3. Numpy
4. Matplotlib
5. OpenCV (cv2)
6. Jupyter Notebook

## Project Setup
Make sure the folder structure look like this
```
.
├── cfg
│   ├── yolov3-continual.cfg
│   ├── yolov3-pascal-19class.cfg
│   ├── yolov3-pascal-1class.cfg
│   ├── yolov3-pascal-2class.cfg
│   ├── yolov3-pascal-3class.cfg
│   ├── yolov3-pascal.cfg
│   ├── yolov3-tiny3-DMC.cfg
│   ├── yolov3-tiny3.cfg
│   └── yolov3.cfg
├── utils
│   ├── adabound.py
│   ├── continual_utils.py
│   ├── datasets.py
│   ├── evolve.sh
│   ├── gcp.sh
│   ├── google_utils.py
│   ├── layers.py
│   ├── parse_config.py
│   ├── torch_utils.py
│   └── utils.py
├── weights
    ├── best_car.pt
    └── best_person.pt
├── detect.py
├── inference.ipynb
└── models.py
```

## Downloading the Weights
You can download the weights in this link [here.](https://drive.google.com/drive/folders/1olvkyvQysahvxT0znz1itsL5cFdBELCu?usp=sharing)

## Running the Inference
You can easily run the inference using two methods below:
### Running the jupyter notebook
1. Make sure jupyter notebook is installed.
2. Open terminal/cmd/powershell in the main directory.
3. Type jupyter notebook in the terminal/cmd/powershell
```
jupyter notebook
```
