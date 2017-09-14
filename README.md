# A2RL

[[Project]](https://debangli.github.io/A2RL/)   [[Paper]]() [[Code]](https://github.com/wuhuikai/TF-A2RL)  [[Online Demo]](https://wuhuikai.github.io/TF-A2RL/)    [[API]](https://algorithmia.com/algorithms/wuhuikai/A2RL)   [[Related Work: GP-GAN (for Image Blending)]](https://github.com/wuhuikai/GP-GAN)


## Overview

| source | step 1 | step 2 | step 3 | step 4 | step 5 | output| 
| --- | --- | --- | --- | --- | --- | --- |
| ![](images/readme/source.png) | ![](images/readme/step1.png) | ![](images/readme/step2.png) | ![](images/readme/step3.png) | ![](images/readme/step4.png) | ![](images/readme/step5.png) | ![](images/readme/output.png) |

A2-RL (aka. Aesthetics Aware Reinforcement Learning) is the author's implementation of the RL-based automatic image cropping algorithm described in:
```
A2-RL: Aesthetics Aware Reinforcement Learning for Automatic Image Cropping   
Debang Li, Huikai Wu, Junge Zhang, Kaiqi Huang
```

Given a source image, our algorithm could take actions step by step to find almost the best cropping window on source image. 

Contact: Debang Li (DerekLee9312@gmail.com)


## Results compared with baseline methods (more [results](https://debangli.github.io/A2RL/))

|Source| VFN+Sliding window | A2-RL | Ground Truth |
| --- | --- | --- |---|
| ![](images/readme/1227.jpg) | ![](images/readme/vfn_1227.jpg) | ![](images/readme/a2rl_1227.jpg) | ![](images/readme/gt_1227.jpg) |
| ![](images/readme/1644.jpg) | ![](images/readme/vfn_1644.png) | ![](images/readme/output.png) | ![](images/readme/gt_1644.jpg) |
| ![](images/readme/2747.jpg) | ![](images/readme/vfn_2747.jpg) | ![](images/readme/a2rl_2747.jpg) | ![](images/readme/gt_2747.jpg) |
| ![](images/readme/2903.jpg) | ![](images/readme/vfn_2903.jpg) | ![](images/readme/a2rl_2903.jpg) | ![](images/readme/gt_2903.jpg) |
| ![](images/readme/9036.jpg) | ![](images/readme/vfn_9036.jpg) | ![](images/readme/a2rl_9036.jpg) | ![](images/readme/gt_9036.jpg) |

```
@article{li2017a2,
  title={A2-RL: Aesthetics Aware Reinforcement Learning for Automatic Image Cropping},
  author={Debang Li, Wu, Huikai and and Zhang, Junge and Huang, Kaiqi},
  year={2017}
}
```
