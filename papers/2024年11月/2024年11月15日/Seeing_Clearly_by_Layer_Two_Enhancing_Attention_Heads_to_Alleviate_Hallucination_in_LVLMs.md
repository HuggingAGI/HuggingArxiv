# 通过第二层洞察清晰：强化注意力头以缓解 LVLMs 中的幻觉

发布时间：2024年11月15日

`LLM应用` `多模态` `语言模型`

> Seeing Clearly by Layer Two: Enhancing Attention Heads to Alleviate Hallucination in LVLMs

# 摘要

> 在多模态大型语言模型（MLLMs）中，幻觉问题屡见不鲜。虽说图像标记在 MLLMs 的输入序列里占比颇高，但针对图像标记和幻觉之间关系的研究却颇为有限。本文中，我们剖析了模型各层和各头中图像标记的注意力得分分布，揭示出一个饶有趣味且常见的现象：多数幻觉都与图像标记自注意力矩阵中的注意力汇聚模式紧密相连，浅层呈现密集的注意力汇聚，深层则是稀疏的注意力汇聚。我们进一步对不同层的注意力头加以分析，发现图像部分具有高密度注意力汇聚的头在缓解幻觉方面发挥着积极作用。在本文里，我们提出了一种无需训练的方法，名为	extcolor{red}{	extbf{增强注意力头（EAH）}}，旨在强化浅层中图像标记注意力汇聚的收敛性。EAH 识别出浅层中呈现视觉汇聚的注意力头，并提取其注意力矩阵。接着，将此注意力图广播至该层的其他头，从而促使该层更关注图像本身。经过大量实验，EAH 在不同的 MLLMs 和指标上展现出显著的减轻幻觉的性能，证明了其有效性和通用性。

> The hallucination problem in multimodal large language models (MLLMs) remains a common issue. Although image tokens occupy a majority of the input sequence of MLLMs, there is limited research to explore the relationship between image tokens and hallucinations. In this paper, we analyze the distribution of attention scores for image tokens across each layer and head of the model, revealing an intriguing and common phenomenon: most hallucinations are closely linked to the pattern of attention sinks in the self-attention matrix of image tokens, where shallow layers exhibit dense attention sinks and deeper layers show sparse attention sinks. We further analyze the attention heads of different layers and find that heads with high-density attention sink in the image part play a positive role in alleviating hallucinations. In this paper, we propose a training-free method named \textcolor{red}{\textbf{E}}nhancing \textcolor{red}{\textbf{A}}ttention \textcolor{red}{\textbf{H}}eads (EAH), an approach designed to enhance the convergence of image tokens attention sinks in the shallow layers. EAH identifies the attention head that shows the vision sink in a shallow layer and extracts its attention matrix. This attention map is then broadcast to other heads in the layer, thereby strengthening the layer to pay more attention to the image itself. With extensive experiments, EAH shows significant hallucination-mitigating performance on different MLLMs and metrics, proving its effectiveness and generality.

[Arxiv](https://arxiv.org/abs/2411.09968)