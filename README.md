# Averial-visible-to-infrared-image-translation
AVIID dataset and the code of some representative image-to-image methods for our paper **Aerial Visible-to-Infrared Image Translation : Methods, Dataset and Baseline**
## AVIID dataset
<img src="https://github.com/silver-hzh/Averial-visible-to-infrared-image-translation/blob/main/img/AVIID1.png" width="400" height="350" alt="AVIID-1"/><img src="https://github.com/silver-hzh/Averial-visible-to-infrared-image-translation/blob/main/img/AVIID2.png" width="400" height="350" alt="AVIID-2"/><img src="https://github.com/silver-hzh/Averial-visible-to-infrared-image-translation/blob/main/img/AVIID31.png" width="400" height="250" alt="AVIID-3-1"/><img src="https://github.com/silver-hzh/Averial-visible-to-infrared-image-translation/blob/main/img/AVIID32.png" width="400" height="250" alt="AVIID-3-2"/>

Our proposed dataset consists of three sub-datasets, named AVIID-1, AVIID-2 and AVIID-3. The AVIID-1 contains 993 pairs of paired visible-infrared images with a resolution of 434 $\times$ 434. The AVIID-2 contains 1090 pairs of paired visible-infrared images with a resolution of 434 $\times$ 434. The AVIID-3 contains 1280 pairs of paired visible-infrared images with a resolution of 512 $\times$ 512. The targets in this datset are standard vehicles on the road, including cars, buses, vans, and urban off-road vehicles. The dataset can be downlaoded from <https://pan.baidu.com/s/1Tj-8PlsGmRlFv_zlm5Rx6Q>, the code is 41uv.
## Code of Baseline methods
In our paer, we evaluate ten representative image-to-image methods on our AVIID datset, including Pix2Pix, BicycleGAN, CycleGAN, GCGAN, CUT, DCLGAN, UNIT, MUNIT, DRIT and MSGAN. The details of training and testing of these methods in our paer can be seen here.
### Requirements
**For Pix2Pix, BicycleGAN, CycleGAN, GCGAN, CUT, DCLGAN, UNIT, and MUNIT:**
- Python 3.7 or higher 
- Pytorch 1.8.0 or higher, torchvison 0.9.0 or higher
- Tensorboard, TensorboardX, Pyyaml, Pillow, dominate, visdom

**For DRIT and MSGAN:**
- Python 3.6
- Pytorch 0.4.0, torchvision 0.2.0
- Tensorboard, TensorboardX
### Pix2Pix
** Train on AVIID-1**
** Test on AVIID-1**
** Train on AVIID-2**
** Test on AVIID-2**
** Train on AVIID-3**
** Test on AVIID-3**

