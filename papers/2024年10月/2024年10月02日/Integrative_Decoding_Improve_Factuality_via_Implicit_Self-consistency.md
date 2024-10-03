# 综合解码：借助隐式自我一致性提升事实准确性

发布时间：2024年10月02日

`LLM理论` `人工智能`

> Integrative Decoding: Improve Factuality via Implicit Self-consistency

# 摘要

> 自一致性方法通过多次采样并选择最一致的输出来显著提升大型语言模型的实际准确性。然而，现有方法对任务格式要求严格，限制了其应用范围。本文介绍的综合解码（ID）旨在释放自一致性在开放式生成任务中的潜力。ID通过构建包含先前采样响应的输入集，并同时处理这些输入，在每个解码步骤中聚合预测结果来选择下一个标记。这种方法巧妙地融入了自一致性。实验表明，ID在多个语言模型中持续提升事实性，尤其在TruthfulQA、Biographies和LongFact基准上表现突出。随着采样次数增加，性能提升更为显著，显示了ID在重复采样中的扩展潜力。

> Self-consistency-based approaches, which involve repeatedly sampling multiple outputs and selecting the most consistent one as the final response, prove to be remarkably effective in improving the factual accuracy of large language models. Nonetheless, existing methods usually have strict constraints on the task format, largely limiting their applicability. In this paper, we present Integrative Decoding (ID), to unlock the potential of self-consistency in open-ended generation tasks. ID operates by constructing a set of inputs, each prepended with a previously sampled response, and then processes them concurrently, with the next token being selected by aggregating of all their corresponding predictions at each decoding step. In essence, this simple approach implicitly incorporates self-consistency in the decoding objective. Extensive evaluation shows that ID consistently enhances factuality over a wide range of language models, with substantial improvements on the TruthfulQA (+11.2%), Biographies (+15.4%) and LongFact (+8.5%) benchmarks. The performance gains amplify progressively as the number of sampled responses increases, indicating the potential of ID to scale up with repeated sampling.

[Arxiv](https://arxiv.org/abs/2410.01556)