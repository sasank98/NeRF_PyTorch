# NeRF (Neural Radiance Fields)

## Overview: 
<img src=data/nerf_render.gif height="300" width="300" > <p></p>
This is a simple implementation of Neural Radiance Fields. Given a pose and position, a reconstructed image is obtained. The neural network learns the parameters related to the 3D model of the object. 
<img src=data/pose.jpg height="300" width="340" > <p></p>
This is a representation of how the poses and point of views point towards the object in the dataset.

## Results:
<img src=data/output.jpg height="300" width="600" > <p></p>
Generated image (left), target image (middle) and PSNR vs. iterations graph spanning over 3000 iterations. The model is able to reach 25 PSNR (Peak Signal to Noise Ratio) after 3000 iterations, and is able to perfectly learn the parameters of the 3D model.


## References:
[1)](https://arxiv.org/abs/2210.00379) NeRF: Neural Radiance Field in 3D Vision, A Comprehensive Review, 2022
