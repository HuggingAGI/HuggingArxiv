# 偏差大揭秘：探究大型语言模型生成代码里的社会偏差

发布时间：2024年11月15日

`LLM应用` `代码生成` `社会偏见评估`

> Bias Unveiled: Investigating Social Bias in LLM-Generated Code

# 摘要

> 大型语言模型（LLMs）在自动代码生成领域取得了显著进展。然而，对于LLMs生成的代码中可能存在的社会偏见的评估，存在明显的研究空缺。为解决此问题，我们提出了一个全新的公平框架——Solar，用于评估和缓解LLM生成代码的社会偏见。具体来说，Solar能自动生成测试用例，定量揭示LLMs自动生成代码中的社会偏见。为量化生成代码中社会偏见的严重程度，我们开发了一个涵盖多种社会问题的数据集。我们把Solar和精心打造的数据集应用于四个用于代码生成的先进LLMs。我们的评估表明，所有被研究的LLMs生成的代码都存在严重偏见。此外，我们探索了几种减轻偏见的策略，如思维链（CoT）提示、将积极角色扮演与CoT提示相结合以及迭代提示。我们的实验显示，迭代提示能有效将LLM生成代码中的社会偏见减少高达90%。Solar在评估新社会问题方面具有很强的扩展性。

> Large language models (LLMs) have significantly advanced the field of automated code generation. However, a notable research gap exists in the evaluation of social biases that may be present in the code produced by LLMs. To solve this issue, we propose a novel fairness framework, i.e., Solar, to assess and mitigate the social biases of LLM-generated code. Specifically, Solar can automatically generate test cases for quantitatively uncovering social biases of the auto-generated code by LLMs. To quantify the severity of social biases in generated code, we develop a dataset that covers a diverse set of social problems. We applied Solar and the crafted dataset to four state-of-the-art LLMs for code generation. Our evaluation reveals severe bias in the LLM-generated code from all the subject LLMs. Furthermore, we explore several strategies for bias mitigation, including Chain-of-Thought (CoT) prompting, combining positive role-playing with CoT prompting and iterative prompting. Our experiments show that iterative prompting can effectively reduce social bias in LLM-generated code by up to 90%. Solar is highly extensible to evaluate new social problems.

[Arxiv](https://arxiv.org/abs/2411.10351)