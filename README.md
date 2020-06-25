# Automatic license plate recognition using YoloV5 and PyTesseract
#### To get more hands on, check [this article](https://towardsdatascience.com/indian-car-license-plate-detection-using-yolo-v5-ae2574578175)
#### This project is a successor to [this](https://github.com/sid0312/ANPR)

#### Refer to our data preparation at [this link](https://github.com/sid0312/ANPR/blob/master/notebooks/data_preparation.ipynb)

### Training 

###### For training, refer to [this link](yolov5_license_plate_train.ipynb)

## Train logs

<p align="center">  
  <img src="https://github.com/sid0312/anpr_yolov5/blob/master/visualizations/results.png">
</p>

<p align="center">  
  <img src="https://github.com/sid0312/anpr_yolov5/blob/master/visualizations/labels.png">
</p>


## Validation Results

<p align="center">  
  <img src="https://github.com/sid0312/anpr_yolov5/blob/master/results/test_batch0_gt.jpg">
</p>

## Detection
```
git clone https://github.com/sid0312/anpr_yolov5
cd anpr_yolov5
python detect.py --source sample_cars/  --weights weights/best.pt --conf 0.4
```
 ###### For detection, refer to [this link](anpr_test.ipynb)
