#Pedestrian and Vehicle Detection Based on Faster R-CNN Pre-built Algorithm
This project is built on the Huawei Cloud ModelArts platform, utilizing its pre-built Faster R-CNN algorithm to implement pedestrian and vehicle detection in images. Through a complete model training and deployment process, automatic identification and localization of vehicles and pedestrians are achieved, providing foundational detection capabilities for scenarios such as traffic safety and autonomous driving.

##Project Overview
**Platform**: Huawei Cloud ModelArts
**Algorithm**: Faster R-CNN Pre-built Algorithm
**Task**: Object detection of pedestrians and vehicles in images
**Output**: Bounding boxes marking the positions of pedestrians and vehicles in images

##Main Tasks
**Server Setup**: Created and configured the ModelArts environment on the Huawei Cloud platform
**Data Annotation**: Imported image datasets and annotated the positions of pedestrians and vehicles in each image with bounding boxes
**Model Training**: Trained the annotated dataset using the Faster R-CNN pre-built algorithm
**Model Deployment**: Deployed the trained model as an online service
**Prediction Analysis**: Uploaded test images for prediction, output detection results, and performed analysis

##Project Structure
Main
├── Report
│ └── ModelArts.pdf ------ Project report (including experimental process and conclusions)
├── Picture
│ ├── Detection_1.PNG ---- Example of detection result 1
│ └── Detection_2.PNG ---- Example of detection result 2
└── README.md ------------ Describe of this project

#基于FasterRCNN预置算法的人车检测
本项目基于华为云ModelArts平台，利用其预置的FasterRCNN算法实现图像中的人车检测。通过完整的模型训练与部署流程，实现对车辆及行人的自动识别与定位，为交通安全、自动驾驶等场景提供基础检测能力。

##项目概述
**平台**：华为云 ModelArts
**算法**：FasterRCNN 预置算法
**任务**：图像中的人、车目标检测
**输出**：在图像中以矩形框形式标出人和车的位置

##主要工作
**服务器搭建**：在华为云平台创建并配置ModelArts环境
**数据标注**：导入图像数据集，对每张图像中的人、车位置进行矩形框标注
**模型训练**：基于FasterRCNN预置算法训练标注好的数据集
**模型部署**：将训练好的模型部署为在线服务
**预测分析**：上传测试图像进行预测，输出检测结果并分析

##项目结构
Main
├── Report
│   └── ModelArts.pdf -------- 项目报告（含实验过程与结论）
├── Picture
│   ├── Detection_1.PNG ------ 检测结果示例1
│   └── Detection_2.PNG ------ 检测结果示例2
└── README.md ---------------- 项目说明文档
