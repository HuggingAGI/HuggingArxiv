# 深入探讨大型语言模型的机器遗忘机制

发布时间：2024年10月10日

`LLM理论` `隐私保护`

> A Closer Look at Machine Unlearning for Large Language Models

# 摘要

> 大型语言模型 (LLM) 可能记住敏感或受版权保护的内容，引发隐私和法律问题。由于重新训练成本高昂，研究人员尝试使用机器遗忘来删除特定内容，同时保持整体性能。本文探讨了 LLM 机器遗忘的几个问题，并提出了可能的解决方案。为解决遗忘后模型输出评估不足的问题，我们引入了三个新指标：令牌多样性、句子语义和事实正确性。我们将遗忘方法分为无目标和有目标两类，分别讨论了它们的问题。无目标遗忘的行为不可预测，可能产生幻觉，而有目标遗忘的现有正则化不足。为此，我们建议使用最大化熵 (ME) 作为无目标遗忘的目标，并引入答案保留 (AP) 损失作为有目标遗忘的正则化。实验结果表明，我们的方法在虚构、持续和真实世界遗忘场景中均有效。代码已开源，详见 https://github.com/sail-sg/closer-look-LLM-unlearning。

> Large language models (LLMs) may memorize sensitive or copyrighted content, raising privacy and legal concerns. Due to the high cost of retraining from scratch, researchers attempt to employ machine unlearning to remove specific content from LLMs while preserving the overall performance. In this paper, we discuss several issues in machine unlearning for LLMs and provide our insights on possible approaches. To address the issue of inadequate evaluation of model outputs after unlearning, we introduce three additional metrics to evaluate token diversity, sentence semantics, and factual correctness. We then categorize unlearning methods into untargeted and targeted, and discuss their issues respectively. Specifically, the behavior that untargeted unlearning attempts to approximate is unpredictable and may involve hallucinations, and existing regularization is insufficient for targeted unlearning. To alleviate these issues, we propose using the objective of maximizing entropy (ME) for untargeted unlearning and incorporate answer preservation (AP) loss as regularization for targeted unlearning. Experimental results across three scenarios, i.e., fictitious unlearning, continual unlearning, and real-world unlearning, demonstrate the effectiveness of our approaches. The code is available at https://github.com/sail-sg/closer-look-LLM-unlearning.

[Arxiv](https://arxiv.org/abs/2410.08109)