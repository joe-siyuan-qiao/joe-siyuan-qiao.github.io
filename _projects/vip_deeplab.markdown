---
layout: page
title: ViP-DeepLab
description: Learning Visual Perception with Depth-aware Video Panoptic Segmentation
img: /assets/img/projects/vip_deeplab/minicover.png
importance: 2
---

Authors: __Siyuan Qiao__, Yukun Zhu, Hartwig Adam, Alan Yuille and Liang-Chieh Chen  
Affiliations: Johns Hopkins University and Google Research  
[\[Paper\]](https://arxiv.org/pdf/2012.05258.pdf) [\[GitHub\]](https://github.com/joe-siyuan-qiao/ViP-DeepLab) [\[YouTube\]](https://youtu.be/XR4HFiwwao0) 


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/vip_deeplab/ViP-DeepLab.gif' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
</div>

### Abstract
In this paper, we present ViP-DeepLab, a unified model attempting to tackle the long-standing and challenging inverse projection problem in vision, which we model as restoring the point clouds from perspective image sequences while providing each point with instance-level semantic interpretations. Solving this problem requires the vision models to predict the spatial location, semantic class, and temporally consistent instance label for each 3D point. ViP-DeepLab approaches it by jointly performing monocular depth estimation and video panoptic segmentation. We name this joint task as Depth-aware Video Panoptic Segmentation, and propose a new evaluation metric along with two derived datasets for it, which will be made available to the public. On the individual sub-tasks, ViP-DeepLab also achieves state-of-the-art results, outperforming previous methods by 5.1% VPQ on Cityscapes-VPS, ranking 1st on the KITTI monocular depth estimation benchmark, and 1st on KITTI MOTS pedestrian.

### Citation
```BibTeX
@article{vip_deeplab,
  title={ViP-DeepLab: Learning Visual Perception with Depth-aware
         Video Panoptic Segmentation},
  author={Siyuan Qiao and Yukun Zhu and Hartwig Adam and Alan Yuille and Liang-Chieh Chen},
  journal={arXiv preprint arXiv:2012.05258},
  year={2020}
}
```
