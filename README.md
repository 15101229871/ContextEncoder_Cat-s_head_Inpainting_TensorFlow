# ContextEncoder_Cat-s_head_Inpainting_TensorFlow
Inplementing the paper 'Context Encoders: Feature Learning by Inpainting' by TensorFlow
# Introduction
This code mainly inplement the paper [Context Encoders: Feature Learning by Inpainting](https://arxiv.org/abs/1604.07379), and we use the dataset of cats' head for training and testing.
![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/paper.jpg)
# Dataset
Cat dataset: http://academictorrents.com/details/c501571c29d16d7f41d159d699d0e7fb37092cbd
Download the cat dataset, then unzip it and put them into the file 'cat_dataset'. Finally, execute the file 'prepocess_cat_dataset.py' to crop the cats' head.
```
├── cat_dataset
     ├── 00000001_000.jpg
     ├── 00000001_000.jpg.cat
     ├── 00000001_001.jpg
     ├── 00000001_001.jpg.cat
     ...
├── cats_bigger_than_64x64
     ├── 00000001_000.jpg
     ├── 00000001_001.jpg
     ├── 00000001_002.jpg
     ├── 00000001_003.jpg
     ...
├── cats_bigger_than_128x128
     ├── 00000001_000.jpg
     ├── 00000001_001.jpg
     ├── 00000001_002.jpg
     ├── 00000001_003.jpg
     ...
```
# Python packages
1. tensorflow-gpu1.4.0
2. numpy
3. scipy
4. pillow
5. cv2
6. glob
# Results
|cat|1|2|3|
|-|-|-|-|
|a|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/1.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/2.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/3.jpg)|
|b|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/4.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/25.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/6.jpg)|
|c|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/7.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/8.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/9.jpg)|
|d|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/10.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/11.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/12.jpg)|
|e|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/13.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/14.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/15.jpg)|
|f|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/16.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/17.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/18.jpg)|
|g|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/19.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/20.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/21.jpg)|
|h|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/22.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/23.jpg)|![](https://github.com/MingtaoGuo/ContextEncoder_Cat-s_head_Inpainting_TensorFlow/blob/master/IMAGES/24.jpg)|
# Acknowledgement
[RelativisticGAN](https://github.com/AlexiaJM/RelativisticGAN)-AlexiaJM
