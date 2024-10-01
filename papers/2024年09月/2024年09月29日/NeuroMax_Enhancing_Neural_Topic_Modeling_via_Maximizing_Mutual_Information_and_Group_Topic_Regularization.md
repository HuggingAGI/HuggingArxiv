# NeuroMax：通过最大化互信息和组主题正则化，提升神经主题建模的效果。

发布时间：2024年09月29日

`LLM应用` `信息检索`

> NeuroMax: Enhancing Neural Topic Modeling via Maximizing Mutual Information and Group Topic Regularization

# 摘要

> 神经主题模型的最新进展主要聚焦于两个方向：一是将推理网络与预训练语言模型结合，二是建模词与主题在生成模型中的关系。然而，大型PLM的使用大幅增加了推理成本，使其在需要快速推理的场景中显得不够实用。同时，建模主题与词的关系以及主题间的相互关系也至关重要。为此，我们提出了NeuroMax框架，通过最大化神经主题模型编码器与PLM表示之间的互信息，并利用最优传输分析主题间信息流动，来学习主题关系。实验显示，NeuroMax不仅缩短了推理时间，还生成了更连贯的主题和主题组，提升了文档嵌入的代表性，从而增强了下游任务的性能。

> Recent advances in neural topic models have concentrated on two primary directions: the integration of the inference network (encoder) with a pre-trained language model (PLM) and the modeling of the relationship between words and topics in the generative model (decoder). However, the use of large PLMs significantly increases inference costs, making them less practical for situations requiring low inference times. Furthermore, it is crucial to simultaneously model the relationships between topics and words as well as the interrelationships among topics themselves. In this work, we propose a novel framework called NeuroMax (Neural Topic Model with Maximizing Mutual Information with Pretrained Language Model and Group Topic Regularization) to address these challenges. NeuroMax maximizes the mutual information between the topic representation obtained from the encoder in neural topic models and the representation derived from the PLM. Additionally, NeuroMax employs optimal transport to learn the relationships between topics by analyzing how information is transported among them. Experimental results indicate that NeuroMax reduces inference time, generates more coherent topics and topic groups, and produces more representative document embeddings, thereby enhancing performance on downstream tasks.

[Arxiv](https://arxiv.org/abs/2409.19749)