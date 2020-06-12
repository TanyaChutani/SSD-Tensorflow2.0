# Single Shot Detector for Densely Packed Objects

- A TensorFlow implementation of object detection paper: SSD - Single Shot MultiBox Detector.
- Replaced the existing VGG backbone with DenseNet to achieve better performance.
- Calibrated the default anchors to better suit for the new dataset
- Trained the model on the SKU110K dataset consisting of 12k grocery store images with each image having 200 objects on average, often appearing similar or identical and positioned in close proximity.

## Model
![](https://github.com/TanyaChutani/SSD-Tensorflow/blob/master/images/ssd.jpeg?raw=true)

## Result
![](https://github.com/TanyaChutani/SSD-Tensorflow/blob/master/images/ssd1.png)
![](https://github.com/TanyaChutani/SSD-Tensorflow/blob/master/images/ssd3.png)

#### Matched default boxes
![](https://github.com/TanyaChutani/SSD-Tensorflow/blob/master/images/ssd_matched.png)

## Pretrained Weights [Download](https://drive.google.com/drive/folders/1--ipuIGCk83vhDZ5QXSz3YVpjdd1Co7d?usp=sharing)

    @misc{liu2015ssd,
        title={SSD: Single Shot MultiBox Detector},
        author={Wei Liu and Dragomir Anguelov and Dumitru Erhan and Christian Szegedy and Scott Reed and Cheng-Yang Fu and Alexander                       C.Berg},
        year={2015},
        eprint={1512.02325},
        archivePrefix={arXiv},
        primaryClass={cs.CV}
    }
