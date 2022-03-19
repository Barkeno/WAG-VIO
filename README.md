# WAG-VIO
## Visual Odometry Tightly Coupled with Wheel Encoder and Gyroscope
#### we replace the accelerometer with a wheel encoder and present a method of using a low-cost camera and a gyroscope to estimate the robot's motion state. Compared with the traditional VIO system, the derivation of the motion state estimation proposed in this paper is more concise. Our algorithm based on the VINS-Mono has better real-time performance and is more suitable for embedded devices.

<p align='left'>
  <img src="./images/pic3.png" alt="drawing" height="320" width="600"/>
</p>

<!-- <p align='left'>
  <img src="./images/pic4.png" alt="drawing" height="280" width="600"/>
</p> -->


<!-- <p align='center'>
	<img src="./doc/seg_01.gif" alt="drawing" width="200"/>
	<img src="./doc/seg_02.gif" alt="drawing" width="200"/>
	<img src="./doc/lidar_odometry.gif" alt="drawing" width="200"/>
	<img src="./doc/mapping.gif" alt="drawing" width="200"/>
</p> -->

## Contributors

Jun Liu (Email: [1193868236@qq.com](1193868236@qq.com))

## BibTex Citation

Thank you for citing our T-LOAM paper on [IEEE](https://ieeexplore.ieee.org/document/9446309)if you use any of this code: 
@ARTICLE{9446309,
  author={Zhou, Pengwei and Guo, Xuexun and Pei, Xiaofei and Chen, Ci},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={T-LOAM: Truncated Least Squares LiDAR-Only Odometry and Mapping in Real Time}, 
  year={2021},
  volume={},
  number={},
  pages={1-13},
  doi={10.1109/TGRS.2021.3083606}
  }

## Credits

We hereby recommend reading [VINS-Mono](https://github.com/HKUST-Aerial-Robotics/VINS-Mono.git) for reference and thank them for making their work public.

## License

The source code is released under [GPLv3](http://www.gnu.org/licenses/) license.

I am constantly working on improving this code. For any technical issues or commercial use, please contact me(1193868236@qq.com).
