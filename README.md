# Fakeddit——domian——datasets 数据集

本项目包含一个 **基于 Fakeddit 数据集标注的领域数据集**，用于虚假新闻研究和多模态分析。  

该数据集是在原始 [Fakeddit](https://github.com/entitize/Fakeddit) 数据基础上进行 **领域标注和整理** 后生成的。  
特别感谢 Fakeddit 项目提供的原始数据和标注框架。  

## 数据集内容
- train.pkl
- val.pkl
- test.pkl  

## 数据标注说明
- 数据标签主要由 **大模型自动标注**  
- 并经过 **人工核验**，保证大部分领域标签准确  
- 如果你在使用过程中发现 **标签有问题或不准确**，欢迎提出 Issue 或反馈  


> 数据经过字段清理和特征整理，可直接用于多领域多模态虚假新闻实验。  

## 引用
如果你在研究或论文中使用本数据集，请引用 Fakeddit 原始项目：  
@misc{fakeddit,
author = {Entitize},
title = {Fakeddit: A Multimodal Dataset for Fine-grained Fake News Detection},
howpublished = {\url{[https://github.com/entitize/Fakeddit](https://github.com/entitize/Fakeddit)}}
,
year = {2021}
}
