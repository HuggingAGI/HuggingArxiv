# 大型语言模型中的中文知识修正基准测试

发布时间：2024年09月09日

`LLM应用` `语言处理` `文化研究`

> Benchmarking Chinese Knowledge Rectification in Large Language Models

# 摘要

> 尽管大型语言模型（LLM）在生成内容方面表现出色，但它们也存在幻觉问题，尤其是在处理特定语言和领域时。例如，LLM 在处理中国古代诗歌、谚语或成语时，可能会因缺乏相关知识而生成无意义的信息。为此，我们提出了一种通过知识编辑来纠正 LLM 中中文知识的基准。我们创建了一个新的中文数据集 CKnowEdit，涵盖了古典文本、成语和百度贴吧内容等七种知识类型，以反映中文的独特特点。通过分析这个数据集，我们发现当前 LLM 在掌握中文方面仍面临挑战。同时，我们对现有知识编辑技术的评估表明，在纠正中文知识方面仍有很大的提升空间。代码和数据集已公开，详见 https://github.com/zjunlp/EasyEdit。

> While Large Language Models (LLMs) exhibit remarkable generative capabilities, they are not without flaws, particularly in the form of hallucinations. This issue is even more pronounced when LLMs are applied to specific languages and domains. For example, LLMs may generate nonsense information when handling Chinese ancient poetry, proverbs, or idioms, owing to the lack of specific knowledge. To this end, this paper introduces a benchmark for rectifying Chinese knowledge in LLMs via knowledge editing. Specifically, we introduce a new Chinese dataset, CKnowEdit, by collecting seven type of knowledge from various sources, including classical texts, idioms, and content from Baidu Tieba Ruozhiba, thereby accounting for the unique polyphony, antithesis, and logical constructs inherent in the Chinese language. Through the analysis of this dataset, we uncover the challenges faced by current LLMs in mastering Chinese. Furthermore, our evaluation of state-of-the-art knowledge editing techniques on this dataset unveil the substantial scope for advancement in the rectification of Chinese knowledge. Code and dataset are available at https://github.com/zjunlp/EasyEdit.

[Arxiv](https://arxiv.org/abs/2409.05806)