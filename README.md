# Residual-Saliency-with-Python

##### The ability of human visual system to detect visualsaliency is extraordinarily fast and reliable. However, computational modeling of this basic intelligent behavior still remains a challenge. Here is a simple method for the visual saliency detection. This model is independent of features, categories, or other forms of prior knowledge of the objects. By analyzing the log-spectrum of an input image, we extract the spectral residual of an image in spectral domain, and propose a fast method to construct the corresponding saliency map in spatial domain. This method was proposed in 2007 in the article cited below.

##### In the following, we test this method on natural images and explore applying it to rule of thirds compliance in photographies.

##### The rule of thirds is a "rule of thumb" for composing visual images such as designs, films, paintings, and photographs. The guideline proposes that an image should be imagined as divided into nine equal parts by two equally spaced horizontal lines and two equally spaced vertical lines, and that important compositional elements should be placed along these lines or their intersections. Proponentsof the technique claim that aligning a subject with these points creates more tension, energy and interest in the composition than simply centering the subject. (Wikipedia)


#### Here is an example of great rule of thirds use in this picture (Source: Wikipédia -https://en.wikipedia.org/wiki/Rule_of_thirds)
![rule%20of%20thirds.gif](attachment:rule%20of%20thirds.gif)

### Dependency
- OpenCV

### Reference
```
@inproceedings{
title = {Saliency Detection: A Spectral Residual Approach},
author = {Xiaodi Hou, Liqing Zhang},
booktitle={Conference on Computer Vision and Pattern Recognition (CVPR)},
year = {2007}}
```
Find the paper at www.houxiaodi.com/assets/papers/cvpr07.pdf

