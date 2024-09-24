# HM3D-OVON：开放词汇对象导航的数据集与基准

发布时间：2024年09月21日

`Agent` `人工智能` `智能家居`

> HM3D-OVON: A Dataset and Benchmark for Open-Vocabulary Object Goal Navigation

# 摘要

> 我们推出了 Habitat-Matterport 3D 开放词汇对象导航数据集 (HM3D-OVON)，这是一个大规模基准，极大地扩展了对象导航 (ObjectNav) 的语义范围。HM3D-OVON 利用 HM3DSem 数据集，涵盖了从真实世界 3D 扫描中提取的 15k 多个家庭对象，分为 379 个类别。与早期仅限于 6-20 个预定义类别的 ObjectNav 数据集不同，HM3D-OVON 允许在测试时通过自由文本定义开放目标集的模型训练和评估。这种开放词汇表的设计鼓励了视觉语义导航行为的学习，使其能够以开放方式搜索文本指定的任何对象。我们还系统地评估了多种方法，发现 HM3D-OVON 可以训练出性能优于现有最先进方法且对噪声更鲁棒的开放词汇表 ObjectNav 代理。我们期待这一基准和基线结果能推动具身代理的发展，使其能够灵活地导航真实世界，寻找通过自由文本指定的家庭对象，从而实现更人性化的语义视觉导航。相关代码和视频可在 naoki.io/ovon 获取。

> We present the Habitat-Matterport 3D Open Vocabulary Object Goal Navigation dataset (HM3D-OVON), a large-scale benchmark that broadens the scope and semantic range of prior Object Goal Navigation (ObjectNav) benchmarks. Leveraging the HM3DSem dataset, HM3D-OVON incorporates over 15k annotated instances of household objects across 379 distinct categories, derived from photo-realistic 3D scans of real-world environments. In contrast to earlier ObjectNav datasets, which limit goal objects to a predefined set of 6-20 categories, HM3D-OVON facilitates the training and evaluation of models with an open-set of goals defined through free-form language at test-time. Through this open-vocabulary formulation, HM3D-OVON encourages progress towards learning visuo-semantic navigation behaviors that are capable of searching for any object specified by text in an open-vocabulary manner. Additionally, we systematically evaluate and compare several different types of approaches on HM3D-OVON. We find that HM3D-OVON can be used to train an open-vocabulary ObjectNav agent that achieves both higher performance and is more robust to localization and actuation noise than the state-of-the-art ObjectNav approach. We hope that our benchmark and baseline results will drive interest in developing embodied agents that can navigate real-world spaces to find household objects specified through free-form language, taking a step towards more flexible and human-like semantic visual navigation. Code and videos available at: naoki.io/ovon.

[Arxiv](https://arxiv.org/abs/2409.14296)