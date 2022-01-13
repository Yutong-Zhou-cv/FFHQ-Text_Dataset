# FFHQ-Text👸
![ ](https://img.shields.io/badge/Python-3.6-green.svg?style=plastic)
![ ](https://img.shields.io/badge/License-CC-green.svg?style=plastic)
![ ](https://img.shields.io/badge/Images-760-ff69b4.svg?style=plastic)
![ ](https://img.shields.io/badge/Resolution-1024x1024-ff69b4.svg?style=plastic)
![ ](https://img.shields.io/badge/Format-.png-ff69b4.svg?style=plastic)
![ ](https://img.shields.io/badge/Descriptions-760x9-blue.svg?style=plastic)
![ ](https://img.shields.io/badge/Format-.txt-blue.svg?style=plastic)

Facial Attribute Textual Descriptions 📃 for  Flickr-Faces-HQ Dataset (FFHQ) 👸.
<div align="center"><img src=./Pic/Overview.png></div>

## 📚Text-to-Image Datasets
### Text-to-X Datasets
| Dataset | Public | Categories | Images (Resolution) | Annotations | Attributes| Other Details
| :--- |  :-: |  :--: | :----: |  :--: |  :----: | :----------
| [CUB-200-2011](http://www.vision.caltech.edu/visipedia/papers/CUB_200_2011.pdf) | √ | 200 |11,788 (Unfixed) |10 |Uncounted | BBox, Segmentation...
| [Oxford-102 Flowers](https://www.robots.ox.ac.uk/~vgg/publications/2008/Nilsback08/nilsback08.pdf) | √ | 102 |8,189 (Unfixed) |10 |Uncounted | -
| [MS-COCO]() | √ | 91 |120k (Unfixed) |5 |Uncounted | BBox, Segmentation...

### Text-to-Face Datasets
| Dataset | Public | Categories | Images (Resolution) | Annotations | Attributes| Other Details
| :--- |  :-: |  :--: | :----: |  :--: |  :----: | :----------
| [SCU-Text2face](https://arxiv.org/pdf/1904.05729.pdf) | × |1 (Mixed) |1,000 (256&times;256) |5 |Uncounted | -
| [Text2FaceGAN](https://ieeexplore.ieee.org/document/8919389) | ×| 1 (Mixed) |10,000 (178&times;218) |6 |40 | -
| [Faces a la Carte](https://ieeexplore.ieee.org/abstract/document/9423291) | ×| 1 (Mixed) |202,599 (178&times;218) |up to 10 |40 | -
| [Multi-Modal-CelebA-HQ](https://ieeexplore.ieee.org/document/9578577) | √ | 1 (Mixed) |30,000 (512&times;512) |10 |38 | Mask, Sketches
| [FFHQ-Text](https://dl.acm.org/doi/abs/10.1145/3474085.3481026) | √ | 1 (Female) |760 (1024&times;1024) |9 |162 | BBox


## 🍀 Overview

**FFHQ-Text** is a small-scale face image dataset with large-scale facial attributes, designed for text-to-face generation&manipulation, text-guided facial image manipulation, and other vision-related tasks.

This dataset is an extension of the [NVIDIA Flickr-Faces-HQ Dataset (FFHQ)](https://github.com/NVlabs/ffhq-dataset), which is the selected top **760 female FFHQ images** that only contain one complete human face. 

In this study, we explore terminology in the human facial to **manually annotate** the FFHQ-Text dataset, which is breakdown into the following **13 multi-valued facial element groups** from coarse to fine:
* Age (8 classes: 0-2, 4-6, 8-13, 15-20, 25-32, 38-43, 48-53, over 60) 
* Gender information (Girl👧 or Woman👩) 
* Head pose (front, left👈, right👉, up👆 or down👇)
* Eyebrows (9 patterns)
* Eyes👀 (18 patterns, 10 colors)
* Nose👃 (8 patterns)
* Mouth👄 (13 patterns)
* Ears👂 (5 patterns)
* Sink (8 patterns, 8 color scale)
* Face shape (7 patterns)
* Hairstyle (21 patterns, 18 colors)
* Accessory (7 patterns 🧢🧣🎓👑👒...)
* Glasses type (glasses👓 or sunglasses🕶)

## 🎁 Download

| Content | Size | Files | Format | Details
| :--- |  :----:  |  :----: | :----: | :----------
| FFHQ-Text | - | 1,524 | | Main Folder
| &boxvr;&nbsp; Image | 0.97 GB | 760 | PNG | Female images from FFHQ of size 1024&times;1024
| &boxvr;&nbsp; Text | 766 KB | 760 | TXT | 9 descriptions for each selected facial image in FFHQ
| &boxvr;&nbsp; Train | 12 KB | 1 | PKL | Filenames of training images
| &boxvr;&nbsp; Test| 6 KB | 1 | PKL | Filenames of testing images
| &boxvr;&nbsp; bounding_boxes| 21 KB | 1 | TXT | Determine the location and orientation of each face 
| &boxvr;&nbsp; images| 19 KB | 1 | TXT | Counts, paths and filenames of all facial images

*✒ Bounding boxes for each face were extracted using the [VGG Image Annotator (VIA)](https://www.robots.ox.ac.uk/~vgg/software/via/) platform.*

Please fill out the [FFHQ-Text Dataset Request Form](https://forms.gle/LDTURuZLyN5if3jN9).

If it is not convenient to access Google, please [contact me📧](mailto:zhou@i.ci.ritsumei.ac.jp) directly with your real name, institution, and institution/organization email address. We will send you an email with the FFHQ-Text dataset within one week. 

## 🎉 Awesome Repo

>This is a survey on Text-to-Image generation & manipulation and Other Related Works.
>[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=Yutong-Zhou-cv&repo=awesome-Text-to-Image&theme=swift)](https://github.com/Yutong-Zhou-cv/awesome-Text-to-Image)

I hope you can have a primary knowledge about this topic, or some information would be helpful to find some sparks in your research~

## 📚 Feedback

Please fill out the [FFHQ-Text Dataset Feedback Form](https://forms.gle/CmwdtNgrtc1QWyWNA).

I  would greatly value your thoughts, suggestions, concerns or problems.

## 📌License & Privacy

The dataset is made available under [Creative Commons BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/) by Ritsumeikan University. 
You can **use, redistribute, and adapt it for non-commercial purposes**, as long as you (a) give appropriate credit by **citing our paper**, (b) **indicate any changes** that you've made, and (c) distribute any derivative works **under the same license**.

The individual images were published in Flickr by their respective authors under either [Creative Commons BY 2.0](https://creativecommons.org/licenses/by/2.0/), [Creative Commons BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/), [Public Domain Mark 1.0](https://creativecommons.org/publicdomain/mark/1.0/), [Public Domain CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/), or [U.S. Government Works](http://www.usa.gov/copyright.shtml) license. All of these licenses allow **free use, redistribution, and adaptation for non-commercial purposes**. However, some of them require giving **appropriate credit** to the original author, as well as **indicating any changes** that were made to the images. The license and original author of each image are indicated in the metadata.

* [https://creativecommons.org/licenses/by/2.0/](https://creativecommons.org/licenses/by/2.0/)
* [https://creativecommons.org/licenses/by-nc/2.0/](https://creativecommons.org/licenses/by-nc/2.0/)
* [https://creativecommons.org/publicdomain/mark/1.0/](https://creativecommons.org/publicdomain/mark/1.0/)
* [https://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1.0/)
* [http://www.usa.gov/copyright.shtml](http://www.usa.gov/copyright.shtml)

The TXT metadata is made available under Creative Commons BY-NC-SA 4.0 license by NVIDIA Corporation.

For other instructions, please see the privacy section of the [original FFHQ dataset](https://github.com/NVlabs/ffhq-dataset) for more details.

**🎯 Terms of Use**

Use of the provided FFHQ-Text Dataset will be deemed and treated as the user agreeing to and accepting the following Terms of Use content:

* The user understands that the use of Dataset is restricted to research purposes only. Any commercial or for-profit purposes are prohibited.

* Use of the FFHQ-Text Dataset by the user for unauthorized distribution, direct sales, or commercial business is prohibited. The user is not granted any rights or license to use the images referenced in the Dataset for any purpose.

* While the contents are provided after thorough confirmation, the FFHQ-Text Dataset makes no warranties regarding the usefulness, accuracy, legality, morality, timeliness, and appropriateness of the information acquisition.


## ⭐Citation

#### <p align=center>“A picture🖼 is worth a thousand words📜~ ”</p>

If you find this dataset helpful for your research, please cite it as below:

```bibtex

@inproceedings{zhou2021generative,
  title={Generative Adversarial Network for Text-to-Face Synthesis and Manipulation with Pretrained BERT Model},
  author={Zhou, Yutong and Shimada, Nobutaka},
  booktitle={2021 16th IEEE International Conference on Automatic Face and Gesture Recognition (FG 2021)},
  year={2021}
}

@inproceedings{zhou2021generative,
  title={Generative Adversarial Network for Text-to-Face Synthesis and Manipulation},
  author={Zhou, Yutong},
  booktitle={Proceedings of the 29th ACM International Conference on Multimedia},
  pages={2940--2944},
  year={2021}
}

@inproceedings{karras2019style,
  title={A style-based generator architecture for generative adversarial networks},
  author={Karras, Tero and Laine, Samuli and Aila, Timo},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={4401--4410},
  year={2019}
}

```
