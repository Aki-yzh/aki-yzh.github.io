---
title: FMCW点云与深度学习
publishDate: 2023-09-13 23:55:10
description: ' 对毫米波雷达采集到的点云进行处理'
language: '中文'
tags:
  - FMCW
  - ai
  - deep
  - learning
---

# FMCW点云与深度学习

## 人体定位

利用速度对人体进行定位，利用微动（胸部呼吸心跳）对高度进行定位

## CFAR

自适应阈值方法

通过区分出速度为0的个体分离出人体。

## 坐标校准

小车运动利用SLAM得到世界坐标系下的直线，与雷达坐标系下的直线，求解出旋转矩阵

## SVD
