# 通过线性表示，探索大型语言模型从认知到表达的演变之旅

发布时间：2024年05月27日

`LLM理论

这篇论文主要探讨了大型语言模型（如百川-7B和百川-33B）的认知与表达能力的演变及其相互作用。研究内容涉及模型的预训练、监督微调及人类反馈强化学习等阶段，以及这些阶段如何影响模型的认知和表达能力。此外，论文还分析了认知能力与表达能力之间的关系，并探讨了这些发展轨迹的理论基础及其与模型架构的关系。这些内容属于对大型语言模型理论层面的深入分析，因此应归类为LLM理论。` `人工智能` `认知科学`

> Exploring the LLM Journey from Cognition to Expression with Linear Representations

# 摘要

> 本文深入分析了大型语言模型（如百川-7B和百川-33B）中认知与表达能力的演变及其相互作用。通过预训练、监督微调及人类反馈强化学习三个阶段，我们界定了模型的认知与表达能力。认知能力体现在神经网络中神经元输出向量传递信息的质与量，类似人类认知的神经信号处理。表达能力则指模型生成单词级输出的能力。研究发现，认知能力在预训练阶段基本形成，而表达能力则在后续阶段显著提升。统计分析显示两者紧密相关，暗示认知能力可能制约表达潜力。文章还探讨了这些发展轨迹的理论基础及其与模型架构的关系，并评估了如少量学习等策略，以弥合认知与表达之间的差距。此研究揭示了隐藏空间与输出空间间的联系，为理解和控制训练过程提供了新视角。

> This paper presents an in-depth examination of the evolution and interplay of cognitive and expressive capabilities in large language models (LLMs), with a specific focus on Baichuan-7B and Baichuan-33B, an advanced bilingual (Chinese and English) LLM series. We define and explore the model's cognitive and expressive capabilities through linear representations across three critical phases: Pretraining, Supervised Fine-Tuning (SFT), and Reinforcement Learning from Human Feedback (RLHF). Cognitive capability is defined as the quantity and quality of information conveyed by the neuron output vectors within the network, similar to the neural signal processing in human cognition. Expressive capability is defined as the model's capability to produce word-level output. Our findings unveil a sequential development pattern, where cognitive abilities are largely established during Pretraining, whereas expressive abilities predominantly advance during SFT and RLHF. Statistical analyses confirm a significant correlation between the two capabilities, suggesting that cognitive capacity may limit expressive potential. The paper also explores the theoretical underpinnings of these divergent developmental trajectories and their connection to the LLMs' architectural design. Moreover, we evaluate various optimization-independent strategies, such as few-shot learning and repeated sampling, which bridge the gap between cognitive and expressive capabilities. This research reveals the potential connection between the hidden space and the output space, contributing valuable insights into the interpretability and controllability of their training processes.

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/schematic_diagram.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/pretrain_pca.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/expressive_cognitive_SFT_PPO.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/convergence_of_cognition.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/umap_visualization_1.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/pca_layer_obqa.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/new_vocab_linear_change.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/baseline_arc_challenge.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/baseline_arc_easy.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/baseline_arc_challenge.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/baseline_csqa.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/baseline_obqa.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/baseline_race.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/pca_layer_arc_easy.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/pca_layer_arc_challenge.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/pca_layer_csqa.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/pca_layer_obqa.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/pca_pretrain_7B.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/7B_arc_easy.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/7B_arc_challenge.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/7B_csqa.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/7B_obqa.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/33B-lm-eval-arc-easy.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/33B-lm-eval-arc-challenge.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/33B-lm-eval-csqa.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/33B-lm-eval-obqa.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/7B-lm-eval-arc-easy.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/7B-lm-eval-arc-challenge.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/7B-lm-eval-race.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/7B-lm-eval-obqa.png)

![通过线性表示，探索大型语言模型从认知到表达的演变之旅](../../../paper_images/2405.16964/gap_race.png)

[Arxiv](https://arxiv.org/abs/2405.16964)