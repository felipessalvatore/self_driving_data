# self_driving_data

A simple database for image classification using images from a robot car.

## Documentation
This repository contains a very simple computer vision dataset for classification. It consists of images like 

<p align = 'center'>
<img src = 'examples/1.png' height = '45px'>
<img src = 'examples/2.png' height = '45px'>
<img src = 'examples/3.png' height = '45px'>
<img src = 'examples/4.png' height = '45px'>
</p>
<p align = 'center'>
examples of: left, right, up and up images.
</p>

### Usage
To download the data set just run
```
$ bash download.sh
```

### Data Details
The data is split into three parts: 56,172 data points of training data (train_data.npy, train_labels.npy), 7,022 points of test data (test_data.npy, test_labels.npy), and 7,022 points of validation data (valid_data.npy, valid_labels.npy). Each data point is a flattened 45x80x3 image (a 10800-dimensional vector). Each image has a corresponding label ('0', '1' and '2') representing a command for the robot car ('0' = up, '1' = left, '2' = right).

### Citation
```
  @misc{self_driving_data2018,
    author = {Paula Moraes, Felipe Salvatore},
    title = {Self Driving Data},
    year = {2018},
    howpublished = {\url{https://github.com/felipessalvatore/self_driving_data/}},
    note = {commit xxxxxxx}
  }
```

### Related Work
- Project M (https://medium.com/@project_m)
