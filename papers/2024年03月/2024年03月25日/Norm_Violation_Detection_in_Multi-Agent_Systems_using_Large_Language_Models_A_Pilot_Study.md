# 利用大型语言模型开展多智能体系统中的规范违反检测：一项探索性研究。

发布时间：2024年03月25日

`分类：Agent` `社会规范` `多智能体系统`

> Norm Violation Detection in Multi-Agent Systems using Large Language Models: A Pilot Study

# 摘要

> 规范构成了社会结构的核心，它定义了社会预期的行为准则。在多智能体系统（MAS）中，智能体们被赋予了社会性能力，包括对规范和信任的推理。规范一直是规范性多智能体系统研究社区的热点，涉及规范的形成、违规检测和处罚等议题。尽管如此，现有研究存在局限，如局限于特定领域、规范的表达方式多样且缺乏统一标准，以及符号推理机制在可扩展性和鲁棒性上的不足。与此相对，大型语言模型（LLMs）为我们在多样化的社会情境中探索和推理规范提供了新的可能性。本文旨在评估LLMs在规范违规检测方面的能力。我们利用家庭环境中80个故事的模拟数据，探究了10种不同规范的遵守情况。通过三名人类评估员对每个故事的独立评估，我们确定了基准真实情况，并将其与三个著名LLM模型（Llama 2 7B、Mixtral 7B和ChatGPT-4）的检测结果进行了比较。研究结果显示，ChatGPT-4在规范违规检测方面展现出潜力，而Mixtral则稍显落后。同时，我们也发现了这些模型在某些方面的不足，并对未来研究方向提出了见解。

> Norms are an important component of the social fabric of society by prescribing expected behaviour. In Multi-Agent Systems (MAS), agents interacting within a society are equipped to possess social capabilities such as reasoning about norms and trust. Norms have long been of interest within the Normative Multi-Agent Systems community with researchers studying topics such as norm emergence, norm violation detection and sanctioning. However, these studies have some limitations: they are often limited to simple domains, norms have been represented using a variety of representations with no standard approach emerging, and the symbolic reasoning mechanisms generally used may suffer from a lack of extensibility and robustness. In contrast, Large Language Models (LLMs) offer opportunities to discover and reason about norms across a large range of social situations. This paper evaluates the capability of LLMs to detecting norm violations. Based on simulated data from 80 stories in a household context, with varying complexities, we investigated whether 10 norms are violated. For our evaluations we first obtained the ground truth from three human evaluators for each story. Then, the majority result was compared against the results from three well-known LLM models (Llama 2 7B, Mixtral 7B and ChatGPT-4). Our results show the promise of ChatGPT-4 for detecting norm violations, with Mixtral some distance behind. Also, we identify areas where these models perform poorly and discuss implications for future work.

![利用大型语言模型开展多智能体系统中的规范违反检测：一项探索性研究。](../../../paper_images/2403.16517/freq_graph.png)

![利用大型语言模型开展多智能体系统中的规范违反检测：一项探索性研究。](../../../paper_images/2403.16517/confusion_matrix.png)

![利用大型语言模型开展多智能体系统中的规范违反检测：一项探索性研究。](../../../paper_images/2403.16517/chat_gpt.png)

[Arxiv](https://arxiv.org/abs/2403.16517)