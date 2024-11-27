# TabulaX：借助大型语言模型实现多类表格的转换

发布时间：2024年11月26日

`LLM应用` `数据分析` `表格数据处理`

> TabulaX: Leveraging Large Language Models for Multi-Class Table Transformations

# 摘要

> 来自不同来源的表格数据整合常因格式和表示的不一致而受阻，这给数据分析师和个人数字助理带来巨大挑战。现有的表格数据自动化转换方法存在局限性，往往聚焦特定类型的转换或缺乏可解释性。本文中，我们推出了 TabulaX，这是一个借助大型语言模型（LLMs）实现多类表格转换的新颖框架。TabulaX 先将输入表格分为四类（基于字符串的、数值的、算法的和一般性的），然后运用定制方法生成人类可理解的转换函数，比如数字公式或编程代码。此方法增强了透明度，使用户能够理解和修改映射。通过对来自不同领域的真实世界数据集展开大量实验，我们表明 TabulaX 在准确性上优于现有先进方法，支持更广泛的转换类别，并生成能有效应用的可解释转换。

> The integration of tabular data from diverse sources is often hindered by inconsistencies in formatting and representation, posing significant challenges for data analysts and personal digital assistants. Existing methods for automating tabular data transformations are limited in scope, often focusing on specific types of transformations or lacking interpretability. In this paper, we introduce TabulaX, a novel framework that leverages Large Language Models (LLMs) for multi-class tabular transformations. TabulaX first classifies input tables into four transformation classes (string-based, numerical, algorithmic, and general) and then applies tailored methods to generate human-interpretable transformation functions, such as numeric formulas or programming code. This approach enhances transparency and allows users to understand and modify the mappings. Through extensive experiments on real-world datasets from various domains, we demonstrate that TabulaX outperforms existing state-of-the-art approaches in terms of accuracy, supports a broader class of transformations, and generates interpretable transformations that can be efficiently applied.

[Arxiv](https://arxiv.org/abs/2411.17110)