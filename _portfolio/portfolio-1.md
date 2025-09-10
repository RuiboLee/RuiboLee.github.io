---
title: "基于FAST-LIO2实时建图与YOLOv5动态检测的无人机-无人车协同救灾系统"
excerpt: "无人机自主巡检效果<br/><img src='/images/autonomous_inspection.gif'>"
collection: Projects
---

设计并实现了一套空地协同的智能消防救灾系统。该系统由无人机和无人消防车组成，其中无人机搭载激光雷达和摄像头，运用 Fast-LIO2 算法进行实时三维建图，并通过 YOLOv5 算法动态检测火情并定位火源。同时，无人机利用 EGO-Planner 算法实现自主巡检，并将地图与火源坐标信息实时共享。消防车接收无人机共享的地图和火源信息，采用 AMCL 算法进行重定位，并结合 A *算法实现自主全局路径规划和 DWA 局部避障，快速抵达火源点执行灭火任务。
