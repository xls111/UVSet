# PRD-UVSet

A new urban village dataset in our recent work "[Fine-Grained Urban Village Extraction By Mask Transformer From High-Resolution Satellite Images in Pearl River Delta](https://ieeexplore.ieee.org/document/10623471)" on [IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=4609443).

## Description

The dataset contains 2102 pairs of high-resolution images of size 512×512 from Pearl River Delta in 2020 .The process of constructing the urban village dataset can be summarized as follows: 

* 16 training images and 10 testing images are evenly and randomly selected from the 329 Google Earth images in Pearl River Delta

* The 26 selected images are annotated through manual visual interpretation to obtain UV. 

* All vectors of UV annotated in the above steps will be rasterized into pixel-wise annotations, where the non-urban village area and the urban village area are denoted by 0 and 255, respectively.

## Experiments

### Method

**MaskUV**

![](C:\Users\czq\AppData\Roaming\marktext\images\2024-08-12-23-32-25-image.png)

### Result

![](C:\Users\czq\AppData\Roaming\marktext\images\2024-08-12-23-34-01-image.png)

## Download

* [BaiduYun](https://pan.baidu.com/s/115aI9PpC7OzRdi9MS4gRVw) (qja6) 
  

## Citation

If you find our work useful for your research, please consider citing our paper:

```latex
@ARTICLE{10623471,
  author={Chai, Zhuoqun and Liu, Mengxi and Shi, Qian and Zhang, Yuanyuan and Zuo, Minglin and He, Da},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing}, 
  title={Fine-Grained Urban Village Extraction by Mask Transformer From High-Resolution Satellite Images in Pearl River Delta}, 
  year={2024},
  volume={17},
  number={},
  pages={13657-13668},
  keywords={Feature extraction;Urban areas;Transformers;Training;Buildings;Rivers;Remote sensing;Deep learning;Pearl River Delta (PRD);remote sensing;urban villages (UVs);urbanization},
  doi={10.1109/JSTARS.2024.3434487}}

```
