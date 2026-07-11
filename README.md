<div align="center">

# 2X7V14N.exe 正在加载中...🤡 
机器人感知学习器 | OpenCV C++ | ROS2 | 2D/3D视觉

<img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" width="250" />

<br>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Comic+Sans+MS&pause=1000&color=FF5733&center=true&vCenter=true&width=700&lines=正在让相机看懂世界;精通把+Warning+养成+Error;OpenCV+调参型选手;ROS2+节点施工中;Robot+Perception+Loading...)](https://git.io/typing-svg)

</div>

---

## 🧪 当前人设 / Current Build


我正在系统学习 **Robot Perception Algorithms / 机器人感知算法**。

当前主线是从传统 OpenCV 视觉出发，逐步升级到：

```text
OpenCV 2D Vision
-> Camera Calibration & Homography
-> ROS2 Perception Nodes
-> Robot Coordinate Frames & Hand-Eye Calibration
-> PCL Point Cloud Processing
-> PyTorch / YOLO Deep Vision
-> SLAM
```

---

## 🤹‍♂️ 核心技术栈 / Core Stack

<div align="center">
  <img src="https://img.shields.io/badge/C++17-正在驯服-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-视觉炼丹炉-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/CMake-构建法阵-064F8C?style=for-the-badge&logo=cmake&logoColor=white" />
  <img src="https://img.shields.io/badge/ROS2-Robot%20Comms-22314E?style=for-the-badge&logo=ros&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-Neural%20Summoning-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/PCL-Point%20Cloud%20Crew-2496ED?style=for-the-badge" />
</div>

<br>

<div align="center">
  <img src="https://img.shields.io/badge/Ctrl%20%2B%20C-谨慎使用-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Ctrl%20%2B%20V-带脑粘贴-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Stack_Overflow-急救箱-orange?style=for-the-badge&logo=stackoverflow" />
  <img src="https://img.shields.io/badge/Bug-越修越像特征-purple?style=for-the-badge" />
</div>

---

## 🚀 已通关玩具项目 / Cleared Toy Project

### OpenCV Grasp Pose Estimation

一个基于 **C++ + OpenCV** 的桌面物体抓取位姿估计项目。

它的主要职责是：

```text
Find target object from image
-> Estimate object center
-> Estimate grasp angle
-> Give robot a usable grasp hint
```

项目流水线 / Pipeline：

```text
Batch image loading
-> HSV Color Segmentation
-> Morphological Denoising
-> Contour Extraction
-> Largest Component Selection
-> minAreaRect Grasp Angle Estimation
-> Draw, Save, Pretend Everything Was Smooth
```

已经实现：

- ✅ 批量读取桌面图片 / Batch image processing
- ✅ HSV 颜色分割 / HSV color segmentation
- ✅ 形态学开闭运算去噪 / Morphological opening & closing
- ✅ 轮廓提取与最大目标筛选 / Contour extraction & largest target selection
- ✅ 最小外接矩形估计抓取角度 / Grasp angle estimation with rotated rectangle
- ✅ 结果图批量保存 / Result visualization and export
- ✅ CMake + 多文件模块化工程结构 / Modular C++ project with CMake

---

## 🧭 技能树升级路线 / Skill Tree

| 阶段 | 副本名称 / Quest | 解锁能力 / Unlock | 状态 |
|---|---|---|---|
| 1 | OpenCV Traditional Vision | 从图像里抠出目标 | ✅ 已通关 |
| 2 | Camera Calibration & Homography | 把像素坐标翻译成桌面真实坐标 | 🔜 当前主线 |
| 3 | ROS2 Basics | 让感知算法接入机器人系统 | ⏳ 排队中 |
| 4 | Robot Frames & Hand-Eye Calibration | 搞清相机、桌面、机械臂谁是谁 | ⏳ 排队中 |
| 5 | PCL Point Cloud | 从 2D 升级到 3D 感知 | ⏳ 排队中 |
| 6 | Deep Learning Vision | YOLO、Segmentation、ONNX Inference | ⏳ 排队中 |
| 7 | SLAM | 让机器人知道自己在哪 | ⏳ 排队中 |
| 8 | 待解锁 | 待解锁 | ⏳ 待解锁 |

---

## 📌 当前主线任务 / Current Quest

### Camera Calibration & Table Coordinate Mapping

当前项目已经能输出：

```text
Pixel center = (u, v)
Grasp angle = theta
```

下一步要升级成：

```text
Table position = (X mm, Y mm)
Robot usable pose = (X, Y, theta)
```

计划施工：

- Chessboard Camera Calibration / 棋盘格相机标定
- Lens Distortion Correction / 畸变校正
- Table Coordinate System / 桌面坐标系定义
- Homography Matrix / 单应性矩阵
- Pixel-to-Table Coordinate Mapping / 像素坐标到桌面坐标转换
- Integration with Grasp Pose Estimation / 接入当前抓取位姿估计项目

---

## 📈 摸鱼及机器人施工统计 / GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=2X7V14N&show_icons=true&theme=synthwave&hide_border=true&title_color=FF5733" width="48%" />
 
</div>
<!-- 综合数据统计卡片 -->
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=2X7V14N&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
</div>
---

<div align="center">
  <h3>🎉 恭喜你是第 <img src="https://profile-counter.glitch.me/2X7V14N/count.svg" /> 个闯入这个 Chaotic Lab 的人</h3>
---

## 🌱 Long-Term Goal / 长期目标

```text
Camera sees the object
-> Algorithm understands its pose
-> Robot receives usable coordinates
-> Robot plans the grasp
-> Robot picks up the object
-> I smile wisely
```

长期目标是建立一套完整的机器人感知基础，把 **Vision、Geometry、ROS2、3D Perception 和 Intelligent Grasping** 串成一条真正能工作的链路。
