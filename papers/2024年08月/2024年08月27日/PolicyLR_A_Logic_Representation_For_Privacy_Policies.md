# PolicyLR：隐私政策的逻辑表达

发布时间：2024年08月27日

`LLM应用` `隐私保护` `法律合规`

> PolicyLR: A Logic Representation For Privacy Policies

# 摘要

> 在线生态系统中，隐私政策至关重要，它们定义了服务如何处理用户数据并遵守法规。然而，其复杂性和频繁更新常使利益相关者难以理解和分析。当前的自动化分析方法虽利用自然语言处理，但多聚焦于单一任务，未能全面理解政策上下文。为此，我们提出了PolicyLR，一种新范式，提供隐私政策的全面机器可读表示，旨在成为多任务的一体化解决方案。PolicyLR通过原子公式的估值，将隐私政策转换为机器可读格式，便于形式化定义合规性和一致性等任务。我们开发的编译器利用大型语言模型，将非结构化政策文本转换为该格式，通过两阶段翻译和蕴含过程，全面考虑政策上下文，推断复杂公式。该模型设计可解释，且基于政策段落，提高了透明度。我们通过ToS;DR数据集评估编译器，利用开源LLM，实现了高精确度和召回值。最后，我们展示了PolicyLR在政策合规性、不一致性检测和隐私比较购物等任务中的实用性。

> Privacy policies are crucial in the online ecosystem, defining how services handle user data and adhere to regulations such as GDPR and CCPA. However, their complexity and frequent updates often make them difficult for stakeholders to understand and analyze. Current automated analysis methods, which utilize natural language processing, have limitations. They typically focus on individual tasks and fail to capture the full context of the policies. We propose PolicyLR, a new paradigm that offers a comprehensive machine-readable representation of privacy policies, serving as an all-in-one solution for multiple downstream tasks. PolicyLR converts privacy policies into a machine-readable format using valuations of atomic formulae, allowing for formal definitions of tasks like compliance and consistency. We have developed a compiler that transforms unstructured policy text into this format using off-the-shelf Large Language Models (LLMs). This compiler breaks down the transformation task into a two-stage translation and entailment procedure. This procedure considers the full context of the privacy policy to infer a complex formula, where each formula consists of simpler atomic formulae. The advantage of this model is that PolicyLR is interpretable by design and grounded in segments of the privacy policy. We evaluated the compiler using ToS;DR, a community-annotated privacy policy entailment dataset. Utilizing open-source LLMs, our compiler achieves precision and recall values of 0.91 and 0.88, respectively. Finally, we demonstrate the utility of PolicyLR in three privacy tasks: Policy Compliance, Inconsistency Detection, and Privacy Comparison Shopping.

[Arxiv](https://arxiv.org/abs/2408.14830)