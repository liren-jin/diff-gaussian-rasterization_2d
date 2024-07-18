# TODO
- add importance score for each 3D gaussian based on its contribution to rendering.
- add uncertainty rendering 
  
# Differential Gaussian Rasterization

This repo is largely based on the implementation of "High-quality Surface Reconstruction using Gaussian Surfels" and "3D Gaussian Splatting for Real-Time Rendering of Radiance Fields". We modify some part of the cuda kernels for our own project. 

```commandline
@inproceedings{Dai2024GaussianSurfels,
  author    = {Dai, Pinxuan and Xu, Jiamin and Xie, Wenxiang and Liu, Xinguo and Wang, Huamin and Xu, Weiwei},
  title     = {High-quality Surface Reconstruction using Gaussian Surfels},
  publisher = {Association for Computing Machinery},
  booktitle = {SIGGRAPH 2024 Conference Papers},
  year      = {2024}
}
```

```commandline
@article{kerbl3Dgaussians,
  author    = {Kerbl, Bernhard and Kopanas, Georgios and Leimk{\"u}hler, Thomas and Drettakis, George},
  title     = {3D Gaussian Splatting for Real-Time Radiance Field Rendering},
  journal   = {ACM Transactions on Graphics},
  number    = {4},
  volume    = {42},
  month     = {July},
  year      = {2023},
  url       = {https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/}
}
```
