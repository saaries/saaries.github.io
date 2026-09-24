---
layout: default
title: "李心妍的个人主页"
site_title: "李心妍的个人主页"
description: "李心妍的个人主页：大语言模型后训练、工具集成数学推理与推理效率优化。"
lang: zh-CN
home_path: /zh/
permalink: /zh/
---

## 李心妍 (Xinyan Li)

高级研究工程师
<br>华为香港研究中心
<br>中国香港
<br>邮箱：<span class="email">xinyanli4-c AT my.cityu.edu.hk</span>

[Google Scholar]({{ site.google_scholar }}) · [GitHub]({{ site.github }}) · [英文简历](/resume.pdf)

---

## 个人简介

你好！我目前在华为香港研究中心担任高级研究工程师，负责 30B+ 大语言模型的端到端后训练，工作覆盖数据构建、SFT/RL、分布式采样与评测。我的研究兴趣包括工具集成数学推理、强化学习、智能体模型训练以及推理 token 效率优化。

我于 2025 年在[香港城市大学](https://www.cityu.edu.hk/)获得计算机科学博士学位，导师为 [Cong Wang 教授](https://www.cs.cityu.edu.hk/~congwang/)。博士期间，我主要研究加密搜索系统中的隐私泄漏及其缓解机制。在此之前，我在香港城市大学获得计算机科学硕士学位（Distinction），并在[华南理工大学](https://www.scut.edu.cn/new/main.htm)获得计算机科学与技术学士学位。

---

## 工作经历

- **2025 年 6 月至今：** 高级研究工程师，华为香港研究中心
  - 负责 30B+ 大语言模型的端到端后训练，重点研究工具集成推理与 token 高效推理。
- **2024 年 12 月至 2025 年 5 月：** 研究实习生，华为香港研究中心
  - 探索不同 RAG 架构与输入归因方法，分析实际业务中的模型异常案例，并评估基于检索的改进方案。
- **2020 年 12 月至 2021 年 6 月：** 研究助理，香港城市大学
- **2018 年 6 月至 2018 年 7 月：** 实习生，中国电信互联网创新中心

---

## 代表性研究与项目

### 工具集成数学推理

- 通过 SFT 和多阶段强化学习训练大语言模型使用 Python 及 Wolfram/Mathematica 解决数学问题。
- 针对中小学数学与物理、大学数学与物理以及竞赛数学，开展能力专项训练与评测。
- 构建教师模型推理轨迹、过滤无效工具调用并清洗 SFT 数据，以提升模型真实的工具使用能力。

### Token 高效推理

- 采用 Long-to-Short RL，将具有 32K 上下文预算的模型所具备的推理能力迁移至 8K 预算模型，同时保持答案准确率。
- 设计强化学习目标与长度惩罚，在推理压缩、答案准确率和过早终止之间取得平衡。

### 智能体模型训练

- 研究基于 SFT、多轮强化学习、工具调用轨迹、环境反馈、可验证奖励和轨迹筛选的智能体训练流程。

---

## 教育经历

- **2021–2025：** 计算机科学博士，香港城市大学
  - GPA：3.87/4.0
  - 博士论文：*Designing Leakage-Aware Mechanisms for Encrypted Search Systems*
  - 导师：[Cong Wang 教授](https://www.cs.cityu.edu.hk/~congwang/)
- **2019–2020：** 计算机科学硕士（Distinction），香港城市大学
- **2015–2019：** 计算机科学与技术学士，华南理工大学
  - 曾赴天津大学及俄罗斯 ITMO University 交流学习

---

## 论文发表

- **Xinyan Li**, Yuefeng Du, and Cong Wang. [When Differential Privacy Meets Query Control: A Hybrid Framework for Practical Range Query Leakage Quantification and Mitigation](https://doi.org/10.1109/TSC.2024.3517316), *IEEE Transactions on Services Computing*, 18(2):1137–1151, 2025.

- **Xinyan Li**, Yuefeng Du, and Cong Wang. [RangeQC: A Query Control Framework for Range Query Leakage Quantification and Mitigation](https://doi.org/10.1109/ICDCS57875.2023.00017), *IEEE International Conference on Distributed Computing Systems (ICDCS)*, pp. 749–759, 2023.

- **Xinyan Li**, Yufei Chen, Cong Wang, and Chao Shen. [When Deep Learning Meets Differential Privacy: Privacy, Security, and More](https://doi.org/10.1109/MNET.001.2100256), *IEEE Network*, 35(6):148–155, 2021.

---

## 技术能力

- **大模型后训练：** SFT、强化学习、多阶段强化学习、Long-to-Short RL
- **推理能力：** 工具集成推理、工具调用、数学与物理推理
- **框架与系统：** verl、TRL、Slurm、分布式训练、采样与评测
- **编程语言：** Python、C/C++、Java、Shell、SQL

---

## 荣誉与奖项

- 香港城市大学 Institutional Research Tuition Scholarship，2022–2024
- 香港城市大学计算机科学系 Achievement Scholarship，2019
