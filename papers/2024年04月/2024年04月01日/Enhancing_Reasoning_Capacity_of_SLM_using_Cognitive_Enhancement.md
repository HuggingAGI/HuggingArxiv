# 通过认知增强技术，我们能够提升小型语言模型（SLM）的推理能力。

发布时间：2024年04月01日

`LLM应用` `网络安全` `自动化`

> Enhancing Reasoning Capacity of SLM using Cognitive Enhancement

# 摘要

> 大型语言模型（LLMs）正被用于自动化网络安全的各个方面，如网络侦查和数字取证。但在使用这些模型进行网络调查和数字取证时，必须考虑到责任和安全性问题。责任意味着模型能够提供合理的解释和结果，这些可以通过明确的提示来获取。同时，在处理数据时，保护数据的隐私和保密性也是安全考虑的关键。为了解决这一问题，一种方法是在本地环境中处理数据，使用模型的本地版本。由于本地资源有限，如内存和GPU容量，我们通常会选择使用较小的大型语言模型（SLM）。尽管SLM的参数数量大幅减少，但这也导致了性能的显著下降，特别是在需要模型提供推理解释的场景中。本文旨在通过引入人类解决问题时所采用的认知策略，实现对SLM的性能提升，我们称之为“提示式认知增强”。实验结果显示，应用这种增强后，SLM的性能得到了显著提升。我们认为，这项探索性研究为未来利用认知增强技术优化SLM以适应网络安全应用开辟了新的道路。

> Large Language Models (LLMs) have been applied to automate cyber security activities and processes including cyber investigation and digital forensics. However, the use of such models for cyber investigation and digital forensics should address accountability and security considerations. Accountability ensures models have the means to provide explainable reasonings and outcomes. This information can be extracted through explicit prompt requests. For security considerations, it is crucial to address privacy and confidentiality of the involved data during data processing as well. One approach to deal with this consideration is to have the data processed locally using a local instance of the model. Due to limitations of locally available resources, namely memory and GPU capacities, a Smaller Large Language Model (SLM) will typically be used. These SLMs have significantly fewer parameters compared to the LLMs. However, such size reductions have notable performance reduction, especially when tasked to provide reasoning explanations. In this paper, we aim to mitigate performance reduction through the integration of cognitive strategies that humans use for problem-solving. We term this as cognitive enhancement through prompts. Our experiments showed significant improvement gains of the SLMs' performances when such enhancements were applied. We believe that our exploration study paves the way for further investigation into the use of cognitive enhancement to optimize SLM for cyber security applications.

[Arxiv](https://arxiv.org/abs/2404.01135)