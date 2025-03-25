---
title: "聚类分析"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: '使用K-means++对UCI Iris和Bank Marketing数据集进行聚类分析，且通过PCA降维和肘部法则确定最佳聚类数，结合轮廓系数评价聚类效果.'
date: 2024-12-11
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
---

使用K-means++对UCI Iris和Bank Marketing数据集进行聚类分析，且通过PCA降维和肘部法则确定最佳聚类数，结合轮廓系数评价聚类效果。结合实验结果分析得知，K-means++在初始化聚类中心时更加高效，能有效避免K-means陷入局部最优。PCA降维简化了数据维度，同时保留了主要特征信息，有助于提高聚类效果和可视化。通过这个实验我也明白了数据处理的重要性，聚类结果高度依赖数据分布和标准化处理，实验中使用MinMaxScaler标准化特征后，结果更加稳定。针对异常值的处理（如Z-score检测）对提升聚类效果也很重要。
