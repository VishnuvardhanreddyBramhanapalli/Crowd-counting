# Crowd-counting
#a project based on python,flask,fast API,faster RCNN and HTML
## Model Weights
Due to GitHub's file size limits, model weights are not uploaded.  
Please manually download the Faster R-CNN model:
- Download from [Torchvision Model Zoo](https://pytorch.org/vision/stable/models.html#faster-r-cnn)

Or programmatically:
```python
from torchvision.models.detection import fasterrcnn_resnet50_fpn, FasterRCNN_ResNet50_FPN_Weights

# This automatically downloads the weights
model = fasterrcnn_resnet50_fpn(weights=FasterRCNN_ResNet50_FPN_Weights.COCO_V1)
