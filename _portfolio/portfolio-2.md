---
title: "Lightweight Super-Resolution of Satellite Imagery for Nitrogen Dioxide Prediction"
excerpt: "My masters thesis completed at University College Dublin. <br/><br/><img src='/images/sr1.png'>"
collection: portfolio
---

Nitrogen dioxide is a common air pollutant that can be difficult to track with traditional ground-based monitoring. While satellites can provide plentiful data and global coverage, such images are often captured at low resolutions that prohibit fine-grained predictions. In this work we investigate the application of super-resolution to the nitrogen dioxide prediction problem by super-resolving Sentinel-2 images with several popular models and our own lightweight architecture. Instead of collecting a second high-resolution dataset for ground-truths, we explore two methods for super-resolving images with a single dataset, thus assessing the viability of a greatly simplified super-resolution pipeline. Furthermore, we investigate the relationship between common superresolution metrics such as per-pixel error and perceptual quality with empirical performance on the downstream nitrogen dioxide prediction task. We find that our bespoke very small model, NinaCustom, outperforms popular deep models on common error benchmarks while offering inference time speedups of up to 50x. We observe that our approach has the potential to slot into the pre-processing steps of numerous computer vision tasks without adding a significant amount of computational overhead or requiring additional data collection while increasing downstream performance.

Check out the code base [here](http://github.com/zacharyyahn/Nitrogen-SR)
Download my paper [here](http://www.github.com/zacharyyahn/zacharyyahn.github.io/files/sr_paper.pdf)

System overview:
<img src='/images/sr2.png'>

Results show that our super resolution-enhanced data performed better on the nitrogen dioxide prediction task:
<img src='/images/sr3.png>

