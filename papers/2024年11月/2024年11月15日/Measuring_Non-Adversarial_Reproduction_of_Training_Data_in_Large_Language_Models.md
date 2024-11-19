# 对大型语言模型中训练数据的非对抗性重现进行测量

发布时间：2024年11月15日

`LLM应用` `语言模型` `数据安全`

> Measuring Non-Adversarial Reproduction of Training Data in Large Language Models

# 摘要

> 大型语言模型会记住部分训练数据。记住短片段和事实，这对于回答世界相关问题以及流畅运用任何语言是必需的。不过，模型也被证实，在受到有意图的对手提示时，会重现长段的逐字记忆文本序列。在本项工作中，我们探究了一种称为非对抗性重现的中间记忆情形，在此情形下，我们量化了模型响应与预训练数据在应对自然和良性提示时的重叠情况。对于各类无害的提示类别（比如，写一封信或者一个教程），我们发现，流行的对话语言模型所生成的文本输出中，多达 15%与互联网上的片段重合。在最糟糕的情况下，我们发现生成的内容 100%都能在网上精确找到。对于相同的任务，我们发现人类编写的文本与互联网数据的重合度要低得多。我们进一步研究提示策略能否缩小模型与人类之间的这种重现差距。虽然恰当的提示平均而言能够减少非对抗性重现，但我们发现，要减轻训练数据在最坏情况下的重现，需要更强有力的防御手段——哪怕是对于良性交互。

> Large language models memorize parts of their training data. Memorizing short snippets and facts is required to answer questions about the world and to be fluent in any language. But models have also been shown to reproduce long verbatim sequences of memorized text when prompted by a motivated adversary. In this work, we investigate an intermediate regime of memorization that we call non-adversarial reproduction, where we quantify the overlap between model responses and pretraining data when responding to natural and benign prompts. For a variety of innocuous prompt categories (e.g., writing a letter or a tutorial), we show that up to 15% of the text output by popular conversational language models overlaps with snippets from the Internet. In worst cases, we find generations where 100% of the content can be found exactly online. For the same tasks, we find that human-written text has far less overlap with Internet data. We further study whether prompting strategies can close this reproduction gap between models and humans. While appropriate prompting can reduce non-adversarial reproduction on average, we find that mitigating worst-case reproduction of training data requires stronger defenses -- even for benign interactions.

[Arxiv](https://arxiv.org/abs/2411.10242)