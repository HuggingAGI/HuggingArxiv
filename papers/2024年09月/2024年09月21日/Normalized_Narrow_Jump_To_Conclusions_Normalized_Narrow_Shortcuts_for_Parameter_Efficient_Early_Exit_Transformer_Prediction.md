# 标准化窄捷径：提升 Transformer 预测效率的参数高效早期退出策略

发布时间：2024年09月21日

`LLM理论` `人工智能`

> Normalized Narrow Jump To Conclusions: Normalized Narrow Shortcuts for Parameter Efficient Early Exit Transformer Prediction

# 摘要

> 随着大型变压器语言模型的规模和成本不断攀升，近期研究者们开始探索通过早期隐藏层直接转换至最终表示，以降低推理成本。特别是，通过早期层线性变换跳过预训练变压器，已证实能提升早期推理精度。然而，对于大型模型，这种方法仍显昂贵。为此，我们提出了“窄跳至结论”（NJTC）及“归一化窄跳至结论”（N-NJTC），这两种参数高效方案可将跳过参数减少97%以上。实验表明，N-NJTC在早期阶段表现优于恒等跳过，并为GPT-2-XL、Phi3-Mini及Llama2-7B等模型提供稳定精度，彰显了更高效跳过方法的潜力。

> With the size and cost of large transformer-based language models growing, recently, there has been interest in shortcut casting of early transformer hidden-representations to final-representations for cheaper model inference. In particular, shortcutting pre-trained transformers with linear transformations over early layers has been shown to improve precision in early inference. However, for large language models, even this becomes computationally expensive. In this work, we propose Narrow Jump to Conclusions (NJTC) and Normalized Narrow Jump to Conclusions (N-NJTC) - parameter efficient alternatives to standard linear shortcutting that reduces shortcut parameter count by over 97%. We show that N-NJTC reliably outperforms Identity shortcuts at early stages and offers stable precision from all transformer block levels for GPT-2-XL, Phi3-Mini and Llama2-7B transformer models, demonstrating the viability of more parameter efficient short-cutting approaches.

[Arxiv](https://arxiv.org/abs/2409.14091)