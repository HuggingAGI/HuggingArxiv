# 细粒度知识图谱助力视频与语言学习，精准识别动作。

发布时间：2024年07月19日

`LLM应用` `视频处理` `人工智能`

> Fine-grained Knowledge Graph-driven Video-Language Learning for Action Recognition

# 摘要

> 近期研究将视频动作识别视为视频与文本的匹配问题，并基于大规模预训练的视觉-语言模型提出了多种有效方法。然而，这些方法主要在粗粒度层面运作，未能深入理解动作概念的细节和语义。为此，我们提出了一个由知识图谱引导的对比视频-语言学习框架——KG-CLIP，该框架将结构化信息融入视频领域的CLIP模型。我们通过组合学习解析动作，构建了一个包含多粒度概念的多模态知识图谱。通过自适应优化实体距离函数中的边际，我们的模型旨在提升知识图中实体的对齐，从而更好地适应复杂关系学习。这增强了视频动作识别能力，能够处理图组件间的细微关联。我们在Kinetics-TPS数据集上全面评估了KG-CLIP，显示其优于竞争基线，特别是在样本帧少或训练数据有限的情况下，展现了卓越的数据利用和学习能力。

> Recent work has explored video action recognition as a video-text matching problem and several effective methods have been proposed based on large-scale pre-trained vision-language models. However, these approaches primarily operate at a coarse-grained level without the detailed and semantic understanding of action concepts by exploiting fine-grained semantic connections between actions and body movements. To address this gap, we propose a contrastive video-language learning framework guided by a knowledge graph, termed KG-CLIP, which incorporates structured information into the CLIP model in the video domain. Specifically, we construct a multi-modal knowledge graph composed of multi-grained concepts by parsing actions based on compositional learning. By implementing a triplet encoder and deviation compensation to adaptively optimize the margin in the entity distance function, our model aims to improve alignment of entities in the knowledge graph to better suit complex relationship learning. This allows for enhanced video action recognition capabilities by accommodating nuanced associations between graph components. We comprehensively evaluate KG-CLIP on Kinetics-TPS, a large-scale action parsing dataset, demonstrating its effectiveness compared to competitive baselines. Especially, our method excels at action recognition with few sample frames or limited training data, which exhibits excellent data utilization and learning capabilities.

[Arxiv](https://arxiv.org/abs/2407.14146)