---
title: "基于熵权法-TOPSIS的目标优化模型在游览路径规划的应用"
collection: publications
category: conferences
permalink: /publication/2024-12-10-paper-title-number-6
excerpt: '结合多种数学模型和启发式算法，针对外国游客在中国的短期旅行进行优化的路径规划.'
date: 2024-12-10
paperurl: 'http://chatgwq.github.io/files/huashubei.pdf'
---

## 1. 数据预处理与景点评分分析
- 首先，论文对352个城市的景点评分数据进行了处理，去除了重复、异常和缺失值，建立了描述性统计模型。使用 MATLAB 分析城市景点的评分，找出最高评分的景点。

## 2. 城市综合评价
- 运用熵权法-TOPSIS模型对352个城市进行综合评价，考虑了城市规模、空气质量、博物馆数量、高铁活动量、年均气温、特色美食等因素，选择出最受外国游客向往的 50 个城市。

## 3. 旅行路径规划与优化
- 论文采用了旅行商问题（TSP）模型，结合网络优化方法，规划了外国游客从广州出发的最优游玩路线。在有限的时间内，最大化游玩城市数量，并考虑高铁交通时间、景点的开放时间等因素。

## 4. 多目标优化模型
- 在问题三的基础上，论文通过多目标优化模型进一步优化了旅行路径，使游客能够在有限的预算和时间内，既游览尽可能多的城市，又尽量减少交通和门票费用。

## 5. 个性化游览路线规划
- 对于仅对山景感兴趣的游客，论文建立了一个多目标粒子群优化模型，规划出既能游览更多山景，又能减少门票和交通费用的最优路线。

## 结论
- 运用蚁群算法、粒子群优化算法和熵权法-TOPSIS模型等多种优化算法，结合具体的旅行需求，通过数学建模实现了针对外国游客的高效路径规划。
