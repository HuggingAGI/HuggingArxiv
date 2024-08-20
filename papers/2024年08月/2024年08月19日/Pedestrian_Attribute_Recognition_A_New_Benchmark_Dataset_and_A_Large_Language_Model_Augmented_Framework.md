# 行人属性识别领域迎来新挑战，我们推出全新基准数据集，并构建大型语言模型增强框架，助力该领域发展。

发布时间：2024年08月19日

`LLM应用` `行人属性识别` `人工智能`

> Pedestrian Attribute Recognition: A New Benchmark Dataset and A Large Language Model Augmented Framework

# 摘要

> 行人属性识别（PAR）是人类中心研究的关键任务。现有数据集忽视了多领域差异，仅简单随机分割，性能已趋饱和。过去五年未有大尺度数据集公开。为此，我们提出MSP60K，一个包含60,122张图像、57个属性标注的跨领域数据集，并进行合成降级以贴近真实挑战。我们评估了17个PAR模型，并提出LLM-PAR框架，通过ViT提取特征，多嵌入查询Transformer学习部分感知特征，并利用LLM增强集成学习和视觉特征。实验证明其有效性。数据集与代码将公开于\url{https://github.com/Event-AHU/OpenPAR}。

> Pedestrian Attribute Recognition (PAR) is one of the indispensable tasks in human-centered research. However, existing datasets neglect different domains (e.g., environments, times, populations, and data sources), only conducting simple random splits, and the performance of these datasets has already approached saturation. In the past five years, no large-scale dataset has been opened to the public. To address this issue, this paper proposes a new large-scale, cross-domain pedestrian attribute recognition dataset to fill the data gap, termed MSP60K. It consists of 60,122 images and 57 attribute annotations across eight scenarios. Synthetic degradation is also conducted to further narrow the gap between the dataset and real-world challenging scenarios. To establish a more rigorous benchmark, we evaluate 17 representative PAR models under both random and cross-domain split protocols on our dataset. Additionally, we propose an innovative Large Language Model (LLM) augmented PAR framework, named LLM-PAR. This framework processes pedestrian images through a Vision Transformer (ViT) backbone to extract features and introduces a multi-embedding query Transformer to learn partial-aware features for attribute classification. Significantly, we enhance this framework with LLM for ensemble learning and visual feature augmentation. Comprehensive experiments across multiple PAR benchmark datasets have thoroughly validated the efficacy of our proposed framework. The dataset and source code accompanying this paper will be made publicly available at \url{https://github.com/Event-AHU/OpenPAR}.

[Arxiv](https://arxiv.org/abs/2408.09720)