# Dataset-and-Benchmark-for-Ship-Detection-in-Complex-Optical-Remote-Sensing-Image
A dataset named Ship Collection in Complex Optical Scene (SCCOS) is constructed, which is obtained from multiple platform sources including Google Earth, Microsoft map, Worldview-3, Pleiades, Orbview-3, Jilin-1 and Ikonos satellites. 

## Dataset Description
Ship detection plays a pivotal role in numerous military and civil applications, yet detecting ships in complex maritime and aerial environments remains a challenging task. While several publicly available datasets for ship detection have been introduced by researchers, most of them do not adequately address the impacts of diverse and intricate environmental factors, which makes the trained algorithms difficult to apply for practical application scenes involving clouds, sea clutter, complex lighting, and facility interferences, limiting the effectiveness and robustness of the detection models. To advance the field of ship detection method research, we propose a dataset named Ship Collection in Complex Optical Scene (SCCOS), which is obtained from multiple platform sources including Google Earth, Microsoft map, Worldview-3, Pleiades, Orbview-3, Jilin-1 and Ikonos satellites. The dataset comprehensively considers complex scenes such as thin clouds, mist, thick clouds, light shadows, sea clutter, port facilities. Additionally, we conduct experiments on this dataset with eleven representative detection algorithms and establish a performance benchmark, which can provide the theoretical basis and practical reference for the design and optimization of subsequent ship detection models.

Table 1 Image source statistics of the proposed dataset
![Github0](https://github.com/user-attachments/assets/c8f1fee0-9fab-4ec7-a80a-16edc15bd023)


![Github1](https://github.com/user-attachments/assets/cd920bec-6378-4ad9-8f23-bcfb67202cc2)
Figure 1 Complex environmental interference situation of the dataset. (a) Mist interference. (b) Thin cloud interference. (c) Thick cloud interference. (d) Shadow interference. (e) Sea clutter interference. (f) Port facility interference.

![image39-1](https://github.com/user-attachments/assets/be5f7064-ed07-496b-8896-9dadc8d08ffc)
Figure 2 Detection results provided by different baseline models: (a) Rotated faster R-CNN, (b) SASM, (c) Oriented RepPoints and (d) ground truth.


## Dataset Download and Usage License
The dataset is available on the following links:

**Baidu Driver**: https://pan.baidu.com/s/1SFutPf2JqN0SONF7RfZA5A (**extraction password: fwth**)

**Google Driver**: https://drive.google.com/drive/folders/1VGJ6e9NVgN1BXvA8BkgGusWKW69odeUn?usp=sharing

Star this project and we will update the corresponding data consistently. **If you want use our dataset, please follows these rules:**

• Use of Google Earth images must respect the "Google Earth" terms of use.

• All images and their associated annotations in SCCOS can be used for academic purposes only, but any commercial use is prohibited.

## Citation 
If you need to use our dataset to make research, **please cite our essay (Dataset and Benchmark for Ship Detection in Complex Optical Remote Sensing Image) (The essay is acceped and the link is below)**.

```
@article{hu2024dataset,
  title={Dataset and Benchmark for Ship Detection in Complex Optical Remote Sensing Image},
  author={Hu, Jianming and Zhi, Xiyang and Shi, Tianjun and Wang, Junjie and Li, Yuelong and Sun, Xiaogang},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  year={2024},
  publisher={IEEE}
}
```
## Contact
If you have any problem or feedback in using SCCOS dataset, please contact me at hujianming@hit.edu.cn.
