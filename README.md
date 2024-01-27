# Point Cloud Segmentation Using PointNet


<div align="center">
    <a href="https://colab.research.google.com/github/reshalfahsi/point-cloud-segmentation/blob/master/Point_Cloud_Segmentation_Using_PointNet.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="colab"></a>
    <br />
</div>

In this project, PointNet is leveraged for the segmentation of parts of a certain shape in the form of point cloud data. The data points are obtained from the ShapeNet dataset, i.e., ShapeNetCore. This project chooses the shape of a motorbike. PointNet is utilized due to its nature, which is invariant to permutation. Keep in mind that point cloud data has zero care for the spatial relationship between points in the point cloud, even though it stores information regarding the object's location in the space. In other words, the order of points must be negligible and not influence the result.

## Experiment

Proceed to the following [link](https://colab.research.google.com/github/reshalfahsi/point-cloud-segmentation/blob/master/Point_Cloud_Segmentation_Using_PointNet.ipynb) to unveil the implementation shrouded in the **cloud** of secrets.

## Result

## Quantitative Result

The numeric values below bespeak the performance of the model.

Test Metric  | Score
------------ | -------------
Loss         | 0.160
IoU          | 0.255


## Loss and IoU Curve

<p align="center"> <img src="https://github.com/reshalfahsi/point-cloud-segmentation/blob/master/assets/loss_curve.png" alt="loss_curve" > <br /> The loss curve on the training set and the validation set of PointNet. </p>

<p align="center"> <img src="https://github.com/reshalfahsi/point-cloud-segmentation/blob/master/assets/iou_curve.png" alt="iou_curve" > <br /> The IoU curve on the training set and the validation set of PointNet. </p>


## Qualitative Result

Click the following image to see the interactive result of the model.

<p align="center"> 
   <a href="https://reshalfahsi.github.io/point-cloud-segmentation">
       <img src="https://raw.githubusercontent.com/reshalfahsi/point-cloud-segmentation/master/assets/result.png" alt="qualitative_result"> 
   </a>
   The segmentation result for the motorbike subcategory of the ShapeNet dataset with the label: <i>wheel</i>, <i>seat</i>, <i>gas_tank</i>, <i>light</i>, and <i>handle</i>.
</p>


## Credit

- [Point Cloud Segmentation with PointNet](https://keras.io/examples/vision/pointnet_segmentation/)
- [PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation](https://arxiv.org/pdf/1612.00593.pdf)
- [ShapeNet](https://shapenet.org/)
- [PointNet.pytorch](https://github.com/fxia22/pointnet.pytorch)
- [PyTorch Lightning](https://lightning.ai/docs/pytorch/latest/)
