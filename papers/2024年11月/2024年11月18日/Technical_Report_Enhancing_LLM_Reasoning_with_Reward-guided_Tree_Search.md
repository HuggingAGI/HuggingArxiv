# 技术报告：以奖励引导的树搜索提升 LLM 推理能力

发布时间：2024年11月18日

`LLM应用`

> Technical Report: Enhancing LLM Reasoning with Reward-guided Tree Search

# 摘要

> 近来，测试时缩放备受研究界关注，这主要归因于 OpenAI 发布的 o1 模型的重大进步。在推理阶段分配更多计算资源，大型语言模型（LLMs）能够通过生成更多思考标记或多样的解决方案来广泛探索解空间，进而给出更精准的回应。不过，开发类似 o1 的推理方式颇具挑战，研究人员一直在进行各类尝试以推动这一开放研究领域的发展。本文中，我们针对通过奖励引导的树搜索算法提升 LLMs 的推理能力展开了初步探索。该框架通过整合策略模型、奖励模型和搜索算法得以实现。其主要围绕树搜索算法构建，策略模型在专门训练的奖励模型引导下对动态扩展的树进行导航。我们深入探究了实现此框架所需的各种设计考量，并给出了技术方面的详尽报告。为评估我们方法的成效，我们聚焦于数学推理任务，并在四个颇具挑战的数据集上进行了广泛评估，显著增强了 LLMs 的推理能力。

> Recently, test-time scaling has garnered significant attention from the research community, largely due to the substantial advancements of the o1 model released by OpenAI. By allocating more computational resources during the inference phase, large language models~(LLMs) can extensively explore the solution space by generating more thought tokens or diverse solutions, thereby producing more accurate responses. However, developing an o1-like reasoning approach is challenging, and researchers have been making various attempts to advance this open area of research. In this paper, we present a preliminary exploration into enhancing the reasoning abilities of LLMs through reward-guided tree search algorithms. This framework is implemented by integrating the policy model, reward model, and search algorithm. It is primarily constructed around a tree search algorithm, where the policy model navigates a dynamically expanding tree guided by a specially trained reward model. We thoroughly explore various design considerations necessary for implementing this framework and provide a detailed report of the technical aspects. To assess the effectiveness of our approach, we focus on mathematical reasoning tasks and conduct extensive evaluations on four challenging datasets, significantly enhancing the reasoning abilities of LLMs.

[Arxiv](https://arxiv.org/abs/2411.11694)