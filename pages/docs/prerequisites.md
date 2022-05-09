---
layout: single
title:  "Prerequisites"
permalink: /docs/prerequisites
---

## Prerequisites
Please install dependencies shown below, according to your operating system.


Tested on Python 3.7 for model quantization -> pls use install the following
```
python3 -m pip install --upgrade pip3 wheel setuptools
python3 -m pip install --upgrade torch
```

For DSE, pls use the following instead
```
pip3 install torch==1.11.0+cpu torchvision==0.12.0+cpu -f https://download.pytorch.org/whl/torch_stable.html torchinfo tqdm pillow pandas numpy 
```
