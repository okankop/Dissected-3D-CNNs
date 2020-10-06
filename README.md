Pytorch implementation of the article "[Dissected 3D CNNs: Temporal Skip Connections for Efficient Online Video Processing](https://arxiv.org/pdf/2009.14639.pdf)".

# Dissected-3D-CNNs

<p align="center"><img src="https://github.com/okankop/Dissected-3D-CNNs/blob/master/visual/spatial_temporal_sk.png" align="middle" width="550" title="temporal skip connections" /><figcaption>Fig. 1:  Comparison of spatial skip connections (a) first proposed in ResNets and temporal skip connections (b) proposed in this work. At every iteration, only the computations for the most recent frame performed. Afterwards, intermediate volumes from the skip connections are updated to be used for the next iteration. This way, recomputation of previous frames is saved. Skip connections are denoted with red lines. 
 </figcaption></figure></p>


# Animation of Inference

<p align="center"><img src="https://github.com/okankop/Dissected-3D-CNNs/blob/master/visual/D3D_animation.gif" align="middle" width="350" title="animation of inference" /></figure></p>


## The code will be uploaded soon!

## Citation

Please cite the following article if you use this code or pre-trained models:

```bibtex
@article{kopuklu2020dissected,
  title={Dissected 3D CNNs: Temporal Skip Connections for Efficient Online Video Processing},
  author={K{\"o}p{\"u}kl{\"u}, Okan and H{\"o}rmann, Stefan and Herzog, Fabian and Cevikalp, Hakan and Rigoll, Gerhard},
  journal={arXiv preprint arXiv:2009.14639},
  year={2020}
}
```
