# 量化对多语言LLM的影响如何？

发布时间：2024年07月03日

`LLM应用` `人工智能`

> How Does Quantization Affect Multilingual LLMs?

# 摘要

> 量化技术常用于提升大型语言模型的推理速度和部署效率。尽管已有研究探讨了量化对英语任务的影响，但跨语言的量化效应尚未被深入研究。我们针对多语言LLM进行了详尽分析，特别关注其在不同语言和规模下的表现。通过自动基准测试、LLM-as-a-Judge方法及人类评估，我们发现：（1）量化在人类评估中显示出明显负面影响，自动指标低估了其损害程度；（2）不同语言对量化的敏感度各异，非拉丁文字语言受影响尤为严重；（3）数学推理等复杂任务受量化影响最大。鉴于低计算模型在全球NLP技术推广中的重要性，我们的研究强调了多语言性能作为高效模型评估关键标准的重要性。

> Quantization techniques are widely used to improve inference speed and deployment of large language models. While a wide body of work examines the impact of quantized LLMs on English tasks, none have examined the effect of quantization across languages. We conduct a thorough analysis of quantized multilingual LLMs, focusing on their performance across languages and at varying scales. We use automatic benchmarks, LLM-as-a-Judge methods, and human evaluation, finding that (1) harmful effects of quantization are apparent in human evaluation, and automatic metrics severely underestimate the detriment: a 1.7% average drop in Japanese across automatic tasks corresponds to a 16.0% drop reported by human evaluators on realistic prompts; (2) languages are disparately affected by quantization, with non-Latin script languages impacted worst; and (3) challenging tasks such as mathematical reasoning degrade fastest. As the ability to serve low-compute models is critical for wide global adoption of NLP technologies, our results urge consideration of multilingual performance as a key evaluation criterion for efficient models.

[Arxiv](https://arxiv.org/abs/2407.03211)