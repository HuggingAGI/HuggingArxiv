# MacBehaviour：专为大型语言模型行为实验设计的R包，旨在深入探索语言模型的行为模式与实验应用。

发布时间：2024年05月13日

`RAG

理由：这篇论文介绍了一个名为“MacBehaviour”的R包，它专门设计用于与大型语言模型（LLMs）交互，以简化LLMs行为实验流程。这个包的功能包括实验设计、模型行为操控、响应记录等，这些都是为了研究和分析LLMs的行为。因此，它属于RAG（Research and Analysis of Generative models）分类，即生成模型的研究和分析工具。虽然它也涉及到LLM的应用，但主要焦点是提供一个工具来研究这些模型的行为，而不是直接应用LLM到某个特定领域。` `机器行为研究` `语言模型交互`

> MacBehaviour: An R package for behavioural experimentation on large language models

# 摘要

> 随着对大型语言模型（LLMs）及其聊天机器人行为研究的兴趣日益浓厚，我们开发了“MacBehaviour”R包，旨在与60多种语言模型交互，简化LLMs行为实验流程。该包提供了一系列功能，涵盖实验设计、刺激展示、模型行为操控、响应记录和令牌概率计算。为了验证“MacBehaviour”的实用性，我们针对GPT-3.5、Llama-2 7B和Vicuna-1.5 13B三个模型进行了实验，成功复制了声音性别关联现象，显示出LLMs具有人类般的性别推断倾向。简而言之，“MacBehaviour”是一个专为机器行为研究设计的R包，以其友好的用户界面和全面的功能，简化了实验流程，提高了标准化水平。

> There has been increasing interest in investigating the behaviours of large language models (LLMs) and LLM-powered chatbots by treating an LLM as a participant in a psychological experiment. We therefore developed an R package called "MacBehaviour" that aims to interact with more than 60 language models in one package (e.g., OpenAI's GPT family, the Claude family, Gemini, Llama family, and open-source models) and streamline the experimental process of LLMs behaviour experiments. The package offers a comprehensive set of functions designed for LLM experiments, covering experiment design, stimuli presentation, model behaviour manipulation, logging response and token probability. To demonstrate the utility and effectiveness of "MacBehaviour," we conducted three validation experiments on three LLMs (GPT-3.5, Llama-2 7B, and Vicuna-1.5 13B) to replicate sound-gender association in LLMs. The results consistently showed that they exhibit human-like tendencies to infer gender from novel personal names based on their phonology, as previously demonstrated (Cai et al., 2023). In summary, "MacBehaviour" is an R package for machine behaviour studies which offers a user-friendly interface and comprehensive features to simplify and standardize the experimental process.

[Arxiv](https://arxiv.org/abs/2405.07495)