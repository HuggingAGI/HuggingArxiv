# 大型语言模型的属性控制微调：去毒化案例研究

发布时间：2024年10月07日

`LLM理论` `人工智能`

> Attribute Controlled Fine-tuning for Large Language Models: A Case Study on Detoxification

# 摘要

> 我们提出了一种约束学习方案，通过属性控制对大型语言模型（LLM）进行微调。给定训练语料库和模型输出约束，我们的方法在微调过程中，既能满足约束条件，又几乎不影响模型的实用性和生成质量。具体而言，我们通过惩罚期望输出分布与模型后验之间的KL散度来正则化训练。这一正则化项可由辅助模型分解为令牌级指导，从而通过闭式公式计算。为提高效率，我们设计了并行更新方案，同时优化LLM和辅助模型。实验表明，我们的方法在控制毒性训练LLM时，能减少不当响应，同时在基准测试和毒性检测任务中表现优异。

> We propose a constraint learning schema for fine-tuning Large Language Models (LLMs) with attribute control. Given a training corpus and control criteria formulated as a sequence-level constraint on model outputs, our method fine-tunes the LLM on the training corpus while enhancing constraint satisfaction with minimal impact on its utility and generation quality. Specifically, our approach regularizes the LLM training by penalizing the KL divergence between the desired output distribution, which satisfies the constraints, and the LLM's posterior. This regularization term can be approximated by an auxiliary model trained to decompose the sequence-level constraints into token-level guidance, allowing the term to be measured by a closed-form formulation. To further improve efficiency, we design a parallel scheme for concurrently updating both the LLM and the auxiliary model. We evaluate the empirical performance of our approach by controlling the toxicity when training an LLM. We show that our approach leads to an LLM that produces fewer inappropriate responses while achieving competitive performance on benchmarks and a toxicity detection task.

[Arxiv](https://arxiv.org/abs/2410.05559)