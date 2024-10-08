# 差异性变换器

发布时间：2024年10月07日

`LLM理论` `人工智能`

> Differential Transformer

# 摘要

> Transformer 常过度关注无关信息。我们提出的 Diff Transformer 则能聚焦相关上下文，同时过滤噪声。其核心在于差分注意力机制，通过计算两组 softmax 注意力图的差异来评分，有效减少噪声，形成稀疏注意力模式。实验显示，无论模型规模或训练数据如何扩展，Diff Transformer 均优于传统 Transformer。更引人注目的是，它在长文本建模、关键信息提取、幻觉抑制等实际应用中表现出色。此外，Diff Transformer 在问答和摘要任务中能有效减少幻觉现象。对于上下文学习，它不仅提升准确性，还显著增强了对输入顺序变化的鲁棒性。这些优势使 Diff Transformer 成为推动大型语言模型发展的有力候选。

> Transformer tends to overallocate attention to irrelevant context. In this work, we introduce Diff Transformer, which amplifies attention to the relevant context while canceling noise. Specifically, the differential attention mechanism calculates attention scores as the difference between two separate softmax attention maps. The subtraction cancels noise, promoting the emergence of sparse attention patterns. Experimental results on language modeling show that Diff Transformer outperforms Transformer in various settings of scaling up model size and training tokens. More intriguingly, it offers notable advantages in practical applications, such as long-context modeling, key information retrieval, hallucination mitigation, in-context learning, and reduction of activation outliers. By being less distracted by irrelevant context, Diff Transformer can mitigate hallucination in question answering and text summarization. For in-context learning, Diff Transformer not only enhances accuracy but is also more robust to order permutation, which was considered as a chronic robustness issue. The results position Diff Transformer as a highly effective and promising architecture to advance large language models.

[Arxiv](https://arxiv.org/abs/2410.05258)