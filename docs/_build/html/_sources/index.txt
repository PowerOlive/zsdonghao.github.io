Hi, I am Hao Dong
=======================================


.. image:: user/my_figs/img_tunelayer.png
  :scale: 25 %
  :align: center
  :target: https://github.com/zsdonghao/tunelayer


大家好，这个文档用来记录

`TuneLayer`_

The `home page <https://zsdonghao.github.io>`_
is not only for describing how to use `TuneLayer`_ but also
a tutorial to walk through different type of Neural Networks, Deep
Reinforcement Learning and Natural Language Processing etc.

However, different with other inflexible TensorFlow wrappers,
`TuneLayer`_ assumes that you are somewhat familiar with Neural Networks and TensorFlow.
A basic understanding of how TensorFlow works is required to be
able to use `TuneLayer`_ skillfully.


.. _TuneLayer-philosopy:

Philosophy
----------

`TuneLayer`_ grew out of a need to combine the flexibility of TensorFlow with the
availability of the right building blocks for training neural networks.
Its development is guided by a number of design goals:


* **Transparency**: Do not hide TensorFlow behind abstractions. Try to rely on
  TensorFlow's functionality where possible, and follow TensorFlow's conventions.
  Do not hide training process, all iteration, initialization can be managed
  by user.

* **Tensor**: Neural networks perform on multidimensional data arrays which are
  referred to as "tensors".

* **TPU**: Tensor Processing Unit is a custom ASIC built specifically for
  machine learning and tailored for TensorFlow.

* **Distribution**: Distributed Machine Learning is the default function of TensorFlow.

* **Compatibility**: A network is abstracted to regularization, cost and outputs
  of each layer. Easy to work with other TensorFlow libraries.

* **Simplicity**: Be easy to use, easy to extend and modify, to facilitate use
  in Research and Engineering.

* **High-Speed**: The running speed under GPU support is the same with
  TensorFlow only. The simplicity do not sacrifice the performance.



.. note::
   If




User Guide
------------

The TuneLayer user guide explains how to install TensorFlow, CUDA and cuDNN,
how to build and train neural networks using TuneLayer, and how to contribute
to the library as a developer.

.. toctree::
  :maxdepth: 2

  user/aboutme
  user/projects


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


.. _GitHub: https://github.com/zsdonghao/tunelayer
.. _TuneLayer: https://github.com/zsdonghao/tunelayer/
