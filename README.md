<div align="center">

# 2X7V14N.exe 正在加载中... 🤖

**Robot Perception Learner | OpenCV C++ | ROS2 | 2D/3D Vision**

> 试图让相机看懂世界，让机器人别再闭眼抓空气。

[中文](#中文版本) | [English](#english-version)

</div>

---

# 中文版本

## 🧪 当前状态

我正在学习 **机器人感知算法**。

简单来说，我现在的主线是：

```text
让相机看见东西
-> 让程序知道那是个东西
-> 让程序知道东西在哪里
-> 让机器人知道该往哪伸手
-> 祈祷它不要把桌子当目标
```

目前我正从传统 OpenCV 视觉开始，一路往相机标定、ROS2、点云、深度学习视觉和 SLAM 推进。

---

## 🚀 当前代表项目

### OpenCV Grasp Pose Estimation

一个基于 C++ 和 OpenCV 的桌面物体抓取位姿估计项目。

它的核心任务是：

```text
从一张桌面照片里找出目标物体
然后算出：
1. 它在哪里
2. 它大概怎么歪着
3. 机器人应该用什么角度去抓它
```

项目流水线：

```text
批量读取图片
-> HSV 颜色分割
-> 形态学搓澡去噪
-> 轮廓提取
-> 找最大目标
-> minAreaRect 算抓取角
-> 画线、保存、收工
```

**它现在会：**

- 从桌面图片里识别目标区域
- 输出目标中心点
- 估计一个可用的抓取角度
- 批量处理图片
- 保存带可视化结果的图片
- 用 CMake 和模块化 C++ 组织代码，不再一坨糊在 `main.cpp` 里

---

## 🧭 技能树升级路线

| 阶段 | 技能点 | 学完以后能干嘛 | 状态 |
|---|---|---|---|
| 1 | OpenCV 传统视觉 | 让程序从图片里抠出目标 | ✅ 已通关 |
| 2 | 相机标定与 Homography | 把像素坐标翻译成桌面真实坐标 | 🔜 下一个副本 |
| 3 | ROS2 基础 | 让感知算法接入机器人通信系统 | ⏳ 排队中 |
| 4 | 机器人坐标系 | 搞懂相机坐标、桌面坐标、机械臂坐标谁是谁 | ⏳ 排队中 |
| 5 | PCL 点云 | 从 2D 图片升级到 3D 空间感知 | ⏳ 排队中 |
| 6 | 深度学习视觉 | YOLO、分割、ONNX，开始召唤神经网络 | ⏳ 排队中 |
| 7 | SLAM | 让机器人知道自己在哪，也知道世界长啥样 | ⏳ 终局副本 |

---

## 🛠️ 装备栏

<div align="center">

![C++](https://img.shields.io/badge/C++-17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-视觉炼丹炉-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-构建法阵-064F8C?style=flat-square&logo=cmake&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-机器人通信频道-22314E?style=flat-square&logo=ros&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-神经网络召唤术-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Python](https://img.shields.io/badge/Python-脚本魔法-3776AB?style=flat-square&logo=python&logoColor=white)

</div>

---

## 🧠 正在修炼

**计算机视觉方向**

- OpenCV C++ 图像处理
- HSV 颜色分割
- 形态学操作：开运算、闭运算，图像版“清洁工”
- 轮廓提取与几何特征
- 相机标定与畸变校正
- Homography 与透视变换

**机器人感知方向**

- 抓取位姿估计
- 像素坐标到真实世界坐标转换
- 机器人坐标系变换
- ROS2 感知节点
- RGB-D 与点云处理

**工程生存技能**

- C++17 项目开发
- CMake 构建系统
- 模块化代码组织
- OpenCV / Visual Studio / 链接器报错抢救
- 把踩过的坑写成笔记，避免以后再次掉进去

---

## 📌 下一个任务

### Camera Calibration & Table Coordinate Mapping

目标：把当前项目从：

```text
我知道目标在图片里的哪里
```

升级成：

```text
我知道目标在桌面真实世界里的哪里
```

计划实现：

- 用棋盘格做相机标定
- 去除镜头畸变
- 定义桌面坐标系
- 计算 Homography 单应性矩阵
- 把目标中心点从像素坐标转换成真实桌面坐标
- 接入当前抓取位姿项目

最终理想输出：

```text
Pixel: (320, 180)
World: (126.5 mm, 84.2 mm)
```

这一步做完，程序就不只是“看到了”，而是开始“看懂了”。

---

## 📚 我的学习方式

```text
先做一个能跑的小项目
-> 跑不动，开始报错
-> 查资料，怀疑人生
-> 修好，突然顿悟
-> 写笔记，假装一切都在计划中
-> 升级项目，进入下一轮循环
```

我相信机器人感知不是靠空想学会的，而是靠：

```text
真实图片 + 真实报错 + 真实项目 + 一点点头铁
```

---

## 📈 GitHub 数据

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=2X7V14N&show_icons=true&theme=tokyonight)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=2X7V14N&layout=compact&theme=tokyonight)

