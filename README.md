# VITON-HD - Official PyTorch Implementation

<p align="left"><img width="99%" src="assets/teaser.jpg" /></p>

This repository provides the official PyTorch implementation of the following paper:

> **VITON-HD: High-Resolution Virtual Try-On via Misalignment-Aware Normalization**<br>
> [Seunghwan Choi*](https://github.com/shadow2496)<sup>1</sup>, [Sunghyun Park*](https://psh01087.github.io/)<sup>1</sup>, [Minsoo Lee*](https://github.com/Minsoo2022)<sup>1</sup>, [Jaegul Choo](https://sites.google.com/site/jaegulchoo/)<sup>1</sup><br>
> <sup>1</sup>KAIST<br>
> In CVPR 2021. (* indicates equal contribution)<br>
> Paper : https://arxiv.org/abs/2103.16874<br>
> Project : https://psh01087.github.io/VITON-HD/<br>

> **Abstract**: *The task of image-based virtual try-on aims to transfer a target clothing item onto the corresponding region of a person, which is commonly tackled by fitting the item to the desired body part and fusing the warped item with the person. While an increasing number of studies have been conducted, the resolution of synthesized images is still limited to low (e.g., 256x192), which acts as the critical limitation against satisfying online consumers. We argue that the limitation stems from several challenges: as the resolution increases, the artifacts in the misaligned areas between the warped clothes and the desired clothing regions become noticeable in the final results; the architectures used in existing methods have low performance in generating high-quality body parts and maintaining the texture sharpness of the clothes. To address the challenges, we propose a novel virtual try-on method called VITON-HD that successfully synthesizes 1024x768 virtual try-on images. Specifically, we first prepare the segmentation map to guide our virtual try-on synthesis, and then roughly fit the target clothing item to a given person's body. Next, we propose ALIgnment-Aware Segment (ALIAS) normalization and ALIAS generator to handle the misaligned areas and preserve the details of 1024x768 inputs. Through rigorous comparison with existing methods, we demonstrate that VITON-HD highly surpasses the baselines in terms of synthesized image quality both qualitatively and quantitatively.*



## Installation
The code and usage examples will be updated soon. Please stay tuned.


## Citation
If you find this work useful for your research, please cite our [paper](https://arxiv.org/abs/2103.16874):

```
@article{choi2021viton,
  title={VITON-HD: High-Resolution Virtual Try-On via Misalignment-Aware Normalization},
  author={Seunghwan Choi and Sunghyun Park and Minsoo Lee and Jaegul Choo},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  year={2021}
}
```