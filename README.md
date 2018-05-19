# QuadsManip

**Cooperative Manipulation using Multiple Quadrotors without Communication**

Click to watch demo video:

<a href="https://www.youtube.com/embed/MYOgharJuoY" target="_blank"><img src="https://img.youtube.com/vi/MYOgharJuoY/0.jpg" 
alt="cla" width="240" height="180" border="10" /></a>

This repository contains the simulation code of the following <a href="https://msl.stanford.edu/sites/default/files/wang.singh_.pavone.ea_.icra18.pdf" target="_blank">ICRA 18 paper</a>:

Z. Wang, S. Singh, M. Pavone, and M. Schwager, “Cooperative object transport in 3D with multiple quadrotors using no peer communication,” In Proc. International Conference on Robotics and Automation (ICRA), Brisbane, Australia, 2018


Code author: <a href="http://web.stanford.edu/~zjwang/" target="_blank">Zijian Wang</a>, Stanford University


## Quickstart and Demo

```
./make.sh
python demo_main.py
python demo_single_quad.py
python demo_traj_opt.py
python demo_traj_opt_time.py
```

The code has been tested in Mac OS 10.11 and Ubuntu 16.04.

This repo does not contain rviz visualization as used in the paper in order to minimize dependency and ease the use of the code. Instead, `matplotlib` is used for visualization.


## Python Dependencies
- **Python 2.7**

- numpy: v1.11.3

- matplotlib: v2.0.0

- (optional) cvxpy: v0.4.11


## Citation

If you find our work useful in your research, please consider citing:

    @inproceedings{WangEtAlICRA18MultiQuadManipulation,
    author = {Z. Wang and S. Singh and M. Pavone and M. Schwager}, 
    title = {Cooperative Object Transport in 3D with Multiple Quadrotors using No Peer Communication},
    booktitle = {Proc. of the International Conference on Robotics and Automation (ICRA)},
    year = {2018}
    }

## License

Our code is released under MIT License (see LICENSE file for details).

For any technical issues, please contact Zijian Wang <zjwang_AT_stanford_DOT_edu>, or open an issue in Github.
