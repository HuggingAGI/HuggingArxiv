# TabVer：运用自然逻辑进行表格事实的验证

发布时间：2024年11月01日

`LLM应用` `事实核查`

> TabVer: Tabular Fact Verification with Natural Logic

# 摘要

> 对于表格证据的事实核查，促使人们采用构建逻辑形式（如 LISP 风格程序）的符号推理模型，其可验证性高于全神经方法。但这类系统往往依赖规范的表格，在很多场景中应用受限。针对文本证据的新兴符号推理范式聚焦于自然逻辑推理，通过对自然语言中主张及其证据间的集合论关系建模来构建证明。此方法灵活透明，不过与表格证据的兼容性欠佳，因为相关关系未涵盖算术函数。我们给出了自然逻辑背景下对数字和算术函数的集合论解读，从而能在确定性证明中融入算术表达式。我们借助大型语言模型，针对主张的关键部分生成问题，并通过在表格上执行相应函数来回答，从而生成算术表达式。在 FEVEROUS 的少样本设定下，我们实现了 71.4 的准确率，比全神经和符号推理模型高 3.4 个点。在 TabFact 上未经进一步训练进行评估时，我们的方法仍具竞争力，准确率领先 0.5 个点。

> Fact verification on tabular evidence incentivises the use of symbolic reasoning models where a logical form is constructed (e.g. a LISP-style program), providing greater verifiability than fully neural approaches. However, these systems typically rely on well-formed tables, restricting their use in many scenarios. An emerging symbolic reasoning paradigm for textual evidence focuses on natural logic inference, which constructs proofs by modelling set-theoretic relations between a claim and its evidence in natural language. This approach provides flexibility and transparency but is less compatible with tabular evidence since the relations do not extend to arithmetic functions. We propose a set-theoretic interpretation of numerals and arithmetic functions in the context of natural logic, enabling the integration of arithmetic expressions in deterministic proofs. We leverage large language models to generate arithmetic expressions by generating questions about salient parts of a claim which are answered by executing appropriate functions on tables. In a few-shot setting on FEVEROUS, we achieve an accuracy of 71.4, outperforming both fully neural and symbolic reasoning models by 3.4 points. When evaluated on TabFact without any further training, our method remains competitive with an accuracy lead of 0.5 points.

[Arxiv](https://arxiv.org/abs/2411.01093)