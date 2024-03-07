# [针对LLMs的遗忘问题，我们提出“防护栏基线”，旨在为模型提供一种有效去除有害信息或实现数据遗忘的基准方法。](https://arxiv.org/abs/2403.03329)

发布时间：2024年03月05日

`LLM应用`

> Guardrail Baselines for Unlearning in LLMs

> 近期研究表明，微调是有效从大型语言模型中移除特定概念的有效途径，但其成本较高，不仅涉及生成大量示例，还需要多次迭代微调模型参数。本文提出，诸如提示和过滤这类简洁的护栏策略也能达到与微调相当的移除学习效果。因此，在衡量更耗计算资源的微调方法效能时，推荐研究者探究此类轻量级基准方法。尽管我们并不认为提示或过滤能作为移除学习问题的万能解法，但研究揭示了亟需构建一套能更好区分护栏策略与微调效能差异的评估指标，并强调了在如仅为微调提供样例生成或仅通过API访问的情况下，护栏策略或许能展现出对移除学习的独特优势。

> Recent work has demonstrated that fine-tuning is a promising approach to `unlearn' concepts from large language models. However, fine-tuning can be expensive, as it requires both generating a set of examples and running iterations of fine-tuning to update the model. In this work, we show that simple guardrail-based approaches such as prompting and filtering can achieve unlearning results comparable to fine-tuning. We recommend that researchers investigate these lightweight baselines when evaluating the performance of more computationally intensive fine-tuning methods. While we do not claim that methods such as prompting or filtering are universal solutions to the problem of unlearning, our work suggests the need for evaluation metrics that can better separate the power of guardrails vs. fine-tuning, and highlights scenarios where guardrails themselves may be advantageous for unlearning, such as in generating examples for fine-tuning or unlearning when only API access is available.