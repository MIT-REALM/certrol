<div align="center">
    <img src="resources/logo.png" width="200"/>
</div>

## Introduction

Certrol is a tool-box for machine learning-based certifiable controller synthesis. Certrol currently supports the following algorithms:

1. [Learning the Control Contraction Metric](https://github.com/MIT-REALM/ccm/tree/8377d469af09b39bd02fe3946f2085d7be63e45a)
2. [Safe Control for Multi-agent Systems with Decentralized Control Barrier Functions](https://github.com/MIT-REALM/macbf/tree/7e364b7a65801debaccc2f60673323385e6f05d3)
3. [Safe Control for Black-box Dynamical Systems with Control Barrier Functions](https://github.com/MIT-REALM/sablas/tree/2ba1c5c92bc18a1218140780f8f9e051f68f73ae)
4. [Safe Nonlinear Control Using Robust Neural Lyapunov-Barrier Functions](https://github.com/MIT-REALM/neural_clbf/tree/a39d3e2cfb9d9bf53ed000b36a30ae1965253dce)
5. [Compositional Neural Certificates for Networked Dynamical Systems](https://github.com/MIT-REALM/neuriss/tree/c1abebc2af38afdf9e58c8089de05217679b1703)

## Installation

Certrol relies on a number of submodules. To clone the Certrol repository and each submodule, run
```
git clone git@github.com:MIT-REALM/certrol.git
git submodule init
git submodule update
```

Then follow the installation instructions for each submodule you are interested in using.

## Licenses

Licenses for each submodule are maintained within each submodule. In summary:

1. `C3M` has a TODO license
2. `macbf` has a TODO license
3. `sablas` has a TODO license
4. `neural_clbf` has a 3-clause BSD license.
5. `neuriss` has a MIT license

## Citation

If you find this project useful in your research, please consider citing:

```bibtex
@article{sun2020learning,
  title = {Learning certified control using contraction metric},
  author = {Sun, Dawei and Jha, Susmit and Fan, Chuchu},
  booktitle = {Proceedings of the Conference on Robot Learning},
  year = {2020}
}

@article{qin2021learning,
  title={Learning Safe Multi-agent Control with Decentralized Neural Barrier Certificates },
  author={Qin, Zengyi and Zhang, Kaiqing and Chen, Yuxiao and Chen, Jingkai and Fan, Chuchu},
  booktitle={International Conference on Learning Representations},
  year={2021}
}

@ARTICLE{qin2021sablas,
  author={Qin, Zengyi and Sun, Dawei and Fan, Chuchu},
  journal={IEEE Robotics and Automation Letters},
  title={Sablas: Learning Safe Control for Black-Box Dynamical Systems},
  year={2022},
  volume={7},
  number={2},
  pages={1928-1935},
  doi={10.1109/LRA.2022.3142743}
}

@article{dawson2021safe,
  title={Safe Nonlinear Control Using Robust Neural Lyapunov-Barrier Functions},
  author={Charles Dawson, Zengyi Qin, Sicun Gao, Chuchu Fan},
  journal={5th Annual Conference on Robot Learning},
  year={2021}
}

@article{dawson2022perception,
  author={Dawson, Charles and Lowenkamp, Bethany and Goff, Dylan and Fan, Chuchu},
  journal={IEEE Robotics and Automation Letters},
  title={Learning Safe,
  Generalizable Perception-Based Hybrid Control With Certificates},
  year={2022},
  volume={7},
  number={2},
  pages={1904-1911},
  doi={10.1109/LRA.2022.3141657}
}

@inproceedings{zhang2023neuriss,
  title={Compositional Neural Certificates for Networked Dynamical Systems},
  author={Songyuan Zhang and Yumeng Xiu and Guannan Qu and Chuchu Fan},
  booktitle={5th Annual Learning for Dynamics {\&} Control Conference},
  year={2023},
}
```
