# 通过将知识概念与全切片图像相匹配，实现精确的组织病理学图像分析

发布时间：2024年11月27日

`LLM应用` `病理分析`

> Aligning Knowledge Concepts to Whole Slide Images for Precise Histopathology Image Analysis

# 摘要

> 由于全切片图像（WSIs）规模大且缺少细粒度标注，其分析通常被当作多实例学习（MIL）问题来处理。然而，以往的研究仅依赖训练数据进行学习，这和人类临床医生相互传授以及对组织病理学实体和因素进行推理的方式截然不同。在此，我们推出了一个全新的基于知识概念的MIL框架，叫做ConcepPath，来填补这一空缺。具体来说，ConcepPath借助GPT-4从医学文献中获取可靠的疾病特异性人类专家概念，并将其与一组纯可学习的概念相结合，从训练数据中提取互补知识。在ConcepPath中，利用病理视觉语言模型这一基本构建组件，使WSIs与这些语言知识概念相匹配。在肺癌亚型分类、乳腺癌HER2评分以及胃癌免疫治疗敏感亚型分类任务的应用里，ConcepPath明显胜过以往缺少人类专家知识引导的SOTA方法。

> Due to the large size and lack of fine-grained annotation, Whole Slide Images (WSIs) analysis is commonly approached as a Multiple Instance Learning (MIL) problem. However, previous studies only learn from training data, posing a stark contrast to how human clinicians teach each other and reason about histopathologic entities and factors. Here we present a novel knowledge concept-based MIL framework, named ConcepPath to fill this gap. Specifically, ConcepPath utilizes GPT-4 to induce reliable diseasespecific human expert concepts from medical literature, and incorporate them with a group of purely learnable concepts to extract complementary knowledge from training data. In ConcepPath, WSIs are aligned to these linguistic knowledge concepts by utilizing pathology vision-language model as the basic building component. In the application of lung cancer subtyping, breast cancer HER2 scoring, and gastric cancer immunotherapy-sensitive subtyping task, ConcepPath significantly outperformed previous SOTA methods which lack the guidance of human expert knowledge.

[Arxiv](https://arxiv.org/abs/2411.18101)