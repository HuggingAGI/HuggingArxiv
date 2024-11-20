# SymDPO：借助符号演示直接偏好优化来增强大型多模态模型的上下文学习能力

发布时间：2024年11月17日

`LLM应用` `多模态` `语言模型`

> SymDPO: Boosting In-Context Learning of Large Multimodal Models with Symbol Demonstration Direct Preference Optimization

# 摘要

> 随着语言模型持续发展壮大，大型语言模型（LLMs）在上下文学习（ICL）领域展现出崭新的能力，能够凭借添加一些作为上下文的示例（ICDs）来解决语言任务。受此启发，研究人员将相关技术加以拓展，开发出具备ICL能力的大型多模态模型（LMMs）。然而，现有的LMMs存在一个关键问题：它们往往难以有效利用多模态示例中的视觉上下文，只是单纯遵循文本模式。这意味着LMMs在多模态示例与模型输出之间未能实现有效对齐。为解决这一难题，我们提出了符号示例直接偏好优化（SymDPO）。具体而言，SymDPO意在打破构建多模态示例的传统模式，通过在实例中用随机符号替代文本答案，迫使模型仔细领会示例图像，并在图像与符号之间建立联系，从而正确回答问题。我们在多个基准测试中验证了该方法的有效性，结果表明借助SymDPO，LMMs能够更有效地理解示例中的多模态上下文，并运用这些知识更好地回答问题。

> As language models continue to scale, Large Language Models (LLMs) have exhibited emerging capabilities in In-Context Learning (ICL), enabling them to solve language tasks by prefixing a few in-context demonstrations (ICDs) as context. Inspired by these advancements, researchers have extended these techniques to develop Large Multimodal Models (LMMs) with ICL capabilities. However, existing LMMs face a critical issue: they often fail to effectively leverage the visual context in multimodal demonstrations and instead simply follow textual patterns. This indicates that LMMs do not achieve effective alignment between multimodal demonstrations and model outputs. To address this problem, we propose Symbol Demonstration Direct Preference Optimization (SymDPO). Specifically, SymDPO aims to break the traditional paradigm of constructing multimodal demonstrations by using random symbols to replace text answers within instances. This forces the model to carefully understand the demonstration images and establish a relationship between the images and the symbols to answer questions correctly. We validate the effectiveness of this method on multiple benchmarks, demonstrating that with SymDPO, LMMs can more effectively understand the multimodal context within examples and utilize this knowledge to answer questions better.

[Arxiv](https://arxiv.org/abs/2411.11909)