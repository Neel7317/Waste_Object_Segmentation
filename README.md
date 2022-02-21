# Waste_Object_Segmentation
Waste Object Segmentation with state of art algorithm YOVOv5 trained on Custom Dataset.

Here I address the problem of localizing waste objects from a color image and an optional depth image, which is a key perception component for robotic interaction with such objects. Specifically, our method integrates the intensity and depth information at multiple levels of spatial granularity. Firstly, a scene-level deep network produces an initial coarse segmentation, based on which we select a few potential object regions to zoom in and perform fine segmentation. 

I have tranied multiple YOLOv5 model check the model validation states..

<table><tr>
<td><img src="https://user-images.githubusercontent.com/65647192/154911092-22d63ac4-13ce-4acb-a614-e9937c6ff484.png" width="350" height="300">
<td><img src="https://user-images.githubusercontent.com/65647192/154909742-b0d7421d-ed09-4e1e-806e-27d89e24f6ab.png" width="350" height="300">
<td><img src="https://user-images.githubusercontent.com/65647192/154910673-c0dd3862-0a3d-4957-ab4e-f51bfd704bac.png" width="350" height="300">
</tr>
</table>

To evaluate object detection models like R-CNN and YOLO, the mean average precision (mAP) is used. which is around 95% with this perticular dataset..

<table><tr>
<td><img src="https://user-images.githubusercontent.com/65647192/154912053-a4ae6ac8-1760-4231-a09b-3709c43a3c47.png" width="350" height="300">
<td><img src="https://user-images.githubusercontent.com/65647192/154913346-939b3ce6-ec60-48e0-bec6-a3bc5c508b57.png" width="350" height=300>
<td><img src="https://user-images.githubusercontent.com/65647192/154913504-966a2164-4037-493a-a9b6-40ce996c6000.png" width="350" height="300">
</tr>
</table>

# Results from model-7

![3](https://user-images.githubusercontent.com/65647192/154914243-5cd1e9eb-a6ec-48b4-9232-261c104b4064.jpg)

Due to less amount of data here i have trained yolov5 for only 8 class detection and confusion matrix for best model from tranied models so far look as below

<img src="https://user-images.githubusercontent.com/65647192/154914789-8c3ad62f-7c92-4c78-8d7e-3b4b295ee63f.png" width="500" height="500">

## -->Note: Pretrained weights are confidential. If you need then feel free to reach out for industrial use purpose..
