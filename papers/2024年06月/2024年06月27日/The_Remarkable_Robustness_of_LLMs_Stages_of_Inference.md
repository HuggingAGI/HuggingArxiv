# 大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？

发布时间：2024年06月27日

`LLM理论

这篇论文的摘要主要探讨了大型语言模型（LLM）的内部结构和鲁棒性，通过实验分析了模型层级结构的变化对模型性能的影响，并提出了模型推理的四个普遍阶段。这些内容更偏向于对LLM理论层面的研究和理解，因此应归类为LLM理论。` `模型鲁棒性`

> The Remarkable Robustness of LLMs: Stages of Inference?

# 摘要

> 我们通过删除和交换相邻层，揭示了大型语言模型的非凡鲁棒性。实验表明，即使不进行微调，这些操作也能保持模型72-95%的预测准确性，且层数越多的模型鲁棒性越强。基于层级干预的实验结果，我们推测所有模型都经历了四个普遍的推理阶段：解标记化、特征工程、预测集成和残差锐化。首先，模型整合局部信息，提升原始标记至高级上下文表示；随后，对任务和实体特定特征进行迭代优化；接着，模型后半部分经历相变，隐藏表示与词汇空间对齐；最后，通过消除过时特征，最后一层精炼了后续标记的分布，减少了预测中的噪声。

> We demonstrate and investigate the remarkable robustness of Large Language Models by deleting and swapping adjacent layers. We find that deleting and swapping interventions retain 72-95\% of the original model's prediction accuracy without fine-tuning, whereas models with more layers exhibit more robustness. Based on the results of the layer-wise intervention and further experiments, we hypothesize the existence of four universal stages of inference across eight different models: detokenization, feature engineering, prediction ensembling, and residual sharpening. The first stage integrates local information, lifting raw token representations into higher-level contextual representations. Next is the iterative refinement of task and entity-specific features. Then, the second half of the model begins with a phase transition, where hidden representations align more with the vocabulary space due to specialized model components. Finally, the last layer sharpens the following token distribution by eliminating obsolete features that add noise to the prediction.

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x1.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x2.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x3.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x4.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x5.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/attn_gpt.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/attn_pythia.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/attn_phi.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x6.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x7.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x8.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x9.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x10.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x11.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/mlp_gpt.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/mlp_pythia.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/mlp_phi.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x12.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x13.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x14.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x15.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x16.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x17.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/cos_sim.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/mean_cos_sim.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x18.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/x19.png)

![大型语言模型（LLMs）展现出惊人的鲁棒性，其推理过程究竟经历了哪些阶段？](../../../paper_images/2406.19384/output.png)

[Arxiv](https://arxiv.org/abs/2406.19384)