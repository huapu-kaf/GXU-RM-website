---
title: 项目
nav:
  order: 2
  tooltip: 校企合作、科研项目
---

# {% include icon.html icon="fa-solid fa-wrench" %}我们的项目

## RoboMaster 机器人项目

{% capture text %}
自适应底盘设计：适应多种地形运动，避免轮子悬空空转导致功率浪费；

三摩擦轮设计：能够实现20m吊射42mm大弹丸打击大装甲板大小模块，命中率60%；实现自动瞄准打击7-8m旋转装甲板；

超级电容：四开关buck-boost 能实现300W稳定放电；

软件控制已实现功率控制、PID+跟踪微分器+前馈、利用弹道方程结合打击目标标定发射机构参数；

视觉部分实现YOLO v8关键点检测、PNP位姿解算。

{% endcapture %}

{%
  include feature.html
  image="images/projects/rm/1.png"
  link="projects"
  title="英雄机器人"
  flip=false
  style="bare"
  text=text
  height="40%"
%}


{% capture text %}
多种底盘结构：全向轮、舵轮、轮腿；

FreeRTOS操作系统实现单片机伪多线程处理；

多轮组运动方程解算满足不同机器人底盘需求；

PID&ADRC实现云台精准控制。
{% endcapture %}

{%
  include feature.html
  image="images/projects/rm/2.png"
  link="projects"
  title="步兵机器人"
  flip=true
  style="bare"
  text=text
  height="40%"
%}


{% capture text %}
全自动运行：卡尔曼运动融合多传感器数据，使机器人自我感知运动状态；

全自动导航：全自由度舵轮赋能精准里程计，结合激光雷达DLIO定位与PCL点云处理，机内实现大量点云处理；PCL可视化地图深度融合A*路径规划。

{% endcapture %}

{%
  include feature.html
  image="images/projects/rm/3.png"
  link="projects"
  title="哨兵机器人"
  flip=false
  style="bare"
  text=text
  height="40%"
%}

{% capture text %}
六轴机械臂，仿生手臂设计方便复杂地形物体获取；

电磁阀结合真空泵实现真空链路，实现物品轻易吸取；

并联机械臂结构，方便多目标简单获取。
{% endcapture %}

{%
  include feature.html
  image="images/projects/rm/4.png"
  link="projects"
  title="工程机器人"
  flip=true
  style="bare"
  text=text
  height="40%"
%}

{% capture text %}
自主研发48V高功率供电板；

轻量化机身设计四轴多旋翼无人机；

Gidance视觉定位稳定悬停，非线性预测，飞控通道映射，助力稳定悬停。

{% endcapture %}

{%
  include feature.html
  image="images/projects/rm/5.png"
  link="projects"
  title="空中机器人"
  flip=false
  style="bare"
  text=text
  height="40%"
%}

{% capture text %}
多种方案并行验证，采用双极摩擦轮方案，摩擦轮温控系统，精确控制摩擦轮发射时条件一致性；

精确控制发射底座朝向，提升20m命中率。
{% endcapture %}

{%
  include feature.html
  image="images/projects/rm/6.png"
  link="projects"
  title="飞镖机器人"
  flip=true
  style="bare"
  text=text
  height="40%"
%}
{% capture text %}
利用工业相机结合激光雷达实现多目标识别、定位和交互；

软件上基于Ubuntu平台实现YoloV8目标检测、目标定位、决策通信，点云聚类极限达50FPS。
{% endcapture %}

{%
  include feature.html
  image="images/projects/rm/7.png"
  link="projects"
  title="雷达机器人"
  flip=false
  style="bare"
  text=text
  height="40%"
%}
