# [CLEVR-POC 是一个专注于在局部可观察环境下的高强度视觉推理问答研究，旨在探究在不完全信息条件下进行复杂视觉推理的能力。]

发布时间：2024年03月05日

`Agent`

> CLEVR-POC: Reasoning-Intensive Visual Question Answering in Partially Observable Environments

> 当前AI研究热点在于整合学习与推理能力，但鲜有研究关注如何利用已有的背景知识针对部分可见场景进行推理并解答相关问题，而实际上，人们常借助这类知识剔除不合理选项以推测视觉问题的答案。此类知识多以物体约束的形式存在，且往往极具领域或环境特异性。为推动这一领域的进展，我们提出了一个创新性的基准——CLEVR-POC，它专注于在受特定约束的、部分可观察环境中的高强度视觉问答推理。在CLEVR-POC中，要求运用逻辑约束形式的知识去解答对给定局部场景中隐藏对象的问题。比如，在已知所有杯子颜色仅限红绿蓝三色且仅有一只绿色杯子的前提下，若其他所有包括绿色杯子在内的杯子都被观察到，则可以推断出被遮挡杯子必为红色或蓝色。实验证明，预训练的视觉语言模型CLIP及大型语言模型GPT-4在CLEVR-POC上的表现欠佳（分别约为22%和46%），这凸显了设计能有效利用和处理关键环境特定背景知识的高强度推理任务框架的必要性。进一步地，我们的展示揭示了一种结合了类似GPT-4的LLM、视觉感知网络以及形式逻辑推理器的神经符号模型，在CLEVR-POC上的表现尤为出色。

> The integration of learning and reasoning is high on the research agenda in AI. Nevertheless, there is only a little attention to use existing background knowledge for reasoning about partially observed scenes to answer questions about the scene. Yet, we as humans use such knowledge frequently to infer plausible answers to visual questions (by eliminating all inconsistent ones). Such knowledge often comes in the form of constraints about objects and it tends to be highly domain or environment-specific. We contribute a novel benchmark called CLEVR-POC for reasoning-intensive visual question answering (VQA) in partially observable environments under constraints. In CLEVR-POC, knowledge in the form of logical constraints needs to be leveraged to generate plausible answers to questions about a hidden object in a given partial scene. For instance, if one has the knowledge that all cups are colored either red, green or blue and that there is only one green cup, it becomes possible to deduce the color of an occluded cup as either red or blue, provided that all other cups, including the green one, are observed. Through experiments, we observe that the low performance of pre-trained vision language models like CLIP (~ 22%) and a large language model (LLM) like GPT-4 (~ 46%) on CLEVR-POC ascertains the necessity for frameworks that can handle reasoning-intensive tasks where environment-specific background knowledge is available and crucial. Furthermore, our demonstration illustrates that a neuro-symbolic model, which integrates an LLM like GPT-4 with a visual perception network and a formal logical reasoner, exhibits exceptional performance on CLEVR-POC.

[Arxiv](https://arxiv.org/abs/2403.03203)