## RTVT-UAV
Real-Time Visual Tracking Design for an Unmanned Aerial Vehicle in Cluttered Environments

## Introduction
Unmanned Aerial Vehicles (UAVs) and Unmanned Ground Vehicles (UGVs) are widely used in various fields, and autonomous tracking of UGV by UAV can significantly improve the collaborative capability and operational range of unmanned systems. In order to realize autonomous UAV tracking in complex and cluttered scenarios, this paper presents a vision-based tracking system for UAV tracking UGV, integrating a visual target tracking model based on deep learning with a local path planning methodology. The system includes a deep learning-based tracker, a state machine, and an obstacle avoidance planning algorithm. In addition, to improve the robustness of UAV onboard tracking, we introduce a lightweight tracking algorithm based on MobileNetV2 network, which ensures the tracking performance while improving the operation speed. Through real-world experiments, it is demonstrated that our system can realize autonomous target tracking in cluttered environments without prior information. The proposed tracker exhibits a success rate of 61.7\% on the UAV123 dataset and achieves a tracking speed of 45 frames per second (fps) on the NVIDIA Jetson TX2, demonstrating significant advancements in real-time, efficient unmanned tracking technologies.

## System Architecture

### Hardware
![uav](./Experiments/Figures/Figure1.png)

### Software
![arch](./Experiments/Figures/Figure2.png)

## Experiments

Tracking static and moving targets in cluttered environment

![gif](./Experiments/Experiments%20Video.gif)

## Tracking Results

https://pan.baidu.com/s/1BE583uZnbRJqxfqqzPLO-g?pwd=6klz 

## Citation

If you find this repository useful for your work, please consider citing it as follows:


```
@article{liangreal,
  title={Real-time visual tracking design for an unmanned aerial vehicle in cluttered environments},
  author={Liang, Juntao and Yi, Peng and Li, Wei and Zuo, Jiaxuan and Zhu, Bo and Wang, Yong},
  journal={Optimal Control Applications and Methods},
  publisher={Wiley Online Library}
}
```

## License

MIT license