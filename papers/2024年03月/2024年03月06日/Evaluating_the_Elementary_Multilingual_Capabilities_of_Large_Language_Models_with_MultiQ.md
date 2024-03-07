# [我们运用 MultiQ 工具，对大型语言模型在处理基础多语言任务时的能力进行深入评估。](https://arxiv.org/abs/2403.03814)

发布时间：2024年03月06日

`LLM应用`

> Evaluating the Elementary Multilingual Capabilities of Large Language Models with MultiQ

> 为满足全球非英语用户的需求，大型语言模型（LLMs）亟需具备多语言服务能力。然而，目前许多LLMs尤其是开源模型，主要面向英语或其他少数资源丰富的语言设计。最近的研究揭示，尽管这些模型设计时有特定使用范围，但在实际应用中，人们已在多种语言环境下对其进行调用。鉴于此，本论文着力探索了顶尖开源LLMs超越预设场景下的基础多语言功能。为了实现这一目标，我们创新推出了名为MultiQ的新一代银标准基准测试，该测试涵盖了137种类型各异的语言，包含27.4k个开放式问题解答测试项。利用MultiQ，我们可以衡量模型对于所给语言的忠诚度（即模型是否能以提示语言作答）及问题回答的准确性。实验结果显示，所有测试的LLMs在部分未预设支持的语言中均能提供忠实且/或准确的回答，多数模型在保持语言忠诚度的同时，其准确率也有所提升。然而，不同模型间的表现差异显著，尤其在一部分语言上，模型回答的准确性和语言一致性都不理想。我们进一步考察了分词处理可能对这一现象产生的影响，发现其中存在的若干相关性有待更深入研究。

> Large language models (LLMs) need to serve everyone, including a global majority of non-English speakers. However, most LLMs today, and open LLMs in particular, are often intended for use in just English (e.g. Llama2, Mistral) or a small handful of high-resource languages (e.g. Mixtral, Qwen). Recent research shows that, despite limits in their intended use, people prompt LLMs in many different languages. Therefore, in this paper, we investigate the basic multilingual capabilities of state-of-the-art open LLMs beyond their intended use. For this purpose, we introduce MultiQ, a new silver standard benchmark for basic open-ended question answering with 27.4k test questions across a typologically diverse set of 137 languages. With MultiQ, we evaluate language fidelity, i.e.\ whether models respond in the prompted language, and question answering accuracy. All LLMs we test respond faithfully and/or accurately for at least some languages beyond their intended use. Most models are more accurate when they respond faithfully. However, differences across models are large, and there is a long tail of languages where models are neither accurate nor faithful. We explore differences in tokenization as a potential explanation for our findings, identifying possible correlations that warrant further investigation.