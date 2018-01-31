---
title: Distributed Deep Learning with Apache Spark using HEP Data
layout: gsoc_proposal
project: SparkDL
year: 2018
organization: CERN
---

# Description
Distributed Deep Learning is quickly becoming a standard way of performing training over large amounts of data. High energy physics (HEP) experiments produce hundreds of petabytes (soon to be EBs) of physics data. In addition, Physicists are increasingly utilizing techniques and tools for machine learning, deep learning and big data processing in their data analysis pipelines. Some of the key points to be successful in this domain are the possibility of efficiently perform deep learning at scale and the integration with the existing data platforms and ecosystem of tools and frameworks for analysis. In this project, we aim to experiment and evaluate a set of DL frameworks running on top of the general-purpose processing engine [Apache Spark](https://spark.apache.org) by building several HEP-specific workflows.

## Task ideas
  * Build a set of pipelines for HEP data processing with [Apache Spark employing](https://spark.apache.org) [spark-root](https://github.com/diana-hep/spark-root) as the Data Source.
  * Experiment with a set of Distributed Deep Learning Frameworks on top of the Apache Spark engine
  * Build several HEP-specific DL pipelines
  * Customize/integrate the tools for training and testing with the infrastructure at CERN IT 

## Expected results
  * Produce working pipelines across a set of DL frameworks and data sets
     * using test and benchmark data to evaluate techniques and tools
     * produce demonstrators using selected HEP-data and use cases
  * Produce performance and scalability studies of the tested solutions

## Requirements
  * Python/Scala
  * Apache Spark
  * Machine Learning algorithms and frameworks

## Mentors
  * [Viktor Khristenko](mailto:viktor.khristenko.cern.ch)
  * [Luca Canali](mailto:Luca.Canali@cern.ch)
  * [Prasanth Kothuri](mailto:prasanth.kothuri@cern.ch)
  * [Vaggelis Motesnitsalis] (mailto:vaggelis.motesnitsalis@cern.ch)
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
  * [Distributed Keras](https://github.com/cerndb/dist-keras)
