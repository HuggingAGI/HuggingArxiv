# 人类动作指令的调整

发布时间：2024年11月25日

`LLM应用` `行为预测`

> Human Motion Instruction Tuning

# 摘要

> 这篇论文呈现了 LLaMo（大型语言和人类动作助手），这是用于人类动作指令调优的多模态框架。和传统把非语言输入（像视频或动作序列）转化为语言标记的指令调优方式不同，LLaMo 在指令调优时保留了原生形式的动作。此方法留存了在标记化时常常丢失的动作特有细节，进而提升了模型解读复杂人类行为的能力。通过对视频、动作数据和文本输入的同步处理，LLaMo 达成了灵活且以人为本的分析。在涵盖人类行为和专业活动等高复杂度领域的实验评估显示，LLaMo 能有效获取特定领域的知识，增强在动作密集场景中的理解和预测。我们期望 LLaMo 能为未来具有广泛应用的多模态 AI 系统奠定基础，从体育分析到行为预测。我们的代码和模型在项目网站上有：https://github.com/ILGLJ/LLaMo。

> This paper presents LLaMo (Large Language and Human Motion Assistant), a multimodal framework for human motion instruction tuning. In contrast to conventional instruction-tuning approaches that convert non-linguistic inputs, such as video or motion sequences, into language tokens, LLaMo retains motion in its native form for instruction tuning. This method preserves motion-specific details that are often diminished in tokenization, thereby improving the model's ability to interpret complex human behaviors. By processing both video and motion data alongside textual inputs, LLaMo enables a flexible, human-centric analysis. Experimental evaluations across high-complexity domains, including human behaviors and professional activities, indicate that LLaMo effectively captures domain-specific knowledge, enhancing comprehension and prediction in motion-intensive scenarios. We hope LLaMo offers a foundation for future multimodal AI systems with broad applications, from sports analytics to behavioral prediction. Our code and models are available on the project website: https://github.com/ILGLJ/LLaMo.

[Arxiv](https://arxiv.org/abs/2411.16805)