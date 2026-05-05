# Semantic Segmentation for Autonomous Driving Using U-Net Architectures

### Dataset Link: 
https://www.kaggle.com/datasets/kumaresanmanickavelu/lyft-udacity-challenge/data
OR
https://datasetninja.com/self-driving-cars#download

# Run the project
```bash
conda create -n your_env_name python==3.8 -y
```

```bash
conda activate your_env_name
```

```bash
git clone https://github.com/MannShrestha/Semantic-Segmentation-For-Autonomous-Driving.git
```

```bash
pip install -r requirements.txt
```
# Data Sample
![Imagesample](https://github.com/MannShrestha/Semantic-Segmentation-For-Autonomous-Driving/blob/main/Images/image%20samples.png)

# Data Distribution
![Comparision](Images/histogram_data_distribution.png)

# U-Net Architectures
![Shallow-U-Net](Images/Sallow_UNet.jpg)

<table>
  <tr>
    <td align="center" style="padding-right:10px;">
      <img src="Images/MobileNetV2_arc.jpg" alt="Image 1" width="500"/>
    </td>
    <td align="center">
      <img src="Images/resnetUnet_arc.jpg" alt="Image 2" width="500"/>
    </td>
  </tr>
</table>

# Training curves
![Comparision](Images/Combine_comparision.jpg)

# IOU per class
![IOU](Images/IOU_per_class_comp.jpg)
![mIoU](Images/mIOU-cfm.jpg)
![Metric-comparision](Images/metric_comparision.jpg)

# Train and Validation Comparison
<table>
  <tr>
    <td align="center" style="padding-right:10px;">
      <img src="Images/train_metric_comp.png" alt="Image 1" width="500"/>
    </td>
    <td align="center">
      <img src="Images/val_metric_comp.png" alt="Image 2" width="500"/>
    </td>
  </tr>
</table>

