# 破链而出：揭秘多跳知识遗忘中的关联

发布时间：2024年10月17日

`LLM应用` `数据隐私` `人工智能`

> Breaking Chains: Unraveling the Links in Multi-Hop Knowledge Unlearning

# 摘要

> 大型语言模型（LLM）存储了大量信息，包括个人和受版权保护的数据，重新训练它们并不现实。因此，开发了多种快速、近似的遗忘技术，以有选择地删除特定知识。尽管现有研究通过调整语言建模目标来降低特定词序列的出现概率，但LLM仍易受间接引用攻击。我们发现，当前的遗忘技术在处理多跳查询时存在局限，尤其是当某个中间步骤被遗忘时，相关知识无法完全清除。为此，我们提出了MUNCH方法，通过将多跳查询分解为子问题，并利用遗忘模型的不确定性进行最终决策，有效解决了这一问题。实证结果显示，MUNCH不仅有效，还能轻松融入现有遗忘技术，为增强遗忘过程提供了灵活且实用的解决方案。

> Large language models (LLMs) serve as giant information stores, often including personal or copyrighted data, and retraining them from scratch is not a viable option. This has led to the development of various fast, approximate unlearning techniques to selectively remove knowledge from LLMs. Prior research has largely focused on minimizing the probabilities of specific token sequences by reversing the language modeling objective. However, these methods still leave LLMs vulnerable to adversarial attacks that exploit indirect references. In this work, we examine the limitations of current unlearning techniques in effectively erasing a particular type of indirect prompt: multi-hop queries. Our findings reveal that existing methods fail to completely remove multi-hop knowledge when one of the intermediate hops is unlearned. To address this issue, we propose MUNCH, a simple uncertainty-based approach that breaks down multi-hop queries into subquestions and leverages the uncertainty of the unlearned model in final decision-making. Empirical results demonstrate the effectiveness of our framework, and MUNCH can be easily integrated with existing unlearning techniques, making it a flexible and useful solution for enhancing unlearning processes.

[Arxiv](https://arxiv.org/abs/2410.13274)