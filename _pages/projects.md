---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Computer Vision: Object Detection for Autonomous Driving
<div style="display:inline-block; border:2px; margin:10px;">
    <p>
        [<a href="https://github.com/Danaliu67/Computer-Vision-Object-Detection-for-Autonomous-Driving">github</a>]
        [<a href="https://zhuanlan.zhihu.com/p/640969983">document</a>]
    </p>
    <p style="float:left;margin-top:10px;">
        This project investigates techniques for improving the detection performance of an autonomous driving detection system. The study systematically adjusts training epochs, batch size, and input image size on the ResNet network and compares and explains these parameters. Results demonstrate that ResNet101 outperforms ResNet50 and increasing the image size can significantly improve mean average precision.Additionally, suitable batch sizes must be selected to balance time and performance, and a suitable number of epochs should be chosen based on practical situations to achieve optimal performance. <br/>
        The findings provide valuable guidance for the study and practice of autonomous driving, and suggest the need for further exploration of other factors that affect object detection performance to propose more efficient and accurate system design methods.
    </p>
    <div style="text-align:center;">
    <img src="https://github.com/Danaliu67/Computer-Vision-Object-Detection-for-Autonomous-Driving/raw/main/resources/figure7.png" width="400" alt="markdown" hspace="40px">
    </div>
    
</div>

## NLP: Machine Reading Comprehension
<div style="display:inline-block; border:2px; margin:10px;">
    <p>
        [<a href="https://github.com/Danaliu67/NLP-Machine-Reading-Comprehension">github</a>]
        [<a href="https://zhuanlan.zhihu.com/p/640977528">document</a>]
    </p>
    <p style="float:left;margin-top:10px;">
        In this experiment, we aimed to optimize the performance of a reading comprehension model using different pre-trained architectures, hyperparameters, and optimization strategies. We experimented with BERT and ALBERT models of various scales and adjusted hyperparameters, such as learning rate, batch size, and max sequence length. Moreover, we employed optimization strategies like Adam optimizer with weight decay, warmup, and learning rate decay. <br/>
        The experimental results provided insights into the strengths and weaknesses of each model, allowing us to select the most suitable model for the reading comprehension task. Based on our experiments, the ALBERT-large model emerged as the best choice, with an "exact" score of 81.428 and an "F1" score of 84.860 on the evaluation set. Through these adjustments and optimization strategies, we achieved good model performance while maintaining stability and generalization during training.
    </p>
    
</div>
