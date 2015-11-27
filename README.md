# TensorFlow Tutorial

[TOC]

## Introduction

- [https://linux.cn/article-6582-1.html](https://linux.cn/article-6582-1.html)
- [http://www.infoq.com/cn/news/2015/11/tensorflow-vs-dmtk-vs-systemml](http://www.infoq.com/cn/news/2015/11/tensorflow-vs-dmtk-vs-systemml)

## Environment Setup

### localhost

[binary install](https://github.com/tensorflow/tensorflow#binary-installation) instruction on tensorflow's github

### vagrant

[tensorflow-ipy](https://github.com/gavinln/tensorflow-ipy)

### docker

[docker image](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/tools/docker#running-the-container) from tensorflow's github

``` shell
docker run -it b.gcr.io/tensorflow/tensorflow
```

### testing

``` python
import tensorflow as tf

hello = tf.constant('Hello, TensorFlow!')
sess = tf.Session()
print sess.run(hello)
# Hello, TensorFlow!

a = tf.constant(10)
b = tf.constant(32)
print sess.run(a+b)
# 42
```

## External Links

- [stackoverflow tag:tensorflow](http://stackoverflow.com/questions/tagged/tensorflow)
- [Taipei.py - 花蓮魏老師](https://github.com/tjwei/tf-play)
- [examples](https://github.com/aymericdamien/TensorFlow-Examples)

## skflow

- [https://github.com/google/skflow](https://github.com/google/skflow)
- [tutorial](https://medium.com/@ilblackdragon/tensorflow-tutorial-part-1-c559c63c0cb1#.6ksf98ogh)