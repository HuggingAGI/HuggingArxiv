# SCOTT：自洽链式思维蒸馏法

发布时间：2023年08月30日

`LLM理论

理由：这篇论文探讨了大型语言模型（LMs）在思维链（CoT）提示下的性能提升问题，并提出了一种忠实的知识蒸馏方法来生成自我一致的小型CoT模型。这种方法涉及到从大型模型中提取理由，并通过反事实推理目标来确保理由的忠实性。这些研究内容主要关注于LLM的理论和内部机制，特别是如何通过技术手段改进模型的内部推理过程，因此属于LLM理论分类。` `人工智能`

> SCOTT: Self-Consistent Chain-of-Thought Distillation

# 摘要

> 当大型语言模型（LMs）达到一定规模时，它们能够通过思维链（CoT）提示生成自由文本的预测理由。虽然CoT能显著提升性能，但这种提升仅限于足够大的模型。更关键的是，这些生成的理由与模型的预测是否一致，以及它们是否真实地证明了决策，这些问题尚无定论。本研究提出了一种忠实的知识蒸馏方法，旨在从庞大的教师模型中提炼出一个自我一致的小型CoT模型。我们通过对比解码技术，从大型LM（教师）中提取支持正确答案的理由，促使教师生成只有在答案正确时才显得合理的令牌。为了确保蒸馏过程的忠实性，我们利用教师生成的理由来训练学生LM，并采用反事实推理目标，以防止学生忽视理由而做出不一致的预测。实验结果显示，尽管在最终任务性能上与基线相当，我们的方法生成的CoT理由更为忠实。进一步分析表明，该模型在决策时更重视理由，因此通过优化其理由，我们能够进一步提升其性能。

> Large language models (LMs) beyond a certain scale, demonstrate the emergent capability of generating free-text rationales for their predictions via chain-of-thought (CoT) prompting. While CoT can yield dramatically improved performance, such gains are only observed for sufficiently large LMs. Even more concerning, there is little guarantee that the generated rationales are consistent with LM's predictions or faithfully justify the decisions. In this work, we propose a faithful knowledge distillation method to learn a small, self-consistent CoT model from a teacher model that is orders of magnitude larger. To form better supervision, we elicit rationales supporting the gold answers from a large LM (teacher) by contrastive decoding, which encourages the teacher to generate tokens that become more plausible only when the answer is considered. To ensure faithful distillation, we use the teacher-generated rationales to learn a student LM with a counterfactual reasoning objective, which prevents the student from ignoring the rationales to make inconsistent predictions. Experiments show that, while yielding comparable end-task performance, our method can generate CoT rationales that are more faithful than baselines do. Further analysis suggests that such a model respects the rationales more when making decisions; thus, we can improve its performance more by refining its rationales.

[Arxiv](https://arxiv.org/abs/2305.01879)