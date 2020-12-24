12/23/2020 - Updated 3D Bounding Boxes sizes from wlh [1.6, 3.9, 1.56] to [3.9, 1.56, 1.6] lhw for kitti format
second/configs/car.lite.config
second/configs/car.lite.argo.config

second/
create_data.py - create kitti dataset info files for train, val and test

second/pytorch/
train.py - Provide functions to train, evaluate and generated predicted bounding boxes by adding the code in line 531

second/data/
kitti_dataset.py - Modified from write only to write + create in line 293