</div>

---

## 🌱 长期目标

```text
相机看见物体
-> 算法理解目标位姿
-> 机器人拿到可用坐标
-> 机械臂规划抓取
-> 成功拿起目标
-> 我露出智慧的微笑
```

长期目标是建立完整的机器人感知能力，把 **视觉、几何、ROS2、3D 感知和智能抓取** 串成一条真正能工作的链路。

---

# English Version

## 🧪 Current Status

I am learning **robotics perception algorithms**.

In simple words, I am trying to build this pipeline:

```text
Let the camera see objects
-> Let the program know they are objects
-> Let the program know where they are
-> Let the robot know where to move
-> Hope it does not grab the table
```

I am starting from traditional OpenCV vision and gradually moving toward camera calibration, ROS2, point clouds, deep learning vision, and SLAM.

---

## 🚀 Featured Project

### OpenCV Grasp Pose Estimation

A C++ OpenCV project for desktop object grasp pose estimation.

Its mission is simple:

```text
Find the target object from a desktop image
Then estimate:
1. Where it is
2. How it is rotated
3. How the robot should approach it
```

Pipeline:

```text
Batch image loading
-> HSV color segmentation
-> Morphological denoising
-> Contour extraction
-> Largest component selection
-> minAreaRect grasp angle estimation
-> Draw, save, done
```

**Current abilities:**

- Detects target regions from desktop images
- Estimates object center position
- Estimates a usable grasp angle
- Processes multiple images in batch
- Saves visualized result images
- Uses modular C++ and CMake instead of stuffing everything into `main.cpp`

---

## 🧭 Skill Tree

| Stage | Skill | What it unlocks | Status |
|---|---|---|---|
| 1 | OpenCV Traditional Vision | Extract objects from images | ✅ Cleared |
| 2 | Camera Calibration & Homography | Convert pixels to real table coordinates | 🔜 Next quest |
| 3 | ROS2 Basics | Connect perception algorithms to robot systems | ⏳ Queued |
| 4 | Robot Coordinate Systems | Understand camera, table, and robot frames | ⏳ Queued |
| 5 | PCL Point Cloud | Upgrade from 2D images to 3D perception | ⏳ Queued |
| 6 | Deep Learning Vision | YOLO, segmentation, ONNX, neural network magic | ⏳ Queued |
| 7 | SLAM | Help robots know where they are and map the world | ⏳ Final boss |

---

## 🛠️ Equipment

<div align="center">

![C++](https://img.shields.io/badge/C++-17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Vision%20Forge-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-Build%20Ritual-064F8C?style=flat-square&logo=cmake&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-Robot%20Comms-22314E?style=flat-square&logo=ros&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-Neural%20Summoning-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Python](https://img.shields.io/badge/Python-Scripting%20Magic-3776AB?style=flat-square&logo=python&logoColor=white)

</div>

---

## 🧠 Currently Training

**Computer Vision**

- OpenCV C++ image processing
- HSV color segmentation
- Morphological operations
- Contour detection and geometry features
- Camera calibration and distortion correction
- Homography and perspective transform

**Robotics Perception**

- Grasp pose estimation
- Pixel-to-world coordinate mapping
- Robot coordinate transformations
- ROS2 perception nodes
- RGB-D and point cloud processing

**Engineering Survival Skills**

- C++17 project development
- CMake build system
- Modular code organization
- Debugging OpenCV / Visual Studio / linker issues
- Turning painful bugs into structured notes

---

## 📌 Next Quest

### Camera Calibration & Table Coordinate Mapping

Goal: upgrade the current project from:

```text
I know where the object is in the image
```

to:

```text
I know where the object is on the real table
```

Planned steps:

- Calibrate camera with chessboard images
- Remove lens distortion
- Define table coordinate system
- Compute Homography matrix
- Convert object center from pixel coordinates to real table coordinates
- Integrate the mapping into the current grasp pose estimation project

Expected output:

```text
Pixel: (320, 180)
World: (126.5 mm, 84.2 mm)
```

After this step, the program is no longer just “seeing” objects. It starts to understand where they are.

---

## 📚 Study Loop

```text
Build a small project
-> It breaks
-> Debug and question reality
-> Fix it and suddenly understand
-> Write notes like it was planned all along
-> Upgrade the project and repeat
```

I believe robotics perception is best learned through:

```text
real images + real errors + real projects + stubborn curiosity
```

---

## 📈 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=2X7V14N&show_icons=true&theme=tokyonight)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=2X7V14N&layout=compact&theme=tokyonight)

</div>

---

## 🌱 Long-Term Goal

```text
Camera sees the object
-> Algorithm understands its pose
-> Robot receives usable coordinates
-> Robot plans the grasp
-> Robot picks up the object
-> I smile wisely
```

My long-term goal is to build a complete robotics perception foundation connecting **vision, geometry, ROS2, 3D perception, and intelligent grasping**.
