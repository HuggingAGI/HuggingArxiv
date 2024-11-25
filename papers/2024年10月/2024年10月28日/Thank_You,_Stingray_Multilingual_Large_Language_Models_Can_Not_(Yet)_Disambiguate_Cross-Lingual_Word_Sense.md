# 感谢黄貂鱼：多语言大型语言模型目前还无法消除跨语言词义的歧义。

发布时间：2024年10月28日

`LLM应用` `语言模型` `跨语言语义`

> Thank You, Stingray: Multilingual Large Language Models Can Not (Yet) Disambiguate Cross-Lingual Word Sense

# 摘要

> 多语言大型语言模型（LLMs）已备受关注，但其在英语之外的可靠性令人担忧。本研究引入用于跨语言语义消歧的新基准 StingrayBench，填补了跨语言语义评估的空白。文中，我们以假朋友（即在两种语言中拼写相似但含义迥异的词）为例，指出 LLMs 在跨语言语义消歧方面的局限性。我们收集了四组语言对中的假朋友，分别是印尼语 - 马来语、印尼语 - 他加禄语、中文 - 日语和英语 - 德语，并让 LLMs 在语境中对其加以区分。通过对各类模型的分析，我们发现它们往往偏向资源更丰富的语言。我们还基于该基准提出了量化跨语言语义偏差和理解的新指标。我们的工作有助于开发更丰富多元、更具包容性的语言模型，为广大多语言群体提供更公平的服务。

> Multilingual large language models (LLMs) have gained prominence, but concerns arise regarding their reliability beyond English. This study addresses the gap in cross-lingual semantic evaluation by introducing a novel benchmark for cross-lingual sense disambiguation, StingrayBench. In this paper, we demonstrate using false friends -- words that are orthographically similar but have completely different meanings in two languages -- as a possible approach to pinpoint the limitation of cross-lingual sense disambiguation in LLMs. We collect false friends in four language pairs, namely Indonesian-Malay, Indonesian-Tagalog, Chinese-Japanese, and English-German; and challenge LLMs to distinguish the use of them in context. In our analysis of various models, we observe they tend to be biased toward higher-resource languages. We also propose new metrics for quantifying the cross-lingual sense bias and comprehension based on our benchmark. Our work contributes to developing more diverse and inclusive language modeling, promoting fairer access for the wider multilingual community.

[Arxiv](https://arxiv.org/abs/2410.21573)