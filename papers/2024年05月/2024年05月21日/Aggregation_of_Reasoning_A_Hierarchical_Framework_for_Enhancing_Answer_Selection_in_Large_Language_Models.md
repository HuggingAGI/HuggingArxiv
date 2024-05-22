# 推理聚合：构建层次框架，提升大型语言模型答案选择的精准度

发布时间：2024年05月21日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在复杂推理任务中的性能提升问题，并提出了一种新的分层推理聚合框架——AoR。该研究关注的是LLMs的理论改进和性能优化，特别是通过评估推理链来精选答案，并根据任务复杂度动态调整推理链数量。这与LLM的应用实践不同，更多地集中在理论层面的创新和模型性能的提升上。因此，将其归类为LLM理论是合适的。` `人工智能`

> Aggregation of Reasoning: A Hierarchical Framework for Enhancing Answer Selection in Large Language Models

# 摘要

> 思维链提示技术的最新进展显著提升了大型语言模型（LLMs）在复杂推理任务中的表现。现有研究通过多推理链采样和答案频率集成提高了LLMs的推理能力，但当正确答案罕见时，这种方法便失效了。我们发现这是制约LLMs推理能力的关键因素，单靠预测答案无法克服。为此，我们提出了一个分层推理聚合框架——AoR（推理聚合），它通过评估推理链来精选答案，并根据任务复杂度动态调整推理链数量。实验证明，AoR在复杂推理任务中超越了其他集成方法，且分析表明，AoR不仅兼容多种LLMs，还达到了比现有方法更高的性能极限。

> Recent advancements in Chain-of-Thought prompting have facilitated significant breakthroughs for Large Language Models (LLMs) in complex reasoning tasks. Current research enhances the reasoning performance of LLMs by sampling multiple reasoning chains and ensembling based on the answer frequency. However, this approach fails in scenarios where the correct answers are in the minority. We identify this as a primary factor constraining the reasoning capabilities of LLMs, a limitation that cannot be resolved solely based on the predicted answers. To address this shortcoming, we introduce a hierarchical reasoning aggregation framework AoR (Aggregation of Reasoning), which selects answers based on the evaluation of reasoning chains. Additionally, AoR incorporates dynamic sampling, adjusting the number of reasoning chains in accordance with the complexity of the task. Experimental results on a series of complex reasoning tasks show that AoR outperforms prominent ensemble methods. Further analysis reveals that AoR not only adapts various LLMs but also achieves a superior performance ceiling when compared to current methods.

[Arxiv](https://arxiv.org/abs/2405.12939)