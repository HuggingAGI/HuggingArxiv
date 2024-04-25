# 概念驱动的大型语言模型（LLM）代理：助力人机协同设计安全准则

发布时间：2024年04月03日

`Agent` `软件工程` `安全工程`

> Concept-Guided LLM Agents for Human-AI Safety Codesign

# 摘要

> 生成性AI在软件工程，尤其是安全工程领域的作用日益凸显，其应用确保软件不会对人造成伤害，这同时也对生成性AI的质量提出了更高要求。单纯依赖大型语言模型（LLM）已无法满足这些高标准。因此，迫切需要开发更先进、更精细的方法来应对软件系统的复杂性和安全挑战。人类必须理解并负责对生成性AI提供的建议，以保障系统安全。本研究提出了一种高效的混合策略，结合LLM进行安全分析和人机协同设计。我们特别开发了一个定制的LLM代理，它结合了提示工程、启发式推理和增强检索生成技术，以解决与预定义安全概念相关的任务，并通过系统模型图进行交互。这一过程通过一系列微决策引导，以保持信息的结构化。此外，我们还提出了一种图的口头化方法，作为系统模型的中间表示，以便更好地促进LLM与图的互动。通过一系列针对安全分析的精选提示和响应对，我们展示了在简化自动驾驶系统用例中应用该方法的实例。

> Generative AI is increasingly important in software engineering, including safety engineering, where its use ensures that software does not cause harm to people. This also leads to high quality requirements for generative AI. Therefore, the simplistic use of Large Language Models (LLMs) alone will not meet these quality demands. It is crucial to develop more advanced and sophisticated approaches that can effectively address the complexities and safety concerns of software systems. Ultimately, humans must understand and take responsibility for the suggestions provided by generative AI to ensure system safety. To this end, we present an efficient, hybrid strategy to leverage LLMs for safety analysis and Human-AI codesign. In particular, we develop a customized LLM agent that uses elements of prompt engineering, heuristic reasoning, and retrieval-augmented generation to solve tasks associated with predefined safety concepts, in interaction with a system model graph. The reasoning is guided by a cascade of micro-decisions that help preserve structured information. We further suggest a graph verbalization which acts as an intermediate representation of the system model to facilitate LLM-graph interactions. Selected pairs of prompts and responses relevant for safety analytics illustrate our method for the use case of a simplified automated driving system.

![概念驱动的大型语言模型（LLM）代理：助力人机协同设计安全准则](../../../paper_images/2404.15317/x1.png)

![概念驱动的大型语言模型（LLM）代理：助力人机协同设计安全准则](../../../paper_images/2404.15317/x2.png)

![概念驱动的大型语言模型（LLM）代理：助力人机协同设计安全准则](../../../paper_images/2404.15317/output.png)

[Arxiv](https://arxiv.org/abs/2404.15317)