# CID-Net (Complex-valued Incection for Diverging-wave Network)
This repo provides CID-Net model with trained weights in [Open Neural Network Exchange (ONNX)](https://onnx.ai) format and a inference demo script, for the following paper:

[Complex Convolutional Neural Networks for Ultrafast Ultrasound Imaging Reconstruction from In-Phase/Quadrature Signal](https://ieeexplore.ieee.org/document/9614147)

## Repo Contents

- [model/](model/cid_net.onnx)cidnet.onnx: CID-Net ONNX model with trained weights
- [data/](data)
  - grid_x.h5: image grid in lateral direction
  - grid_z.h5: image grid in axial direction
  - data_gammex.h5: data example acquiered from phantom (Gammex, model 410SCG)
  - data_cirs.h5: data example acquiered from phantom (CIRS, model 054GS)

- [demo.ipynb](demo.ipynb): Running inference 


## Requirements
- [numpy](https://pypi.org/project/numpy/)
- [h5py](https://pypi.org/project/h5py/)
- [onnxruntime](https://pypi.org/project/onnxruntime/)
- [matplotlib](https://pypi.org/project/matplotlib/)

## Model inference with the image examples
Code pieces are provided in [jupyter](https://jupyter.org/install) notebook [demo.ipynb](demo.ipynb)

