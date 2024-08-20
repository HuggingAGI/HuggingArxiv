# 在多语言的海洋中寻找针尖：探索多语言大型语言模型在长上下文中的表现

发布时间：2024年08月19日

`LLM应用` `多语言处理` `问答系统`

> Multilingual Needle in a Haystack: Investigating Long-Context Behavior of Multilingual Large Language Models

# 摘要

> 尽管大型语言模型 (LLM) 在多语言查询响应上表现出色，但其处理长篇多语言文本的能力仍待探索。为此，我们设计了 MLNeedle 测试，旨在从多语言干扰文本中检索关键信息，扩展了多语言问答任务的范畴。通过评估四种顶尖 LLM，我们发现模型性能受语言类型和信息位置影响显著，尤其在非英语语系及文本中部时表现最差。此外，尽管某些模型宣称支持长达 8k 令牌的上下文，实际跨语言检索能力却随上下文增长而下降。本研究首次深入探讨了 LLM 在多语言长文本环境下的表现，为未来评估提供了重要参考。

> While recent large language models (LLMs) demonstrate remarkable abilities in responding to queries in diverse languages, their ability to handle long multilingual contexts is unexplored. As such, a systematic evaluation of the long-context capabilities of LLMs in multilingual settings is crucial, specifically in the context of information retrieval. To address this gap, we introduce the MultiLingual Needle-in-a-Haystack (MLNeedle) test, designed to assess a model's ability to retrieve relevant information (the needle) from a collection of multilingual distractor texts (the haystack). This test serves as an extension of the multilingual question-answering task, encompassing both monolingual and cross-lingual retrieval. We evaluate four state-of-the-art LLMs on MLNeedle. Our findings reveal that model performance can vary significantly with language and needle position. Specifically, we observe that model performance is the lowest when the needle is (i) in a language outside the English language family and (ii) located in the middle of the input context. Furthermore, although some models claim a context size of $8k$ tokens or greater, none demonstrate satisfactory cross-lingual retrieval performance as the context length increases. Our analysis provides key insights into the long-context behavior of LLMs in multilingual settings to guide future evaluation protocols. To our knowledge, this is the first study to investigate the multilingual long-context behavior of LLMs.

[Arxiv](https://arxiv.org/abs/2408.10151)