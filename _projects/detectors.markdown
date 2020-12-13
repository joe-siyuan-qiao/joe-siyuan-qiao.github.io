---
layout: page
title: DetectoRS
description: Detecting Objects with Recursive Feature Pyramid and Switchable Atrous Convolution
img: /assets/img/projects/detectors/minicover.png
importance: 1
---

Authors: __Siyuan Qiao__, Liang-Chieh Chen and Alan Yuille  
Affiliations: Johns Hopkins University and Google Research  
[\[Paper\]](https://arxiv.org/pdf/2006.02334.pdf) [\[GitHub\]](https://github.com/joe-siyuan-qiao/DetectoRS)

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/detectors-detecting-objects-with-recursive-1/instance-segmentation-on-coco)](https://paperswithcode.com/sota/instance-segmentation-on-coco?p=detectors-detecting-objects-with-recursive-1)  
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/detectors-detecting-objects-with-recursive-1/panoptic-segmentation-on-coco-test-dev)](https://paperswithcode.com/sota/panoptic-segmentation-on-coco-test-dev?p=detectors-detecting-objects-with-recursive-1)  
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/detectors-detecting-objects-with-recursive-1/object-detection-on-coco)](https://paperswithcode.com/sota/object-detection-on-coco?p=detectors-detecting-objects-with-recursive-1)


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/detectors/cover.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
Figure 1. (a) Our Recursive Feature Pyramid adds feedback connections (solid lines) from the top-down FPN layers to the
bottom-up backbone layers to look at the image twice or more. (b) Our Switchable Atrous Convolution looks twice at the
input features with different atrous rates and the outputs are combined together by switches.
</div>

### Abstract
Many modern object detectors demonstrate outstanding
performances by using the mechanism of looking and thinking twice. In this paper, we explore this mechanism in the
backbone design for object detection. At the macro level,
we propose Recursive Feature Pyramid, which incorporates
extra feedback connections from Feature Pyramid Networks
into the bottom-up backbone layers. At the micro level, we
propose Switchable Atrous Convolution, which convolves the
features with different atrous rates and gathers the results using switch functions. Combining them results in DetectoRS,
which significantly improves the performances of object detection. On COCO test-dev, DetectoRS achieves state-of-theart 55.7% box AP for object detection, 48.5% mask AP for
instance segmentation, and 50.0% PQ for panoptic segmentation.

### Citation
```BibTeX
@article{detectors,
  title={DetectoRS: Detecting Objects with Recursive Feature
         Pyramid and Switchable Atrous Convolution},
  author={Qiao, Siyuan and Chen, Liang-Chieh and Yuille, Alan},
  journal={arXiv preprint arXiv:2006.02334},
  year={2020}
}
```

