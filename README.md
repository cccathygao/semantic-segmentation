# Semantic Segmentation

Synthetic masked images for Semantic Segmentation. It contains ~1300 masked images for 75 based images, 45 from Cityscape (outdoor-urban scenes) and 30 from ADE20k (outdoor-nature and indoor scenes).

It covers the following cases:
```
1 class 1 instance (ADE nature + indoor)
N class 1 instance (ADE nature + indoor)
1 class N instance (ADE nature + indoor)
N class N instance (ADE indoor + cityscape)
```

- coco_format folder contains all the mask and image metadata.

- output_masks folder contains all the masked images.
