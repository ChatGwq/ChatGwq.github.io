---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.E in Software Engineering, Guangzhou University, 2026 (expected)

Project experience
======
* 【项目名称】：身形优化商业计划书                                【项目角色】：项目负责人
  * 市场调研：通过问卷星/SPSS收集分析消费者数据，划分出健身人群/亚健康白领/控糖群体3大核心客群。 
  * 用户调研：建立BMI指数/消费场景/营养诉求等维度的用户画像体系。 
  * 竞品分析：挖掘识别出产品痛点，完成商业模型测算，基于竞品定价与成本结构数据，建立动态定价模型,预测首年毛利率达52%。
  * 报告输出： 输出商业计划书，整合市场/用户/财务数据。 
 * 【项目名称】：基于微信小程序焦虑情绪分享平台                   【项目角色】：核心成员
  * 需求挖掘：设计混合调研方案，通过问卷星收集文本数据，结合课程评论情感分析，建立学习焦虑，考试焦虑，社交焦虑，择业焦虑以及考研焦虑等焦虑系数计算公式。  
  * 数据集成：整合相关等因素与论坛评论等多源数据，使用Python完成20+焦虑相关特征提取。
  * 构建模型：融合随机森林，通过交叉验证焦虑值预测；设计用户反馈闭环，开发系统焦虑预警API接口，持续收集用户焦虑因素的数据优化模型。 
  * 数据可视化：设计焦虑热力图看板，开发个性化推荐引擎。


  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
