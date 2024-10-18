## [Match me if you can: Semi-Supervised Semantic Correspondence Learning with Unpaired Images](https://arxiv.org/abs/2311.18540)

> [Jiwon Kim<sup>1,2*](https://scholar.google.com/citations?user=Ozezv6kAAAAJ&hl=ko), [Byeongho Heo<sup>1](https://sites.google.com/view/byeongho-heo/home), [Sangdoo Yun<sup>1](https://sangdooyun.github.io/), [Seungryong Kim<sup>3](https://cvlab.kaist.ac.kr/members), [Dongyoon Han<sup>1</sup>&dagger;](https://dongyoonhan.github.io/),  <br>
> <sup> * Work done during an internship at NAVER AI Lab, currently at LG AI Research <br>
> &dagger; Corresponding author </sup> <br>
> <sup>1</sup>[NAVER AI LAB](https://naver-career.gitbook.io/en/teams/clova-cic/ai-lab), <sup>2</sup>[LG AI Research](https://www.sogang.ac.kr/ko/home), <sup>3</sup> [KAIST](https://cvlab.kaist.ac.kr/)

[![paper](https://img.shields.io/badge/arXiv-Paper-red.svg)](https://arxiv.org/abs/2311.18540)

### Abstract
> Semantic correspondence methods have advanced to obtaining high-quality correspondences employing complicated networks, aiming to maximize the model capacity. However, despite the performance improvements, they may remain constrained by the scarcity of training keypoint pairs, a consequence of the limited training images and the sparsity of keypoints. This paper builds on the hypothesis that there is an inherent data-hungry matter in learning semantic correspondences and uncovers the models can be more trained by employing densified training pairs. We demonstrate a simple machine annotator reliably enriches paired key points via machine supervision, requiring neither extra labeled key points nor trainable modules from unlabeled images. Consequently, our models surpass current state-of-the-art models on semantic correspondence learning benchmarks like SPair-71k, PF-PASCAL, and PF-WILLOW and enjoy further robustness on corruption benchmarks.


### Our Motivation: 
Current semantic correspondence learning suffers from **data hunger** during training:
- (a) Labeled images in SPair-71k contain sparse manually annotated keypoint pairs 
- (b) Unlabeled images could be hidden supplementary sources to increase the pairs' density.
- (c) Newly expanded image pairs can provide abundant densified pairs to alleviate the data-hungry matter.

  <img width="600" alt="image" src="https://github.com/user-attachments/assets/d179e8b4-320e-41bf-adba-3a4b8cd483ba">


### New Benchmark
#### Visualization of corrupted images in SPair-C
<img width="879" alt="image" src="https://github.com/user-attachments/assets/18775a38-a8a5-4a63-9670-2e20705f53d8">

#### Corrupted images with different severities
<img width="879" alt="image" src="https://github.com/user-attachments/assets/bf237470-e8e4-4ad7-868e-131d779ae00a">

- [Download Spair-C](https://drive.google.com/file/d/1ZY9bp5TEgtWDmOBfpipf4Hxy7RuxD_X2/view?usp=drive_link)

### Updates
* (2024/10/11): Code is under internal review.
* (2024/09/20): Our paper has been accepted at ACCV 2024🎉🎉🎉
