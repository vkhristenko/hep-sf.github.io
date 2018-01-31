---
title: Distributed Deep Learning with Apache Spark using HEP Data
layout: gsoc_proposal
project: deepest
year: 2018
organization: CERN
---

# Description
Distributed Deep Learning is quickly becoming a standard way of performing training over large amounts of data. HEP Experiments produce PBs (soon to be EBs) of physics data, therefore, it is crucial to be able to efficiently perform deep learning model training. In this project, we aim to experiment and evaluate a set of DL frameworks running on top of general purpose processing engine [Apache Spark](https://spark.apache.org) by building several HEP specific workflows.

## Task ideas
  * Build a set of pipelines for HEP data processing with [Apache Spark employing](https://spark.apache.org) [spark-root](https://github.com/diana-hep/spark-root) as the Data Source.
  * Experiment with a set of Distributed Deep Learning Frameworks on top of Apache Spark engine
  * Build several HEP specific DL pipelines

## Expected results
  * Working pipelines across a set of DL Frameworks
  * Successful training/testing using CERN IT-DB infrastructure 

## Requirements
  * python/scala
  * Apache Spark
  * Familiarity with Machine Learning Algorithms/Frameworks

## Mentors
  * [Viktor Khristenko](mailto:viktor.khristenko.cern.ch)
  * [Luca Canali](mailto:Luca.Canali@cern.ch)
  * [Prasanth Kothuri](mailto:prasanth.kothuri@cern.ch)
  * [Maurizio Pierini](mailto:Maurizio.Pierini@cern.ch)

## Links
  * [spark-root](https://github.com/diana-hep/spark-root)
  * [BigDL](https://github.com/intel-analytics/BigDL)
  * [deeplearning4j](https://deeplearning4j.org)
  * [H2O](https://www.h2o.ai/sparkling-water/)
  * [MMLSpark](https://github.com/Azure/mmlspark)
  * [Elephas](http://maxpumperla.github.io/elephas/)
  * [Horovod](https://github.com/uber/horovod)
  * [TensorFlowOnSpark](https://github.com/yahoo/TensorFlowOnSpark)
