# CEB：大型语言模型公平性的组合评估基准

发布时间：2024年07月02日

`LLM应用` `社会科学`

> CEB: Compositional Evaluation Benchmark for Fairness in Large Language Models

# 摘要

> 随着 LLM 在 NLP 任务中的广泛应用，其生成内容可能带来的社会负面影响也引起了关注。为评估 LLM 的偏见，研究者们提出了多种数据集，但现有评估多聚焦于单一偏见类型，且指标不统一，导致跨数据集和模型的比较困难。为此，我们收集了多样的偏见评估数据集，并提出 CEB，一个覆盖不同社会群体和任务的多类型偏见组合评估基准。CEB 基于我们新创的组合分类法构建，该分类法从偏见类型、社会群体和任务三个维度对数据集进行全面描述。通过整合这三个维度，我们设计了一套全面的 LLM 偏见评估策略。实验显示，偏见程度在各维度间存在差异，为针对性偏见缓解方法的开发提供了方向。

> As Large Language Models (LLMs) are increasingly deployed to handle various natural language processing (NLP) tasks, concerns regarding the potential negative societal impacts of LLM-generated content have also arisen. To evaluate the biases exhibited by LLMs, researchers have recently proposed a variety of datasets. However, existing bias evaluation efforts often focus on only a particular type of bias and employ inconsistent evaluation metrics, leading to difficulties in comparison across different datasets and LLMs. To address these limitations, we collect a variety of datasets designed for the bias evaluation of LLMs, and further propose CEB, a Compositional Evaluation Benchmark that covers different types of bias across different social groups and tasks. The curation of CEB is based on our newly proposed compositional taxonomy, which characterizes each dataset from three dimensions: bias types, social groups, and tasks. By combining the three dimensions, we develop a comprehensive evaluation strategy for the bias in LLMs. Our experiments demonstrate that the levels of bias vary across these dimensions, thereby providing guidance for the development of specific bias mitigation methods.

[Arxiv](https://arxiv.org/abs/2407.02408)