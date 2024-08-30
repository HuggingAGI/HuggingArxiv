# Critic-CoT：借助思维链批评机制，大幅提升大型语言模型的推理能力。

发布时间：2024年08月29日

`LLM理论` `人工智能`

> Critic-CoT: Boosting the reasoning abilities of large language model via Chain-of-thoughts Critic

# 摘要

> 自我批评机制在提升LLMs推理性能方面扮演着关键角色。然而，现有方法多依赖基础提示，缺乏深度训练，导致准确性受限。同时，LLM的批评能力与其任务解决性能之间的关系尚未得到充分探讨。为此，我们创新性地提出了Critic-CoT框架，通过逐步推理和远距离监督数据构建，强化LLMs的系统2类批评能力，无需人工标注。实验结果显示，通过剔除无效方案或迭代优化，我们的模型在GSM8K和MATH任务中表现更佳，验证了方法的有效性。此外，单独的批评与改进训练也能显著提升生成质量。我们期待这项研究能为未来LLMs推理与批评能力的发展提供新的视角。

> Self-critic has become an important mechanism for enhancing the reasoning performance of LLMs. However, current approaches mainly involve basic prompts without further training, which tend to be over-simplified, leading to limited accuracy.Moreover, there is a lack of in-depth investigation of the relationship between LLM's ability to criticism and its task-solving performance.To address these issues, we propose Critic-CoT, a novel framework that pushes LLMs toward System-2-like critic capability, via step-wise CoT reasoning format and distant-supervision data construction, without the need for human annotation. Experiments on GSM8K and MATH show that via filtering out invalid solutions or iterative refinement, our enhanced model boosts task-solving performance, which demonstrates the effectiveness of our method. Further, we find that training on critique and refinement alone improves the generation. We hope our work could shed light on future research on improving the reasoning and critic ability of LLMs.

[Arxiv](https://arxiv.org/abs/2408.16326)