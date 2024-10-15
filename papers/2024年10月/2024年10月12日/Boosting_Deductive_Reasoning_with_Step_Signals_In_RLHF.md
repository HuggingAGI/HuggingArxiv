# 通过步骤信号提升 RLHF 中的演绎推理能力

发布时间：2024年10月12日

`LLM理论` `人工智能`

> Boosting Deductive Reasoning with Step Signals In RLHF

# 摘要

> 逻辑推理对 LLM 至关重要，尤其是多步骤推理更具挑战性。基于形式逻辑，我们开发了 MuseD 方法，用于自动生成演绎推理数据，并创建了多步骤推理的训练和测试集。通过控制生成指令的复杂性，我们能在不同难度级别上训练和评估模型。RLHF 训练显著提升了模型在域内外的逻辑推理能力。此外，我们还测试了不同模型的多步骤推理能力。

> Logical reasoning is a crucial task for Large Language Models (LLMs), enabling them to tackle complex problems. Among reasoning tasks, multi-step reasoning poses a particular challenge. Grounded in the theory of formal logic, we have developed an automated method, Multi-step Deduction (MuseD), for deductive reasoning data. MuseD has allowed us to create training and testing datasets for multi-step reasoning. Our generation method enables control over the complexity of the generated instructions, facilitating training and evaluation of models across different difficulty levels. Through RLHF training, our training data has demonstrated significant improvements in logical capabilities for both in-domain of out-of-domain reasoning tasks. Additionally, we have conducted tests to assess the multi-step reasoning abilities of various models.

[Arxiv](https://arxiv.org/abs/2410.09528)