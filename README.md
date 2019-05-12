# JA_dataset
Joint attention dataset used in our ICCVW2017 paper.

If this dataset helps your research, please cite our paper as follows:

Y. Huang, M. Cai, H. Kera, R. Yonetani, K. Higuchi, and Y. Sato, "Temporal localization and spatial segmentation of joint attention in multiple first-person videos," Proceedings of IEEE International Conference on Computer Vision Workshop (ICCVW2017), pp. 2313-2321, 2017.

We provide code for reagion feature extraction based on selective search.

For example 
```from feature_extraction import selective_search
import cv2
img = cv2.imread('path/to/image')
features = selective_search(img)
```
