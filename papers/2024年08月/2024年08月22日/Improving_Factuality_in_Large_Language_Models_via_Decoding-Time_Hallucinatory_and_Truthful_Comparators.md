# 利用解码时刻的幻觉与真实对比机制，提升大型语言模型的事实准确性

发布时间：2024年08月22日

`LLM应用` `人工智能`

> Improving Factuality in Large Language Models via Decoding-Time Hallucinatory and Truthful Comparators

# 摘要

> 尽管大型语言模型 (LLM) 能力出众，但它们常生成与事实不符的回应，即产生幻觉内容。现有方法多聚焦于模型参数优化或语义表示调整，却牺牲了模型内部的事实知识。此外，幻觉在下游任务中呈现多样模式，制约了模型跨任务的整体表现。为此，我们提出比较器驱动的解码时 (CDT) 框架，旨在减轻回应中的幻觉现象。我们首先构建了多任务微调样本的幻觉与真实比较器，并采用指令原型引导的专家混合策略，提升比较器捕捉不同幻觉或真实性模式的能力。CDT 通过对比目标 LLM 与比较器的 logit 差异，约束下一个词预测于事实性稳健的分布。系统实验显示，该框架能显著提升模型性能及回应的事实性。

> Despite their remarkable capabilities, Large Language Models (LLMs) are prone to generate responses that contradict verifiable facts, i.e., unfaithful hallucination content. Existing efforts generally focus on optimizing model parameters or editing semantic representations, which compromise the internal factual knowledge of target LLMs. In addition, hallucinations typically exhibit multifaceted patterns in downstream tasks, limiting the model's holistic performance across tasks. In this paper, we propose a Comparator-driven Decoding-Time (CDT) framework to alleviate the response hallucination. Firstly, we construct hallucinatory and truthful comparators with multi-task fine-tuning samples. In this case, we present an instruction prototype-guided mixture of experts strategy to enhance the ability of the corresponding comparators to capture different hallucination or truthfulness patterns in distinct task instructions. CDT constrains next-token predictions to factuality-robust distributions by contrasting the logit differences between the target LLMs and these comparators. Systematic experiments on multiple downstream tasks show that our framework can significantly improve the model performance and response factuality.

[Arxiv](https://arxiv.org/abs/2408.12325)