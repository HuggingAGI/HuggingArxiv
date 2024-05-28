# 探究并引导大型语言模型的道德方向

发布时间：2024年05月27日

`LLM理论

理由：这篇论文主要关注大型语言模型（LLMs）的伦理问题，并进行了深入的道德比较分析。它探讨了不同类型的LLMs在面对伦理难题时的表现，并提出了一种技术来干预模型的道德判断。这些内容更多地涉及LLMs的理论和内部机制，而不是它们的应用或特定的Agent或RAG框架。因此，将其归类为LLM理论是合适的。` `自动化`

> Exploring and steering the moral compass of Large Language Models

# 摘要

> 大型语言模型（LLMs）在推动自动化和决策制定方面扮演着关键角色，同时也引发了伦理上的重大关切。本研究对顶尖LLMs进行了深入的道德比较分析。我们让多个前沿模型面对伦理难题，发现专有模型多持功利主义立场，而开放权重模型则更倾向于基于价值观的伦理。此外，通过道德基础问卷测试，除Llama 2外，所有模型均表现出明显的自由主义倾向。为了干预这些模型的道德判断，我们创新性地采用了相似性特定激活引导技术，成功引导模型偏向不同的伦理学派。这些发现揭示了已部署LLMs中常被忽略的伦理层面。

> Large Language Models (LLMs) have become central to advancing automation and decision-making across various sectors, raising significant ethical questions. This study proposes a comprehensive comparative analysis of the most advanced LLMs to assess their moral profiles. We subjected several state-of-the-art models to a selection of ethical dilemmas and found that all the proprietary ones are mostly utilitarian and all of the open-weights ones align mostly with values-based ethics. Furthermore, when using the Moral Foundations Questionnaire, all models we probed - except for Llama 2- displayed a strong liberal bias. Lastly, in order to causally intervene in one of the studied models, we propose a novel similarity-specific activation steering technique. Using this method, we were able to reliably steer the model's moral compass to different ethical schools. All of these results showcase that there is an ethical dimension in already deployed LLMs, an aspect that is generally overlooked.

![探究并引导大型语言模型的道德方向](../../../paper_images/2405.17345/x1.png)

![探究并引导大型语言模型的道德方向](../../../paper_images/2405.17345/x2.png)

![探究并引导大型语言模型的道德方向](../../../paper_images/2405.17345/x3.png)

![探究并引导大型语言模型的道德方向](../../../paper_images/2405.17345/x4.png)

![探究并引导大型语言模型的道德方向](../../../paper_images/2405.17345/x5.png)

[Arxiv](https://arxiv.org/abs/2405.17345)