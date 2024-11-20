# 大型预训练 Transformer 模型基于混合高斯先验的幅度剪枝

发布时间：2024年11月01日

`LLM应用` `人工智能`

> Magnitude Pruning of Large Pretrained Transformer Models with a Mixture Gaussian Prior

# 摘要

> 大型预训练的 Transformer 模型以其在自然语言处理（NLP）领域的卓越表现，给现代 AI 应用带来了革命性的变化。然而，其庞大的参数数量给实际应用部署带来难题。为应对此，研究人员常依据参数的大小或灵敏度来删减参数以缩小模型规模。此前的研究已指出幅度修剪的局限性，尤其在现代 NLP 任务的迁移学习情境中。在本文里，我们推出一种新的基于幅度的修剪算法，名为混合高斯先验修剪（MGPP），它运用混合高斯先验进行正则化。MGPP 在混合高斯先验的引导下，修剪无表现力的权重，以保留模型的表达能力。通过对包括自然语言理解、问答和自然语言生成等各类 NLP 任务的广泛评估，证明 MGPP 优于现有的修剪方法，特别是在高稀疏度的设定中。另外，我们为稀疏 Transformer 的一致性给出了理论依据，揭示了所提修剪方法的有效性。

> Large pretrained transformer models have revolutionized modern AI applications with their state-of-the-art performance in natural language processing (NLP). However, their substantial parameter count poses challenges for real-world deployment. To address this, researchers often reduce model size by pruning parameters based on their magnitude or sensitivity. Previous research has demonstrated the limitations of magnitude pruning, especially in the context of transfer learning for modern NLP tasks. In this paper, we introduce a new magnitude-based pruning algorithm called mixture Gaussian prior pruning (MGPP), which employs a mixture Gaussian prior for regularization. MGPP prunes non-expressive weights under the guidance of the mixture Gaussian prior, aiming to retain the model's expressive capability. Extensive evaluations across various NLP tasks, including natural language understanding, question answering, and natural language generation, demonstrate the superiority of MGPP over existing pruning methods, particularly in high sparsity settings. Additionally, we provide a theoretical justification for the consistency of the sparse transformer, shedding light on the effectiveness of the proposed pruning method.

[Arxiv](https://arxiv.org/abs/2411.00969)