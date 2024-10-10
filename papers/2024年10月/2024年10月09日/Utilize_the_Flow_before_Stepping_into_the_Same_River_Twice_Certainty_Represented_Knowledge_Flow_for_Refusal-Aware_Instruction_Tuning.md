# 在两次踏入同一条河流之前，利用流动的确定性知识进行拒绝感知的指令调优。

发布时间：2024年10月09日

`LLM理论` `人工智能`

> Utilize the Flow before Stepping into the Same River Twice: Certainty Represented Knowledge Flow for Refusal-Aware Instruction Tuning

# 摘要

> 拒绝感知指令调优 (RAIT) 让大型语言模型 (LLM) 学会拒绝回答未知问题。通过将训练数据中未知问题的答案改为“我不知道”，RAIT 提升了 LLM 的可靠性并减少了幻觉。然而，这种简单的方法可能导致 LLM 过度拒绝回答本可以正确回答的问题，即过度拒绝。本文探讨了过度拒绝的两个主要原因：静态冲突和动态冲突。为了解决这些问题，我们提出了确定性表示知识流 (CRaFT)，通过引入响应确定性和初步排练训练，减少冲突并提升 LLM 在 RAIT 过程中的整体性能。实验结果证实了 CRaFT 的有效性。源代码和训练数据将在 Github 上公开。

> Refusal-Aware Instruction Tuning (RAIT) enables Large Language Models (LLMs) to refuse to answer unknown questions. By modifying responses of unknown questions in the training data to refusal responses such as "I don't know", RAIT enhances the reliability of LLMs and reduces their hallucination. Generally, RAIT modifies training samples based on the correctness of the initial LLM's response. However, this crude approach can cause LLMs to excessively refuse answering questions they could have correctly answered, the problem we call over-refusal. In this paper, we explore two primary causes of over-refusal: Static conflict emerges when the RAIT data is constructed solely on correctness criteria, causing similar samples in the LLM's feature space to be assigned different labels (original vs. modified "I don't know"). Dynamic conflict occurs due to the changes of LLM's knowledge state during fine-tuning, which transforms previous unknown questions into knowns, while the training data, which is constructed based on the initial LLM, remains unchanged. These conflicts cause the trained LLM to misclassify known questions as unknown, resulting in over-refusal. To address this issue, we introduce Certainty Represented Knowledge Flow for Refusal-Aware Instructions Construction (CRaFT). CRaFT centers on two main contributions: First, we additionally incorporate response certainty to selectively filter and modify data, reducing static conflicts. Second, we implement preliminary rehearsal training to characterize changes in the LLM's knowledge state, which helps mitigate dynamic conflicts during the fine-tuning process. We conducted extensive experiments on open-ended question answering and multiple-choice question task. Experiment results show that CRaFT can improve LLM's overall performance during the RAIT process. Source code and training data will be released at Github.

[Arxiv](https://arxiv.org/abs/2410.06913)