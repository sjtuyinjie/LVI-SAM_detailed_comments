# LVI-SAM超详细注释与配套

-by 计算机视觉life 旗下 [SLAM知识星球学习小组](https://mp.weixin.qq.com/s/Lzn7jUPRwpbMqe-5Ku9Ksg)

**参与人员**（排名不分先后）：

荆黎明（东北大学）、刘嘉林（复旦大学）、汪寿安（中国矿业大学北京）、万文俊（中科院计算所）、周新杰（哈工大）、乔生（吉林大学）、刘嘉荣（上海交通大学）

## 一、我们的贡献
1. 为源代码提供了详细的中文注释
2. 制作了docker镜像，可节约本地环境配置时间
3. 录制了校园内的实际数据集并开放
4. 在更多数据集上的验证可行性

## 二、docker环境链接

[LVI-SAM学习小组docker v1.2使用图文简洁介绍](https://github.com/electech6/LVI-SAM_detailed_comments/blob/master/LVI-SAM%E5%AD%A6%E4%B9%A0%E5%B0%8F%E7%BB%84docker%20v1.2%E4%BD%BF%E7%94%A8%E5%9B%BE%E6%96%87%E7%AE%80%E6%B4%81%E4%BB%8B%E7%BB%8D.pdf)

docker镜像已上传docker-hub，可以拉取镜像按照教程使用节约环境配置的时间
拉取镜像的命令：```docker pull liangjinli/slam-docker:v1.2```


## 三、学习小组录制LVI-SAM数据集

链接:https://pan.baidu.com/s/1e5UhbLfnJE28wVy1l1Rc3w?fm=lk0 
提取码:x5xi

百度网盘里存有80G的bag包，bag包的使用说明见此仓库的[README](https://github.com/shuttworth/Record_Datasets_For_LVI-SAM)


### 采集设备

<center>
<img src="https://github.com/shuttworth/Record_Datasets_For_LVI-SAM/blob/main/img/device.jpg" width="70%">
</center>

### 建图效果
<center>
<img src="https://github.com/shuttworth/Record_Datasets_For_LVI-SAM/blob/main/img/result.png" width="70%">
</center>


## 四、在M2DGR数据集上演示
<center>
<img src="https://github.com/shuttworth/Record_Datasets_For_LVI-SAM/blob/main/img/gate_01_v1.gif" width="70%">
</center>

<center>
<img src="https://github.com/shuttworth/Record_Datasets_For_LVI-SAM/blob/main/img/street_08_v1.gif" width="70%">
</center>


## 五、学习小组分享顺序

1. **LVI-SAM英文论文精读** 
2. **简单捋一遍LOAM到LVI-SAM的方法跃迁**
3. **visual_feature + featureExtraction** ，横向对比视觉和雷达的提取特征思路上的异同 
4. **imuPreintergation.cpp**，结合imu预积分的原理推导和代码讲解 
5. **visual_estimator** ，视觉里程计部分
6. **imageProjection.cpp** ，激光雷达数据去畸变 
7. **mapOptmization**  ，因子图优化
8. **visual_loop** ，视觉回环模块 
9. **回顾盘点**，理清系统的数据流动，节点之间的关系和总览

视频和课件分享见 [cvlife.net](https://cvlife.net/detail/p_620a027fe4b02b82584a90e2/6) 



## 六、中文代码注释

中文注释的代码已全部上传

期待反馈当前注释存在的问题！



## 七、LVI-SAM 原仓库链接

https://github.com/TixiaoShan/LVI-SAM

