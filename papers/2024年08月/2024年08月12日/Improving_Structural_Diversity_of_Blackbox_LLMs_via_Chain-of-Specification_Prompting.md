# 利用 Chain-of-Specification Prompting 技术，我们旨在增强黑盒 LLM 的结构多样性。

发布时间：2024年08月12日

`LLM应用` `软件开发`

> Improving Structural Diversity of Blackbox LLMs via Chain-of-Specification Prompting

# 摘要

> 大型语言模型 (LLM) 在生成多样化文本方面面临挑战。虽然已有研究通过 $n$-gram 或 BERT 嵌入等指标探讨多样性，但用户对多样性维度的控制有限。例如，诗歌领域可能追求韵律和格律的多样性，而代码领域则关注解决问题表达方式的多样性。为此，我们引入了结构多样性度量，允许用户定义多样性特征。同时，我们提出了规范链 (CoS) 提示策略，通过先定义特征再生成文本，有效提升多样性，且适用于黑盒 LLM。实验表明，CoS 在诗歌和代码领域的结构多样性上显著优于传统方法。

> The capability to generate diverse text is a key challenge facing large language models (LLMs). Thus far, diversity has been studied via metrics such as $n$-gram diversity or diversity of BERT embeddings. However, for these kinds of diversity, the user has little control over the dimensions along which diversity is considered. For example, in the poetry domain, one might desire diversity in terms of rhyme and meter, whereas in the code domain, one might desire diversity in terms of the kinds of expressions used to solve a problem. We propose a diversity metric called structural diversity, where the user provides a mapping from generated text to features capturing the kinds of diversity that they care about. In addition, we propose a novel strategy called chain-of-specification (CoS) prompting for improving diversity by first having the LLM generate a specification encoding one instance of structural features, and then prompting the LLM to generate text that satisfies these features; notably, our strategy works with blackbox LLMs. In our experiments, we show that for structural diversity in the poetry and code domains, CoS significantly improves diversity compared to several baselines.

[Arxiv](https://arxiv.org/abs/2408.06186)