# LIME-in-DPU-platform

This repo explains how to use LIME as an interpreter for deep learning model inference on DPU

## Environment
---
We tested this repo using the following environment
|  |   |
| ------------ | ------------ |
| SOM  | ilinx Kria KV260  |
|   Vitis ai Version| 1.4  |

## Requirements
---
Please install the following dependency libraries before use
`pip install lime operncv-python`

## test
---
git clone repo and install Require library. You can download the test model from this [`download_model.md`](http://https://github.com/NTTUlab501/LIME-in-DPU-platform/blob/main/model/Download_model.md "`download_ model.md`"). After that, run the ipynb file 
[lime.ipynb](https://github.com/NTTUlab501/LIME-in-DPU-platform/blob/main/example/lime.ipynb "lime.ipynb") to test
