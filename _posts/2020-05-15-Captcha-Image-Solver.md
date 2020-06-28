---
title: "Machine Learning: Captcha Image Solver"
date: 2020-05-15
tags: [machine learning, image classification]
excerpt: "Machine Learning, Image Classification"
toc: true
toc_label: Captcha
---

To check out the project, take a look at the [repo](https://github.com/evanaze/captcha).

## Background

I was browsing Reddit one day, and came across a post on the subreddit [r/MachineLearning](https://www.reddit.com/r/MachineLearning/), where somebody was asking for help to solve Captcha images, like the one here:

{% include figure image_path="/assets/images/captcha_sample.png" type="center"%}

The captchas are a noisy image with verical lines on a colorful background, with between 1 and 9 squares added on top of a different pattern. I was immediately intrigued and knew that this is an interesting application of Machine Learning, and agreed to work on the project.  
He started by sending me 88 unlabeled captchas, just like the one above. My initial method was to use a [MNIST example](https://github.com/pytorch/examples/tree/master/mnist) repo in Pytorch. That did not go so well. First, I am embarrassed to say that I had data leakage and thought I had solved the problem by achieving 100% accuracy. When I removed the data leakage, I was down to just about random chance.

## Methods
### Method 1: OpenCV