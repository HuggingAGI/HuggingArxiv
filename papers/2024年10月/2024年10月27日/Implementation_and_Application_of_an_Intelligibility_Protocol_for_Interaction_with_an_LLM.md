# LLM 交互可理解性协议的实施与应用

发布时间：2024年10月27日

`Agent`

> Implementation and Application of an Intelligibility Protocol for Interaction with an LLM

# 摘要

> 我们的兴趣在于构建一种交互式系统，让人类专家与机器学习引擎在数据分析任务中相互作用。这在处理科学、环境、医学等领域出现的复杂问题时颇具意义，因为这些问题无法直接用常规的统计或数学建模方法解决。在这类情况下，将人类的专业知识和创造力与现代机器学习通过构建新的数据内部表示来识别模式的能力相结合，或许能为可能的解决方案带来一些启发。本文研究了为代理间交互开发的抽象协议的实现，每个代理都能进行预测和解释。[12]中描述的\PXP 协议受“双向可理解性”概念驱动，通过一对通信有限状态机来指定。虽然这种形式化让作者得以证明该协议的若干属性，但并未给出实现。在此，我们针对其中一个代理以大型语言模型（LLM）充当“生成器”，另一个代理以人类专家或人类专家的代理（如利用人类专业知识编译的数据库）充当“测试器”的情况，弥补了这一不足。我们认为，这些用例将成为上述这类问题广泛适用的交互形式。我们给出了通用实现的算法描述，并在放射学和药物发现这两个不同领域对其使用进行了初步实验。实验结果为该协议以[12]中提出的方式捕获人类与 LLM 之间的单向和双向可理解性的能力提供了早期证据。

> Our interest is in constructing interactive systems involving a human-expert interacting with a machine learning engine on data analysis tasks. This is of relevance when addressing complex problems arising in areas of science, the environment, medicine and so on, which are not immediately amenable to the usual methods of statistical or mathematical modelling. In such situations, it is possible that harnessing human expertise and creativity to modern machine-learning capabilities of identifying patterns by constructing new internal representations of the data may provide some insight to possible solutions. In this paper, we examine the implementation of an abstract protocol developed for interaction between agents, each capable of constructing predictions and explanations. The \PXP protocol, described in [12] is motivated by the notion of ''two-way intelligibility'' and is specified using a pair of communicating finite-state machines. While the formalisation allows the authors to prove several properties about the protocol, no implementation was presented. Here, we address this shortcoming for the case in which one of the agents acts as a ''generator'' using a large language model (LLM) and the other is an agent that acts as a ''tester'' using either a human-expert, or a proxy for a human-expert (for example, a database compiled using human-expertise). We believe these use-cases will be a widely applicable form of interaction for problems of the kind mentioned above. We present an algorithmic description of general-purpose implementation, and conduct preliminary experiments on its use in two different areas (radiology and drug-discovery). The experimental results provide early evidence in support of the protocol's capability of capturing one- and two-way intelligibility in human-LLM in the manner proposed in [12].

[Arxiv](https://arxiv.org/abs/2410.20600)