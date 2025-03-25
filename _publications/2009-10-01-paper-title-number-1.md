---
title: "基于图搜索技术求解八数码问题"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: '使用BFS、DFS以及两种启发式搜索分析比较不同算法之间的优缺点'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
---

实验1基于图搜索技术对八数码问题进行求解，实现了广度优先搜索（BFS）、深度优先搜索（DFS）以及两种启发式搜索（曼哈顿距离与错位计数）。对比分析了不同搜索算法的优缺点以及启发式函数的影响。BFS虽然简单且易于实现，但在大规模问题中易导致存储问题。
DFS的效率更高，但存在陷入死循环的风险，需要深度限制。启发式搜索算法（如A*算法）在解决复杂问题时表现突出，尤其是在路径优化方面更优。启发式搜素中估计函数的选择非常重要，经实验发现，曼哈顿距离在路径估计中更为精确，使搜索更加高效。错位计数虽然计算简单，但估计效果不如曼哈顿距离。但可能在不同情况下错位计数会优于曼哈顿距离。
