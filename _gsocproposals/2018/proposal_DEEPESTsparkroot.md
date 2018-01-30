---
title: spark-root: ROOT I/O for JVM/JS/Native
layout: gsoc_proposal
project: deepest
year: 2018
organization: CERN
---

# Description
HEP Experiments store PBs of physics data in [ROOT](http://root.cern.ch) File Format which is inaccessbile from Big Data solutions like [Apache Spark](https://spark.apache.org/).
[spark-root](https://github.com/diana-hep/spark-root) is a pure [scala](https://www.scala-lang.org/) implementation of the [ROOT](http://root.cern.ch) I/O that aims to bridge the gap and introduce HEP community to the general purpose processing engines like [Apache Spark](https://spark.apache.org/).
Recent development of [scala-js](https://www.scala-js.org/) and [scala-native](scala-native.org) would allow same Scala source for [ROOT](http://root.cern.ch) I/O be used for either running large scale data analysis on [JVM](https://java.com/en/download/), interacting with ROOT file contents in the browser using [scala-js](https://www.scala-js.org/) or running on a bare metal with [scala-native](scala-native.org)

## Task ideas
  * Refactor parts that are implemented in java
  * Factor out [Apache Spark](https://spark.apache.org/) related hooks into a separate package.
  * Build a core package, which is cross-compilable for JVM/JS/Native.
  * Add the ability to write ROOT files to disk.

## Expected results
  * A core package, which is cross-compilable and both Input/Output are working for the most common ROOT primitives.

## Requirements
  * Scala
  * git
  * Familiarity with c++, java

## Mentors
  * [Viktor Khristenko](mailto:viktor.khristenko.cern.ch)
  * [Luca Canali](mailto:Luca.Canali@cern.ch)

## Links
  * [Scala](https://www.scala-lang.org/)
  * [scala-js](https://www.scala-js.org/)
  * [scala-native](scala-native.org)
  * [spark-root](https://github.com/diana-hep/spark-root)
  * [ROOT](http://root.cern.ch)
