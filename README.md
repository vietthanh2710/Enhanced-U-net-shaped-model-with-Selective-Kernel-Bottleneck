# U-Net Based Model with Selective Kernels Bottleneck

## Abtract
This study enhances the U-net model for steel defect segmentation, emphasizing the critical role of the bottleneck block at the model's end. The traditional bottleneck block is replaced with Selective Kernels, introducing flexibility and efficiency. Unlike fixed-sized convolutions, selective kernels enable the model to adapt to specific features, improving generalization, especially in complex image structures. This modification reduces the number of parameters, enhancing the segmentation model's efficiency and effectiveness.

## Dataset
Alexey Grishin, BorisV, iBardintsev, inversion, Oleg. (2019). Severstal: Steel Defect Detection. Kaggle. https://kaggle.com/competitions/severstal-steel-defect-detection 

Training set: 4389 images 256 x 256  
Validation set: 165 images 256 x 256
Test set: 189 images 256 x 256

## Result
________________________________________
| Metric| U-Net	| U-Net + SK Bottleneck|
________________________________________
| Dice	| 77.38	|     80.96            |
________________________________________
| IoU	  | 63.14	|     68.04            |
