---
title: AI-Powered Socioeconomic Prediction of Lifespan
author: 
    - Rustom Ichhaporia [`rustomi2@illinois.edu`][^*]
date: 2020-12-12
description: 
    Something something. 
geometry: margin=1in
# documentclass: article
classoption: 
- twocolumn
---

<!-- Document -->

## 

Last week, I registered for HAL access so that I could run the hyperparameter optimization script remotely because my computer overheated and could not run it for the appropriate number of trials. I was able to upload my files and run the first half of the script, but unfortunately when running the `fmin` optimization function, the program crashes after the first of 150 loops with the error: 

```
lightgbm.basic.LightGBMError: Cannot change 
bin_construct_sample_cnt after constructed 
Dataset handle.
```

[^1]

<!-- Footnotes -->

[^*]: This research project was completed during my time as a research intern at the [Illinois Risk Lab](https://irisklabuiuc.wixsite.com/) during the Fall of 2020. My research was a part of the AI-Powered Lifecycle Financial Planning project, which is still under development. I appreciate the help of Dr. Runhuan Feng, Dr. Frank Quan, Dr. Yong Xie, Dr. Linfeng Zhang, and my fellow interns throughout the process. Thank you!

[^1]: https://github.com/microsoft/LightGBM/issues/2696https://pandoc.org/MANUAL.html#templates