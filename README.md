<p align="center">
  <h1 align="center">GARAD-SLAM: 3D GAussian splatting for Real-time Anti Dynamic SLAM</h1>
  <h3 align="center">ICRA 2025</h3>
    <p align="center"><sup>†</sup>Mingrui Li<sup>1</sup>, <sup>†</sup>Weijian Chen<sup>2</sup>, Na Cheng<sup>1</sup>, Jingyuan Xu<sup>1</sup>, Dong Li<sup>3</sup> and Hongyu Wang<sup>1∗</sup></p>
    <h3 align="center"><a href="https://doi.org/10.48550/arXiv.2502.03228">Paper</a> | <a href="https://github.com/user-attachments/assets/6da74298-b9d3-41cd-837d-b16a62b8e716">Video</a> </h3>
    <video src="https://github.com/user-attachments/assets/6da74298-b9d3-41cd-837d-b16a62b8e716" width="100%" controls autoplay > </video>
</p>




## Abstract
GARAD-SLAM is a real-time 3DGS-based SLAM system tailored for dynamic scenes. It directly performs dynamic segmentation on Gaussians and map them back to the front-end to obtain dynamic point labels through a Gaussian pyramid network, achieving precise dynamic removal and robust tracking. It imposes rendering penalties on dynamically labeled Gaussians updated through the network to avoid irreversible erroneous removal caused by simple pruning. We utilize [TUM RGB-D](https://cvg.cit.tum.de/data/datasets/rgbd-dataset) and [BONN RGB-D](https://www.ipb.uni-bonn.de/data/rgbd-dynamic-dataset/index.html) datasets to evaluate the performance of our algorithm.

<img width="1953" height="789" alt="image" src="https://github.com/user-attachments/assets/63ed9ed4-887f-4db8-8d2e-5ac682f76760" />


## Usage

_**Source code will be released soon.**_

<!-- ## Acknowledgement -->

## License
GARAD-SLAM is released under the [GNU General Public License v3.0](LICENSE).

## Citation

If you find our work useful, please kindly cite us:

```bibtex
@misc{li2025garadslam3dgaussiansplatting,
      title={GARAD-SLAM: 3D GAussian splatting for Real-time Anti Dynamic SLAM}, 
      author={Mingrui Li and Weijian Chen and Na Cheng and Jingyuan Xu and Dong Li and Hongyu Wang},
      year={2025},
      eprint={2502.03228},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2502.03228}, 
}
```
 
