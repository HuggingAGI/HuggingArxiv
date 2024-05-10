# 大型语言模型的安全性问题亟待解决，我们致力于减轻其夸大风险，以确保技术的稳健发展。

发布时间：2024年05月08日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在安全性和实用性之间的平衡问题，特别是关注了“过度安全”问题，即模型对危险提示的过度反应。通过使用XSTest数据集和不同类型的提示（交互式、上下文和少量提示），研究者们分析了Llama2、Gemma Command R+和Phi-3等模型的决策边界，并提出了一种多重提示策略来减少模型的过度安全行为。这种方法旨在使LLMs既能识别并拒绝危险提示，同时保持其帮助性。因此，这篇论文属于LLM应用类别，因为它关注的是LLMs在实际应用中的安全性和有效性问题。` `人工智能安全`

> Mitigating Exaggerated Safety in Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的流行，确保模型既安全又实用变得至关重要。我们面临的挑战是让LLMs既能识别并拒绝危险提示，又不失其助人之能。所谓的“过度安全”问题揭示了这一挑战的复杂性。为了减少这种过度反应——其中有26.1%的安全提示被误判为危险并被拒绝——我们采用了XSTest数据集的提示，以及交互式、上下文和少量提示，来探索Llama2、Gemma Command R+和Phi-3等LLMs的决策边界。研究发现，少量提示最适合Llama2，交互式提示最适合Gemma，而上下文提示最适合Command R+和Phi-3。通过综合运用这些提示策略，我们成功将所有LLMs的过度安全行为降低了92.9%。我们的研究提出了一种多重提示策略，以解锁LLMs的决策过程，使它们能够在拒绝不安全提示和保持帮助性之间巧妙地找到平衡。

> As the popularity of Large Language Models (LLMs) grow, combining model safety with utility becomes increasingly important. The challenge is making sure that LLMs can recognize and decline dangerous prompts without sacrificing their ability to be helpful. The problem of "exaggerated safety" demonstrates how difficult this can be. To reduce excessive safety behaviours -- which was discovered to be 26.1% of safe prompts being misclassified as dangerous and refused -- we use a combination of XSTest dataset prompts as well as interactive, contextual, and few-shot prompting to examine the decision bounds of LLMs such as Llama2, Gemma Command R+, and Phi-3. We find that few-shot prompting works best for Llama2, interactive prompting works best Gemma, and contextual prompting works best for Command R+ and Phi-3. Using a combination of these prompting strategies, we are able to mitigate exaggerated safety behaviors by an overall 92.9% across all LLMs. Our work presents a multiple prompting strategies to jailbreak LLMs' decision-making processes, allowing them to navigate the tight line between refusing unsafe prompts and remaining helpful.

![大型语言模型的安全性问题亟待解决，我们致力于减轻其夸大风险，以确保技术的稳健发展。](../../../paper_images/2405.05418/llama2-ex.png)

[Arxiv](https://arxiv.org/abs/2405.05418)