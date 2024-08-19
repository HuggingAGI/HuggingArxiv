# Math-PUMA：通过逐步向上多模态对齐，提升数学推理能力

发布时间：2024年08月16日

`LLM应用` `人工智能`

> Math-PUMA: Progressive Upward Multimodal Alignment to Enhance Mathematical Reasoning

# 摘要

> 多模态大型语言模型 (MLLMs) 在处理文本数学问题时表现优异，但在面对数学图表时却力不从心，这主要是因为它们的训练数据以自然场景图像为主。尽管视觉辅助对人类解决问题大有裨益，MLLMs 在信息从文本转向视觉时却表现不佳，原因在于图像与文本的对齐能力不足。为此，我们引入了 Math-PUMA 方法，专注于渐进式多模态对齐，旨在通过三阶段训练提升 MLLMs 的数学推理能力，特别是关键的对齐阶段。我们首先通过大量文本数学问题强化模型的推理能力，随后构建包含丰富文本与视觉信息的多模态数据集，确保每个问题至少以两种形式呈现。利用下一个标记预测分布的 Kullback-Leibler (KL) 散度进行模态对齐，确保问题解决的一致性。最终，通过高质量多模态数据对 MLLMs 进行指令调优。实验显示，采用 Math-PUMA 训练的 MLLMs 在多个数学推理基准上超越了众多开源模型，显著缩小了不同模态问题呈现时的性能差距。

> Multimodal Large Language Models (MLLMs) excel in solving text-based mathematical problems, but they struggle with mathematical diagrams since they are primarily trained on natural scene images. For humans, visual aids generally enhance problem-solving, but MLLMs perform worse as information shifts from textual to visual modality. This decline is mainly due to their shortcomings in aligning images and text. To tackle aforementioned challenges, we propose Math-PUMA, a methodology focused on Progressive Upward Multimodal Alignment. This approach is designed to improve the mathematical reasoning skills of MLLMs through a three-stage training process, with the second stage being the critical alignment stage. We first enhance the language model's mathematical reasoning capabilities with extensive set of textual mathematical problems. We then construct a multimodal dataset with varying degrees of textual and visual information, creating data pairs by presenting each problem in at least two forms. By leveraging the Kullback-Leibler (KL) divergence of next-token prediction distributions to align visual and textual modalities, consistent problem-solving abilities are ensured. Finally, we utilize multimodal instruction tuning for MLLMs with high-quality multimodal data. Experimental results on multiple mathematical reasoning benchmarks demonstrate that the MLLMs trained with Math-PUMA surpass most open-source MLLMs. Our approach effectively narrows the performance gap for problems presented in different modalities.

[Arxiv](https://arxiv.org/abs/2408.08640)