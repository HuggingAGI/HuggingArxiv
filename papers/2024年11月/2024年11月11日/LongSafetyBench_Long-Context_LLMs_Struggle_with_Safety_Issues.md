# LongSafetyBench：长上下文的大型语言模型在安全问题上举步维艰。

发布时间：2024年11月11日

`LLM应用` `语言模型` `安全性评估`

> LongSafetyBench: Long-Context LLMs Struggle with Safety Issues

# 摘要

> 随着大型语言模型（LLM）的发展，这些模型的序列长度不断增加，使得长上下文语言模型受到了极大的关注。然而，对这些模型的评估主要局限于它们的能力，缺乏对其安全性的研究。现有的工作，如 ManyShotJailbreak，在一定程度上表明长上下文语言模型可能存在安全问题。然而，所使用的方法有限且缺乏全面性。为此，我们引入了	extbf{LongSafetyBench}，这是第一个旨在客观和全面评估长上下文模型安全性的基准。LongSafetyBench 由 10 个任务类别组成，平均长度为 41,889 个单词。在 LongSafetyBench 上对 8 个长上下文语言模型进行测试后，我们发现现有的模型普遍表现出安全性不足的能力。大多数主流长上下文 LLM 的安全响应比例低于 50％。此外，模型在长上下文场景中的安全性能并不总是与短上下文场景中的一致。进一步的调查显示，长上下文模型往往会忽略长文本中的有害内容。我们还提出了一个简单而有效的解决方案，使开源模型能够实现与顶级闭源模型相当的性能。我们相信 LongSafetyBench 可以作为评估长上下文语言模型安全能力的有价值的基准。我们希望我们的工作能够鼓励更广泛的社区关注长上下文模型的安全性，并为提高长上下文 LLM 的安全性的解决方案的发展做出贡献。

> With the development of large language models (LLMs), the sequence length of these models continues to increase, drawing significant attention to long-context language models. However, the evaluation of these models has been primarily limited to their capabilities, with a lack of research focusing on their safety. Existing work, such as ManyShotJailbreak, has to some extent demonstrated that long-context language models can exhibit safety concerns. However, the methods used are limited and lack comprehensiveness. In response, we introduce \textbf{LongSafetyBench}, the first benchmark designed to objectively and comprehensively evaluate the safety of long-context models. LongSafetyBench consists of 10 task categories, with an average length of 41,889 words. After testing eight long-context language models on LongSafetyBench, we found that existing models generally exhibit insufficient safety capabilities. The proportion of safe responses from most mainstream long-context LLMs is below 50\%. Moreover, models' safety performance in long-context scenarios does not always align with that in short-context scenarios. Further investigation revealed that long-context models tend to overlook harmful content within lengthy texts. We also proposed a simple yet effective solution, allowing open-source models to achieve performance comparable to that of top-tier closed-source models. We believe that LongSafetyBench can serve as a valuable benchmark for evaluating the safety capabilities of long-context language models. We hope that our work will encourage the broader community to pay attention to the safety of long-context models and contribute to the development of solutions to improve the safety of long-context LLMs.

[Arxiv](https://arxiv.org/abs/2411.06899)