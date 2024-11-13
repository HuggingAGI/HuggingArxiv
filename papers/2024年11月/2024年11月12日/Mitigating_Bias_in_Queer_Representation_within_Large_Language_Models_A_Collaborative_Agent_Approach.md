# 在大型语言模型中减轻酷儿表征的偏差：一种协作代理方法

发布时间：2024年11月12日

`Agent` `人工智能伦理`

> Mitigating Bias in Queer Representation within Large Language Models: A Collaborative Agent Approach

# 摘要

> 大型语言模型（LLM）在代词使用方面经常延续偏见，导致对酷儿个体的错误表述或排斥。本文解决了 LLM 输出中代词使用有偏见的具体问题，特别是在需要包容性语言来准确代表所有身份时，不恰当地使用传统的性别代词（“他”、“她”）。我们引入了一个协作代理管道，旨在通过分析和优化代词使用的包容性来减轻这些偏见。我们的多代理框架包括专门用于偏差检测和纠正的代理。使用 Tango 数据集（一个专注于性别代词使用的基准）进行的实验评估表明，我们的方法显著提高了包容性代词分类，与 GPT-4o 相比，在正确反对不适当的传统性别代词方面提高了 32.6 个百分点（$χ^2 = 38.57，p < 0.0001$）。这些结果突出了代理驱动框架在提高人工智能生成内容的公平性和包容性方面的潜力，展示了它们在减少偏见和促进社会责任人工智能方面的功效。

> Large Language Models (LLMs) often perpetuate biases in pronoun usage, leading to misrepresentation or exclusion of queer individuals. This paper addresses the specific problem of biased pronoun usage in LLM outputs, particularly the inappropriate use of traditionally gendered pronouns ("he," "she") when inclusive language is needed to accurately represent all identities. We introduce a collaborative agent pipeline designed to mitigate these biases by analyzing and optimizing pronoun usage for inclusivity. Our multi-agent framework includes specialized agents for both bias detection and correction. Experimental evaluations using the Tango dataset-a benchmark focused on gender pronoun usage-demonstrate that our approach significantly improves inclusive pronoun classification, achieving a 32.6 percentage point increase over GPT-4o in correctly disagreeing with inappropriate traditionally gendered pronouns $(χ^2 = 38.57, p < 0.0001)$. These results accentuate the potential of agent-driven frameworks in enhancing fairness and inclusivity in AI-generated content, demonstrating their efficacy in reducing biases and promoting socially responsible AI.

[Arxiv](https://arxiv.org/abs/2411.07656)