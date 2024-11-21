# 长上下文语言建模中的困惑度存在哪些问题？

发布时间：2024年10月31日

`LLM应用` `模型评估`

> What is Wrong with Perplexity for Long-context Language Modeling?

# 摘要

> 处理长上下文输入对于大型语言模型（LLMs）在诸如扩展对话、文档摘要和多示例上下文学习等任务而言至关重要。尽管近期的方法拓展了 LLMs 的上下文窗口，并将困惑度（PPL）用作标准评估指标，然而 PPL 在评估长上下文能力时被证实并不可靠。此限制的根本原因尚不明确。在本项工作中，我们针对此问题给出了全面的阐释。我们发现，PPL 因对所有标记取平均而忽略了对长上下文理解至关重要的关键标记，进而掩盖了模型在长上下文场景中的真实表现。为解决这一问题，我们提出了	extbf{LongPPL}，这是一种新的指标，它通过采用长-短上下文对比方法来识别关键标记，从而聚焦于关键标记。我们的实验表明，LongPPL 与各类长上下文基准的性能紧密相关（比如，皮尔逊相关系数为-0.96），在预测准确性上显著优于传统的 PPL。另外，我们引入了	extbf{LongCE}（长上下文交叉熵）损失，这是一种用于微调的重加权策略，优先考虑关键标记，从而在不同的基准测试中实现了持续的改进。总之，这些贡献深入剖析了 PPL 的局限性，并为准确评估和提升 LLMs 的长上下文能力提供了有效的解决方案。代码可在 https://github.com/PKU-ML/LongPPL 获得。

> Handling long-context inputs is crucial for large language models (LLMs) in tasks such as extended conversations, document summarization, and many-shot in-context learning. While recent approaches have extended the context windows of LLMs and employed perplexity (PPL) as a standard evaluation metric, PPL has proven unreliable for assessing long-context capabilities. The underlying cause of this limitation has remained unclear. In this work, we provide a comprehensive explanation for this issue. We find that PPL overlooks key tokens, which are essential for long-context understanding, by averaging across all tokens and thereby obscuring the true performance of models in long-context scenarios. To address this, we propose \textbf{LongPPL}, a novel metric that focuses on key tokens by employing a long-short context contrastive method to identify them. Our experiments demonstrate that LongPPL strongly correlates with performance on various long-context benchmarks (e.g., Pearson correlation of -0.96), significantly outperforming traditional PPL in predictive accuracy. Additionally, we introduce \textbf{LongCE} (Long-context Cross-Entropy) loss, a re-weighting strategy for fine-tuning that prioritizes key tokens, leading to consistent improvements across diverse benchmarks. In summary, these contributions offer deeper insights into the limitations of PPL and present effective solutions for accurately evaluating and enhancing the long-context capabilities of LLMs. Code is available at https://github.com/PKU-ML/LongPPL.

[Arxiv](https://arxiv.org/abs/2410.23771)