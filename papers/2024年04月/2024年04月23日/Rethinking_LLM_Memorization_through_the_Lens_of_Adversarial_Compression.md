# 透过对抗性压缩的透镜，我们重新审视大型语言模型的记忆力。

发布时间：2024年04月23日

`LLM理论` `数据科学`

> Rethinking LLM Memorization through the Lens of Adversarial Compression

# 摘要

> 大型语言模型（LLMs）在海量网络数据集上的训练引发了对数据使用规范的重大疑虑。关键疑问在于，这些模型究竟是简单地“背诵”其训练数据，还是能够像人类一样整合并学习信息。这一问题的答案很大程度上取决于我们如何界定“记忆”。本研究提出了一种新的评估指标——对抗性压缩比率（ACR），用以衡量LLMs的记忆能力。如果训练数据中的某个特定字符串能够通过比该字符串本身更短的提示被唤起，那么这个字符串就被视为已被模型“记忆”。换言之，这些字符串可以通过生成较少令牌的对抗性提示与模型进行“压缩”。我们指出了现有记忆概念的不足，并展示了ACR是如何通过（i）提供一种对抗性的视角来衡量记忆，尤其是在监控遗忘和合规性方面；以及（ii）在合理的计算成本下，为任意字符串提供衡量记忆的灵活性，从而克服这些挑战。这一定义不仅为判断模型所有者是否违反数据使用条款提供了实用工具，也可能成为法律领域的重要工具，为我们审视这类问题提供了新的视角。项目详情：https://locuslab.github.io/acr-memorization。

> Large language models (LLMs) trained on web-scale datasets raise substantial concerns regarding permissible data usage. One major question is whether these models "memorize" all their training data or they integrate many data sources in some way more akin to how a human would learn and synthesize information. The answer hinges, to a large degree, on $\textit{how we define memorization}$. In this work, we propose the Adversarial Compression Ratio (ACR) as a metric for assessing memorization in LLMs -- a given string from the training data is considered memorized if it can be elicited by a prompt shorter than the string itself. In other words, these strings can be "compressed" with the model by computing adversarial prompts of fewer tokens. We outline the limitations of existing notions of memorization and show how the ACR overcomes these challenges by (i) offering an adversarial view to measuring memorization, especially for monitoring unlearning and compliance; and (ii) allowing for the flexibility to measure memorization for arbitrary strings at a reasonably low compute. Our definition serves as a valuable and practical tool for determining when model owners may be violating terms around data usage, providing a potential legal tool and a critical lens through which to address such scenarios. Project page: https://locuslab.github.io/acr-memorization.

[Arxiv](https://arxiv.org/abs/2404.15146)