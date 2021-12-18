<div align="center">
    <img src="resources/logo.png" width="200"/>
</div>

## Introduction

Certrol is a tool-box for machine learning-based certifiable controller synthesis. Certrol currently supports the following algorithms:

1. [Learning the Control Contraction Metric](./ccm)
2. [Safe Control for Multi-agent Systems with Decentralized Control Barrier Functions](./macbf)
3. [Safe Control for Black-box Dynamical Systems with Control Barrier Functions](./sablas)
4. [Safe Nonlinear Control Using Robust Neural Lyapunov-Barrier Functions](./neural_clbf)


## Citation

If you find this project useful in your research, please consider cite:

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

@article{dawson2021safe,
  title={Safe Nonlinear Control Using Robust Neural Lyapunov-Barrier Functions},
  author={Charles Dawson, Zengyi Qin, Sicun Gao, Chuchu Fan},
  journal={5th Annual Conference on Robot Learning},
  year={2021}
}
```