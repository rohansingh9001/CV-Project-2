# CV-Project-2
An repository for course project 2 for the course Computer Vision 2023 @ IIT Jodhpur: A Review on Semantic Segmentation

![Example Image](https://github.com/rohansingh9001/CV-Project-2/blob/main/sample.png?raw=true)

# A Review on Semantic Segmentation

This repository contains a detailed comparison of four recent papers in the field of semantic segmentation. The primary focus is on understanding the contributions of each paper and their implications in the advancement of semantic segmentation.
## Papers Analyzed

1. **SegNeXt** [1]: A convolutional network architecture that uses cheap convolutional operations to encode contextual information and achieves state-of-the-art performance on popular benchmarks, including ADE20K, Cityscapes, COCO-Stuff, Pascal VOC, Pascal Context, and iSAID.
2. **Token Contrast (ToCo)** [2]: A new approach that combines Class Activation Map (CAM) with Vision Transformer (ViT) for weakly-supervised semantic segmentation. ToCo addresses the over-smoothing issue in ViT by designing a Patch Token Contrast (PTC) module that supervises final patch tokens and a Class Token Contrast (CTC) module that facilitates representation consistency.
3. **Hierarchical Mutli-Scale Attention** [3]: A paper that tries to incorporate attention mechanisms and hierarchical learning into the process of semantic segmentation.
4. **Segformer** [4]: An end-to-end trainable network that capitalizes on multi-scale feature fusion, a technique that combines low-level detail information and high-level semantic information.

## References
```
[1] @misc{guo2022segnext,
      title={SegNeXt: Rethinking Convolutional Attention Design for Semantic Segmentation}, 
      author={Meng-Hao Guo and Cheng-Ze Lu and Qibin Hou and Zhengning Liu and Ming-Ming Cheng and Shi-Min Hu},
      year={2022},
      eprint={2209.08575},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

[2] (@misc{ru2023token,
      title={Token Contrast for Weakly-Supervised Semantic Segmentation}, 
      author={Lixiang Ru and Heliang Zheng and Yibing Zhan and Bo Du},
      year={2023},
      eprint={2303.01267},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

[3] @article{DBLP:journals/corr/abs-2005-10821,
  author       = {Andrew Tao and
                  Karan Sapra and
                  Bryan Catanzaro},
  title        = {Hierarchical Multi-Scale Attention for Semantic Segmentation},
  journal      = {CoRR},
  volume       = {abs/2005.10821},
  year         = {2020},
  url          = {https://arxiv.org/abs/2005.10821},
  eprinttype    = {arXiv},
  eprint       = {2005.10821},
  timestamp    = {Fri, 22 May 2020 16:21:29 +0200},
  biburl       = {https://dblp.org/rec/journals/corr/abs-2005-10821.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}

[4] @article{DBLP:journals/corr/abs-2105-15203,
  author       = {Enze Xie and
                  Wenhai Wang and
                  Zhiding Yu and
                  Anima Anandkumar and
                  Jose M. Alvarez and
                  Ping Luo},
  title        = {SegFormer: Simple and Efficient Design for Semantic Segmentation with
                  Transformers},
  journal      = {CoRR},
  volume       = {abs/2105.15203},
  year         = {2021},
  url          = {https://arxiv.org/abs/2105.15203},
  eprinttype    = {arXiv},
  eprint       = {2105.15203},
  timestamp    = {Wed, 02 Jun 2021 11:46:42 +0200},
  biburl       = {https://dblp.org/rec/journals/corr/abs-2105-15203.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```
