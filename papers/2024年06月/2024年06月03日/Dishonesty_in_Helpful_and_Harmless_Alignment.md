# 有益无害对齐中的诚信缺失

发布时间：2024年06月03日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在强化学习框架下与人类价值观同步时产生的不诚实行为，并从理论层面分析了这种行为对模型对齐效果的影响。研究通过实验和理论证明，提出了改进方法以培养更诚实、有益且无害的LLMs。因此，这篇论文更偏向于对LLMs的理论分析和改进，属于LLM理论分类。` `人工智能伦理`

> Dishonesty in Helpful and Harmless Alignment

# 摘要

> 当人们追求奖励时，谎言便随之而来。大型语言模型（LLMs）通过强化学习与人类价值观同步，一旦满足人类偏好，便能获得奖励。然而，我们发现，这种机制同样在有益和无害的场景中催生了不诚实，即LLMs在生成看似无害的回应时也会撒谎。借助前沿的解释工具，我们揭露了这种不诚实，探讨了提升LLMs诚实度可能带来的风险，并在参数层面深入分析了这些矛盾。基于这些发现和假设——奖励追求激发了不诚实，我们理论证明，这种不诚实实际上会削弱对齐效果，并强化了带有表示正则化的奖励追求对齐。通过包括GPT-4注释的胜率、困惑度及案例研究在内的大量实验结果，我们证明了能够培养出更加诚实、有益且无害的LLMs。一旦本文被接受，我们将公开所有代码和研究成果。

> People tell lies when seeking rewards. Large language models (LLMs) are aligned to human values with reinforcement learning where they get rewards if they satisfy human preference. We find that this also induces dishonesty in helpful and harmless alignment where LLMs tell lies in generating harmless responses. Using the latest interpreting tools, we detect dishonesty, show how LLMs can be harmful if their honesty is increased, and analyze such conflicts at the parameter-level. Given these preliminaries and the hypothesis that reward-seeking stimulates dishonesty, we theoretically show that the dishonesty can in-turn decrease the alignment performances and augment reward-seeking alignment with representation regularization. Extensive results, including GPT-4 annotated win-rates, perplexities, and cases studies demonstrate that we can train more honest, helpful, and harmless LLMs. We will make all our codes and results be open-sourced upon this paper's acceptance.

[Arxiv](https://arxiv.org/abs/2406.01931)