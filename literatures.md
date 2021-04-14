## Unsupervised Learning

* CycleGAN: [paper](https://openaccess.thecvf.com/content_ICCV_2017/papers/Zhu_Unpaired_Image-To-Image_Translation_ICCV_2017_paper.pdf) [code](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)
  * net structure - Perceptual loss for style transfer: [paper](https://arxiv.org/pdf/1603.08155.pdf%7C)
  * GAN loss - LSGAN: [paper](https://openaccess.thecvf.com/content_ICCV_2017/papers/Mao_Least_Squares_Generative_ICCV_2017_paper.pdf)
  * update discriminator - SimGAN: [paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Shrivastava_Learning_From_Simulated_CVPR_2017_paper.pdf)
  * baseline - [CoGAN](https://arxiv.org/pdf/1606.07536.pdf), [SimGAN](https://openaccess.thecvf.com/content_cvpr_2017/papers/Shrivastava_Learning_From_Simulated_CVPR_2017_paper.pdf), [BiGAN](https://arxiv.org/pdf/1605.09782.pdf)/[ALI](https://arxiv.org/pdf/1606.00704.pdf), [pix2pix](https://openaccess.thecvf.com/content_cvpr_2017/papers/Isola_Image-To-Image_Translation_With_CVPR_2017_paper.pdf)
  * good for color & texture change, bad for geometrical change.
  * CycleGAN is a Master of Steganography? [paper](https://arxiv.org/pdf/1712.02950.pdf)
* Contrastive Unpaired Translation: [paper](https://arxiv.org/abs/2007.15651) [code](https://github.com/taesungp/contrastive-unpaired-translation)
* Geometry-Consistent GAN: [paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Fu_Geometry-Consistent_Generative_Adversarial_Networks_for_One-Sided_Unsupervised_Domain_Mapping_CVPR_2019_paper.pdf)


## Other Related 

* Adversarial Autoenoder: [paper](https://arxiv.org/abs/1511.05644)
* VAEGAN: [paper](http://proceedings.mlr.press/v48/larsen16.pdf)
* 

## Applications
* Cloud removal fusing sentinel-1/2 (CycleGAN): [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9211498) [dataset](https://mediatum.ub.tum.de/1554803)
  * Cloud removal fusing sentinel-1/2 (EDSR+cloud loss): [paper](https://www.sciencedirect.com/science/article/pii/S0924271620301398)
