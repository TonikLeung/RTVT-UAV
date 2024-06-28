# RTVT-UAV
Real-Time Visual Tracking Design for an Unmanned Aerial Vehicle in Cluttered Environments

# Introduction
Unmanned Aerial Vehicles (UAVs) and Unmanned Ground Vehicles (UGVs) are widely used in various fields, and autonomous tracking of UGV by UAV can significantly improve the collaborative capability and operational range of unmanned systems. In order to realize autonomous UAV tracking in complex and cluttered scenarios, this paper presents a vision-based tracking system for UAV tracking UGV, integrating a visual target tracking model based on deep learning with a local path planning methodology. The system includes a deep learning-based tracker, a state machine, and an obstacle avoidance planning algorithm. In addition, to improve the robustness of UAV onboard tracking, we introduce a lightweight tracking algorithm based on MobileNetV2 network, which ensures the tracking performance while improving the operation speed. Through real-world experiments, it is demonstrated that our system can realize autonomous target tracking in cluttered environments without prior information. The proposed tracker exhibits a success rate of 61.7\% on the UAV123 dataset and achieves a tracking speed of 45 frames per second (fps) on the NVIDIA Jetson TX2, demonstrating significant advancements in real-time, efficient unmanned tracking technologies.

# Experiments

Tracking static and moving targets in cluttered environment

![gif](./Experiments/Experiments%20Video.gif)
