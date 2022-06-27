```diff
+ this will be highlighted in green
- this will be highlighted in red

# AMSGradP
This is AMSGradP (Backpropagation Algorithm) implementation of pytorch version of  [Fault diagnosis for small samples based on attention mechanism
](https://www.sciencedirect.com/science/article/pii/S0263224121011507)

**However, in fact, the title [Fault diagnosis for small samples based on interpretable improved space-channel attention mechanism and improved regularization algorithms](https://www.sciencedirect.com/science/article/pii/S0263224121011507) fits the research content of the paper better.**

Imporved [AdamP](https://openreview.net/forum?id=Iz3zU3M316D) called  [AMSGradP](https://www.sciencedirect.com/science/article/pii/S0263224121011507) is suitable for intelligent fault diagnosis.

In this study, it is easy for small samples to converge to the local optimum. Unfortunately, the author has not given the improvement of more advanced AMSGrad. Inspired by this, the idea of Ref. [34] are introduced into AMSGrad called AMSGradP. In Appendix, Algorithm 1 outlines the pseudocode of AMSGradP.

![image](https://user-images.githubusercontent.com/19371493/144706901-ce59398c-3b9d-4aee-b65e-69e94b0d6328.png)

# If this project helps you, welcome to cite it:
```html
@article{ZHANG2022110242,  
title = {Fault diagnosis for small samples based on attention mechanism},  
journal = {Measurement},  
volume = {187},  
pages = {110242},  
year = {2022},  
issn = {0263-2241},  
doi = {https://doi.org/10.1016/j.measurement.2021.110242 },  
url = {https://www.sciencedirect.com/science/article/pii/S0263224121011507},  
author = {Xin Zhang and Chao He and Yanping Lu and Biao Chen and Le Zhu and Li Zhang}  
}
```
![image](https://user-images.githubusercontent.com/19371493/144707296-2731c87b-8469-4e2e-b0da-fa5edaca72be.png)

# Reference

```html
@inproceedings{DBLP:conf/iclr/HeoCOHYKUH21,
  author    = {Byeongho Heo and
               Sanghyuk Chun and
               Seong Joon Oh and
               Dongyoon Han and
               Sangdoo Yun and
               Gyuwan Kim and
               Youngjung Uh and
               Jung{-}Woo Ha},
  title     = {AdamP: Slowing Down the Slowdown for Momentum Optimizers on Scale-invariant
               Weights},
  booktitle = {9th International Conference on Learning Representations, {ICLR} 2021,
               Virtual Event, Austria, May 3-7, 2021},
  publisher = {OpenReview.net},
  year      = {2021},
  url       = {https://openreview.net/forum?id=Iz3zU3M316D},
  timestamp = {Mon, 28 Jun 2021 09:04:00 +0200},
  biburl    = {https://dblp.org/rec/conf/iclr/HeoCOHYKUH21.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```

