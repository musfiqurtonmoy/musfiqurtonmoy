## Md. Musfiqur Rahman

AI and robotics engineer. BSc Mechatronics Engineering, Rajshahi University of Engineering & Technology (RUET), Bangladesh.

I build perception and learning systems that have to work on real machines: computer vision, sensor fusion, deep learning, and the data and deployment work around them.

📫 musfiqurtonmoy@gmail.com

### Featured projects

**[steel-defect-inspection](https://github.com/musfiqurtonmoy/steel-defect-inspection)**: industrial surface inspection from raw images to a production API. Data-quality checks (caught a duplicate in the public NEU-CLS dataset), versioned SQL manifest, PyTorch training, ONNX export and a Dockerised FastAPI service. **100% test accuracy with a 6 MB MobileNetV3; ONNX Runtime 8.4× faster than PyTorch on CPU (1.2 ms per image).**
`PyTorch` `ONNX Runtime` `FastAPI` `SQLAlchemy` `Docker` `GitHub Actions`

**[ros2-vslam-sensor-fusion-varying-light](https://github.com/musfiqurtonmoy/ros2-vslam-sensor-fusion-varying-light)**: a Raspberry Pi 5 robot fusing camera, LiDAR, IMU and wheel encoders in ROS 2, with a visual confidence score that shifts trust from camera to LiDAR as light fails. **100% navigation success at 2.8 cm error in daylight; 80% at 6.2 cm in total darkness, where camera-only SLAM scored 0%.** Published in *Measurement*.
`ROS 2` `ORB-SLAM3` `Nav2` `Raspberry Pi 5`

### Research code

- **[malcert](https://github.com/musfiqurtonmoy/malcert)**: certified robustness of ML malware detectors in a constrained PE feature space. Measured feature changes under functionality-preserving edits, built a constrained threat model, and evaluated certified defences on BODMAS (MLP, LightGBM) with family-disjoint and temporal splits over 5 seeds. Manuscript.
- **[bus-aware-safe-locomotion](https://github.com/musfiqurtonmoy/bus-aware-safe-locomotion)**: safe learned legged locomotion under battery and DC-bus limits, with a barrier-based power filter. Manuscript in preparation.

### Publications

- **Rahman, M.M.**, Mahmud, J.A., Ali, M.F., Rahim, M.A., Sarker, S.K. & Yan, B. (2026). ROS2-based real-time autonomous mapping and navigation: Integrating visual SLAM and sensor fusion with performance analysis under varying light. *Measurement*, 268, 120695. [DOI](https://doi.org/10.1016/j.measurement.2026.120695) · [repo, video and results](https://github.com/musfiqurtonmoy/ros2-vslam-sensor-fusion-varying-light)
- **Rahman, M.M.**, Mahmud, J.A. & Ali, M.F. (2025). A review on detection of cyberattacks in industrial automation systems and its advancement through MPC-based AI. *Advanced Control for Applications: Engineering and Industrial Systems*, 7, e70003. [DOI](https://doi.org/10.1002/adc2.70003) · [repo](https://github.com/musfiqurtonmoy/ics-cyberattack-detection-mpc-ai-review)
- Rahim, M.A., Rahman, M.M., Islam, M.S., Joseph, C.I., Rahman, M.A., Ramasamy, D., **Rahman, M.M.** & Islam, M.Z. (2025). Attentive neural networks and meta-learning integration for revolutionary vehicular engine health monitoring. *Mechanical Systems and Signal Processing*, 238, 113141. [DOI](https://doi.org/10.1016/j.ymssp.2025.113141) · [repo](https://github.com/musfiqurtonmoy/engine-health-attentive-bigru-maml)
- Sheakh, M.H.R., **Rahman, M.M.** & Ali, M.F. (2026). Design and development of IoT based square-wave single-phase online inverter system with solar panel installation. *IEEE QPAIN 2026*. [IEEE Xplore](https://ieeexplore.ieee.org/document/11546107) · [repo and demo](https://github.com/musfiqurtonmoy/iot-solar-square-wave-inverter)
- In progress: culture-aware reinforcement learning for service-robot navigation in resource-constrained hospitals (first author).

Reviewer for Springer Nature journals including *Scientific Reports* and *Artificial Intelligence Review*.

### Robotics and vision projects

- **ROS2 visual SLAM navigation stack** (BSc thesis): real-time mapping and localisation with EKF multi-sensor fusion and an adaptive visual confidence score that re-weights sensors when image quality drops.
- **Safe reinforcement learning**: SAC policy with a control barrier function safety shield in Gazebo and ROS2.
- **Bipedal humanoid**: gait planning and balance control.
- **Gesture-controlled virtual mouse**: real-time hand tracking with OpenCV and ML.
- **Remote surveillance robot** with live video, **high-speed line follower** (PID, 3.5 m/s), **closed-loop DC motor speed control** (PWM, encoder).

### Tools

`Python` `C++` `PyTorch` `TensorFlow/Keras` `YOLO` `OpenCV` `PCL` `NumPy` `Pandas` `FastAPI` `SQL` `Docker` `Linux` `Git` `ROS/ROS2` `Gazebo` `RViz` `MATLAB/Simulink`
