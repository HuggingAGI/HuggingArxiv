# 无需更新，In-Context Learning 便能带来更深层次的洞察，其效果超越了微调。

发布时间：2024年10月06日

`LLM理论` `人工智能` `机器学习`

> Deeper Insights Without Updates: The Power of In-Context Learning Over Fine-Tuning

# 摘要

> 微调和上下文学习 (ICL) 是提升大型语言模型任务特定知识的两大法宝。通常认为，微调在充足训练样本的支持下能超越 ICL，因其能根据数据调整模型参数。然而，本文揭示了一个令人意外的现象：在处理隐含模式任务时，ICL 的表现远胜微调。我们设计了多个包含隐含模式的数集，如通过奇偶性解题或识别计算中的可约项。在 0.5B 到 7B 参数的模型中，我们分别测试了微调和 ICL 对这些模式的理解。结果显示，ICL 模型能迅速洞察深层模式，大幅提升准确性；而微调虽使用海量训练样本，改进却有限。我们还提出了电路偏移理论，从机制可解释性角度解析了 ICL 的优势所在。

> Fine-tuning and in-context learning (ICL) are two prevalent methods in imbuing large language models with task-specific knowledge. It is commonly believed that fine-tuning can surpass ICL given sufficient training samples as it allows the model to adjust its internal parameters based on the data. However, this paper presents a counterintuitive finding: For tasks with implicit patterns, ICL captures these patterns significantly better than fine-tuning. We developed several datasets featuring implicit patterns, such as sequences determining answers through parity or identifying reducible terms in calculations. We then evaluated the models' understanding of these patterns under both fine-tuning and ICL across models ranging from 0.5B to 7B parameters. The results indicate that models employing ICL can quickly grasp deep patterns and significantly improve accuracy. In contrast, fine-tuning, despite utilizing thousands of times more training samples than ICL, achieved only limited improvements. We also proposed circuit shift theory from a mechanistic interpretability's view to explain why ICL wins.

[Arxiv](https://arxiv.org/abs/2410.04691)