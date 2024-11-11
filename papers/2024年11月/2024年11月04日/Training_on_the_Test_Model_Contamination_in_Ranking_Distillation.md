# 在测试模型上进行训练：排名蒸馏中的污染

发布时间：2024年11月04日

`LLM应用` `知识蒸馏`

> Training on the Test Model: Contamination in Ranking Distillation

# 摘要

> 基于预训练语言模型的神经排序方法在临时搜索中非常有效。然而，这些模型的计算成本可能会限制其应用。因此，一种称为知识蒸馏的过程经常被应用，以允许一个更小、更高效的模型向一个有效但昂贵的模型学习。一个关键的例子是将昂贵的基于 API 的商业大型语言模型蒸馏成更小的可投入生产的模型。然而，由于大多数商业模型的训练数据和过程不透明，无法确保所选的测试集以前没有被观察到，从而有可能造成无意的数据污染。因此，我们研究了在蒸馏环境中受污染的教师模型的影响。我们评估了几种蒸馏技术，以评估蒸馏过程中发生污染的程度。通过模拟一个“最坏情况”的设置，其中污染程度是已知的，我们发现即使测试数据只占教师训练样本的一小部分，也会发生污染。因此，当使用数据来源不明确的黑箱教师模型进行训练时，我们鼓励谨慎行事。

> Neural approaches to ranking based on pre-trained language models are highly effective in ad-hoc search. However, the computational expense of these models can limit their application. As such, a process known as knowledge distillation is frequently applied to allow a smaller, efficient model to learn from an effective but expensive model. A key example of this is the distillation of expensive API-based commercial Large Language Models into smaller production-ready models. However, due to the opacity of training data and processes of most commercial models, one cannot ensure that a chosen test collection has not been observed previously, creating the potential for inadvertent data contamination. We, therefore, investigate the effect of a contaminated teacher model in a distillation setting. We evaluate several distillation techniques to assess the degree to which contamination occurs during distillation. By simulating a ``worst-case'' setting where the degree of contamination is known, we find that contamination occurs even when the test data represents a small fraction of the teacher's training samples. We, therefore, encourage caution when training using black-box teacher models where data provenance is ambiguous.

[Arxiv](https://arxiv.org/abs/2411.02284)