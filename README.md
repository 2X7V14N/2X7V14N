<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=180&section=header&text=2X7V14N.exe%20Loading...&fontSize=42&fontAlignY=35&animation=twinkling" />

# 🤡 机器人感知炼丹师 / Bug Manufacturing Engineer

**Robot Perception Learner | OpenCV C++ | ROS2 | 2D/3D Vision**

<br>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=FF5733&center=true&vCenter=true&width=720&lines=Robot+Perception+Loading...;Pixel+Cat+Assistant+Online...;OpenCV+Debugging+In+Progress...;Camera+Calibration+Next+Quest...;ROS2+Nodes+Under+Construction...)](https://git.io/typing-svg)



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

```text
白天：Robot Perception Learner
晚上：OpenCV Error Researcher
深夜：CMake Mystery Observer
目标：让机器人知道自己到底该抓哪儿
```

---

---
## 🤹‍♂️ 核心技术栈 / Core Stack

<div align="center">
  <img src="https://img.shields.io/badge/C++17-Being_Tamed-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-Vision_Forge-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/CMake-Build_Ritual-064F8C?style=for-the-badge&logo=cmake&logoColor=white" />
  <img src="https://img.shields.io/badge/ROS2-Robot_Comms-22314E?style=for-the-badge&logo=ros&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-Neural_Summoning-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/PCL-Point_Cloud_Crew-2496ED?style=for-the-badge" />
</div>

<br>

<div align="center">
  <img src="https://img.shields.io/badge/Ctrl+C-Use_Carefully-2ea44f?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Ctrl+V-Paste_With_Brain-1f6feb?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Stack_Overflow-Emergency_Kit-F58025?style=for-the-badge&logo=stackoverflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Bug-Feature_In_Disguise-8A2BE2?style=for-the-badge" />
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
| 8 | Locked Quest | 待解锁 | ⏳ 待解锁 |

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

## 📈 摸鱼及机器人施工统计 / Build Progress

> GitHub stats 服务偶尔会加载失败，所以这里改成不抽风的手写施工面板。

| 模块 / Module | 当前进度 / Progress | 状态 / Status |
|---|---:|---|
| OpenCV Traditional Vision | `██████████` 100% | ✅ 已通关 |
| C++ / CMake Project Setup | `█████░░░░░` 40% | 🔧 继续驯服中 |
| Camera Calibration & Homography | `██░░░░░░░░` 20% | 🔜 当前主线 |
| ROS2 Perception Nodes | `░░░░░░░░░░` 0% | ⏳ 准备施工 |
| Robot Coordinate Transform | `░░░░░░░░░░` 0% | 💤 等待解锁 |
| PCL Point Cloud | `░░░░░░░░░░` 0% | 💤 等待解锁 |
| PyTorch / YOLO Vision | `░░░░░░░░░░` 0% | 💤 等待解锁 |
| SLAM | `░░░░░░░░░░` 0% | 🧊 终局副本 |

<div align="center">

<img src="https://img.shields.io/badge/Current_Quest-Camera_Calibration_%26_Homography-FF5733?style=for-the-badge" />
<img src="https://img.shields.io/badge/Main_Project-OpenCV_Grasp_Pose_Estimation-5C3EE8?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Building_Robot_Perception-2EA44F?style=for-the-badge" />

</div>

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


---

## 📊 GitHub Data Showcase / 数据展示

<div align="center">

<img src="./assets/pixel-cat.svg" width="118" alt="Pixel cat" />
<img src="./assets/pixel-dog.svg" width="96" alt="Pixel dog" />

<br>

<b>Pixel GitHub Dashboard：小猫负责看访客，小狗负责数提交。</b>

<br><br>

<img src="https://img.shields.io/badge/Mochi.cat-Visitor_Watcher-ffb6c1?style=for-the-badge" />
<img src="https://img.shields.io/badge/Debug.dog-Commit_Counter-a97142?style=for-the-badge" />

</div>

<br>

<div align="center">

<table>
  <tr>
    <td align="center" width="33%">
      <b>🐱 Visitors</b><br><br>
      <img src="https://komarev.com/ghpvc/?username=2X7V14N&label=Visitors&color=ff69b4&style=for-the-badge" />
    </td>
    <td align="center" width="33%">
      <b>🐾 Followers</b><br><br>
      <img src="https://img.shields.io/github/followers/2X7V14N?label=Followers&color=ffb86c&style=for-the-badge&logo=github" />
    </td>
    <td align="center" width="33%">
      <b>⭐ Stars</b><br><br>
      <img src="https://img.shields.io/github/stars/2X7V14N?affiliations=OWNER%2CCOLLABORATOR&label=Stars&color=f9e2af&style=for-the-badge&logo=github" />
    </td>
  </tr>
</table>

</div>

<br>

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=2X7V14N&theme=tokyonight" width="92%" />

<br><br>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=2X7V14N&theme=tokyonight" width="45%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=2X7V14N&theme=tokyonight&utcOffset=8" width="45%" />

<br><br>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=2X7V14N&theme=tokyonight" width="45%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=2X7V14N&theme=tokyonight" width="45%" />

</div>

<br>

```text
 /\_/\\   Mochi.cat: "访客 +1，已记录到小鱼干账本。"
( o.o )
 > ^ <    Debug.dog: "提交记录巡逻完成，GitHub 今日无异常。"
```

> 这里展示的是 GitHub 相关动态数据：访客、followers、stars、提交与语言统计。若某张统计卡偶尔加载失败，通常是第三方统计服务缓存或限流问题。
<div align="center">

<img src="./assets/pixel-bunny.svg" width="96" alt="Pixel bunny" />
<img src="./assets/pixel-cat.svg" width="110" alt="Pixel cat" />
<img src="./assets/pixel-bird.svg" width="94" alt="Pixel bird" />

<br>

<b>Pixel pets are closing the lab. See you in the next commit.</b>

</div>






