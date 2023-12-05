# BiSTNet: Semantic Image Prior Guided Bidirectional Temporal Feature Fusion for Deep Exemplar-based Video Colorization

### [Project Page](https://yyang181.github.io/BiSTNet/) | [Paper (ArXiv)](https://arxiv.org/abs/2212.02268) | [Supplemental Material](https://arxiv.org/abs/2212.02268) | [Code (Github)](https://github.com/yyang181/NTIRE23-VIDEO-COLORIZATION) 

[![google colab logo](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1T7-BOpSkd41fNW8bffo6aXSeK_jizsvv#scrollTo=P2UZcCEXmtb_) [![OpenXLab](https://camo.githubusercontent.com/ac2c2020b7679b75220d708037e0df9018615264f199d941f01d28795d31968b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f44656d6f2d2546302539462539302542432532304f70656e584c61622d626c7565)](https://openxlab.org.cn/apps/detail/yyang181/BiSTNet) ![visitors](https://visitor-badge.laobi.icu/badge?page_id=yyang181/BiSTNet)[![GitHub Stars](https://img.shields.io/github/stars/yyang181/BiSTNet?style=social)](https://github.com/yyang181/BiSTNet)

**This repository is the official pytorch implementation of our paper, *BiSTNet: Semantic Image Prior Guided Bidirectional Temporal Feature Fusion for Deep Exemplar-based Video Colorization*.**

[Yixin Yang](https://imag-njust.net/)<sup>1</sup>,
[Zhongzheng Peng](https://imag-njust.net/)<sup>1</sup>,
[Xiaoyu Du](https://imag-njust.net/xiaoyu-du/)<sup>1</sup>,
[Zhulin Tao](https://ices.cuc.edu.cn/2022/1028/c5332a200498/page.htm)<sup>2</sup>,
[Jinhui Tang](https://imag-njust.net/jinhui-tang/)<sup>1</sup>,
[Jinshan Pan](https://jspan.github.io/)<sup>1</sup> <br>

<sup>1</sup>Nanjing University of Science and Technology, <sup>2</sup>Communication University of China

## 🔥 News

- [2023-12-05] Integrated to 🐼 [OpenXLab](https://openxlab.org.cn/apps). Try out online demo! [![OpenXLab](https://camo.githubusercontent.com/ac2c2020b7679b75220d708037e0df9018615264f199d941f01d28795d31968b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f44656d6f2d2546302539462539302542432532304f70656e584c61622d626c7565)](https://openxlab.org.cn/apps/detail/yyang181/BiSTNet).
- [2023-12-05] Add inference code using two reference images, see [test_BiSTNet.py](https://github.com/yyang181/NTIRE23-VIDEO-COLORIZATION/blob/main/BiSTNet-NTIRE2023/test_BiSTNet.py).  
- [2023-12-02] Colab demo for BiSTNet is available [![google colab logo](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1T7-BOpSkd41fNW8bffo6aXSeK_jizsvv#scrollTo=OVMNWEaz2b06).

## **🔥 NTIRE2023 Video Colorization Challenge Champion 🏆**

We are excited to announce that our method based on BiSTNet won 1st place in the [NTIRE2023 Video Colorization Challenge](https://tianchi.aliyun.com/competition/entrance/532054/rankingList/) Track 1, Fréchet Inception Distance (FID) Optimization! You can find our code and the pre-trained weights in the following links:

- [Colorization results](https://drive.google.com/drive/folders/1jwVKK2IfAp01C6KpuqB3Wcm0uT4yXZBB?usp=share_link)
- [Testing code](https://github.com/yyang181/NTIRE23-VIDEO-COLORIZATION)
- [Pre-trained models](https://github.com/yyang181/NTIRE23-VIDEO-COLORIZATION)

## Framework
<img src='docs/media/pipeline.jpg'/>

## Input Videos (left column) and Colorized Videos (right column)

![](./docs/media/fanghua292.gif)

![](./docs/media/fanghua301.gif)

![](./docs/media/fanghua302.gif)

### To Do
- [ ] Release training code
- [x] Release testing code
- [x] Release pre-trained models

### Citation

If this work is helpful for your research, please consider citing the following entry.

```
@article{bistnet,
  title={BiSTNet: Semantic Image Prior Guided Bidirectional Temporal Feature Fusion for Deep Exemplar-based Video Colorization},
  author={Yang, Yixin and Peng, Zhongzheng and Du, Xiaoyu and Tao, Zhulin and Tang, Jinhui and Pan, Jinshan},
  journal={arXiv preprint arXiv:2212.02268},
  year={2022}
}
```

### Contact

This repo is currently maintained by Yixin Yang ([@yyang181](https://github.com/yyang181)) and is for academic research use only. 

