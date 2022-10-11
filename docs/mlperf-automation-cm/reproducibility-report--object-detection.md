# MLPerf automation and reproducibility report

**Tags:** MLPerf inference v2.1; Object Detection; Resnet50; ONNX 1.12.1; Ubuntu 22.04; x8664

[Back to MLPerf reproducibility studies](reproducibility.md)

## Current status

*[20221010] Python 3.9: Working.*

## Setup

* [System dependencies](../../cm/docs/installation.md#ubuntu--debian)
* [CK installation](../../cm/docs/installation.md#cm-installation)

## CM automation workflow

* [README](https://github.com/mlcommons/ck/tree/master/cm-mlops/script/app-mlperf-inference-reference#retinanet)

## Reusable CM components

* [Python](https://github.com/mlcommons/ck/tree/master/cm-mlops/script/get-python3)
* [Retinanet model (ONNX)](https://github.com/mlcommons/ck/tree/master/cm-mlops/script/get-ml-model-retinanet)
* [Openimages validation set](https://github.com/mlcommons/ck/tree/master/cm-mlops/script/get-dataset-openimages)
* [ONNX run-time](https://github.com/mlcommons/ck/tree/master/cm-mlops/script/get-onnxruntime)
* [MLPerf inference benchmark workflow with Python FE](https://github.com/mlcommons/ck/tree/master/cm-mlops/script/app-mlperf-inference-reference)

* [Other reusable CM components](https://github.com/mlcommons/ck/tree/master/cm-mlops/script)*

## Report problems

* [Open GitHub issue](https://github.com/mlcommons/ck/issues)
* [Discuss during weekly conf-calls](https://github.com/mlcommons/ck/blob/master/docs/mlperf-education-workgroup.md)