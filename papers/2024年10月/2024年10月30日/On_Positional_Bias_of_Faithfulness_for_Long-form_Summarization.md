# 论长文本摘要中忠实度的位置偏差

发布时间：2024年10月30日

`LLM应用` `文本摘要`

> On Positional Bias of Faithfulness for Long-form Summarization

# 摘要

> 大型语言模型（LLMs）在长上下文情境中常常呈现出位置偏差，对输入中部的信息关注不够。我们探究了这种偏差在长篇摘要里的存在状况、其对忠实度的影响以及各类减轻该偏差的技术。为持续评估忠实度，我们先是汇集了一个由八个人工标注的长篇摘要数据集构成的基准，并对忠实度指标展开了元评估。我们指出，基于 LLM 的忠实度指标尽管在全上下文输入时有效，却仍对文档顺序敏感，这意味着存在位置偏差。分析六个数据集中 LLM 生成的摘要，我们发现忠实度呈现“U 形”趋势，即 LLMs 能忠实总结文档的开头和结尾，却忽视中间内容。打乱文档顺序也表明，当重要文档置于输入中间时，模型的忠实度较低。我们发现这种情况部分是因为随着上下文长度变化而转移了焦点：随着上下文增加，摘要的忠实度下降，但超过一定长度后，由于模型聚焦于结尾，忠实度得以提升。最后，我们试验了不同的生成技术以减少位置偏差，发现提示技术能有效将模型注意力引向特定位置，而更复杂的方法改进效果有限。我们的数据和代码可在 https://github.com/meetdavidwan/longformfact 获取。

> Large Language Models (LLMs) often exhibit positional bias in long-context settings, under-attending to information in the middle of inputs. We investigate the presence of this bias in long-form summarization, its impact on faithfulness, and various techniques to mitigate this bias. To consistently evaluate faithfulness, we first compile a benchmark of eight human-annotated long-form summarization datasets and perform a meta-evaluation of faithfulness metrics. We show that LLM-based faithfulness metrics, though effective with full-context inputs, remain sensitive to document order, indicating positional bias. Analyzing LLM-generated summaries across six datasets, we find a "U-shaped" trend in faithfulness, where LLMs faithfully summarize the beginning and end of documents but neglect middle content. Perturbing document order similarly reveals models are less faithful when important documents are placed in the middle of the input. We find that this behavior is partly due to shifting focus with context length: as context increases, summaries become less faithful, but beyond a certain length, faithfulness improves as the model focuses on the end. Finally, we experiment with different generation techniques to reduce positional bias and find that prompting techniques effectively direct model attention to specific positions, whereas more sophisticated approaches offer limited improvements. Our data and code are available in https://github.com/meetdavidwan/longformfact.

[Arxiv](https://arxiv.org/abs/2410.23609)