# 《沙漠骆驼与石油酋长：围绕阿拉伯的前沿大型语言模型红队策略》

发布时间：2024年10月31日

`LLM应用` `语言模型`

> Desert Camels and Oil Sheikhs: Arab-Centric Red Teaming of Frontier LLMs

# 摘要

> 大型语言模型（LLMs）应用广泛，然而因其嵌入的社会偏见引发了伦理担忧。本研究在诸如妇女权利、恐怖主义、反犹太主义等八个领域，审视了LLM对阿拉伯人与西方人的偏见，并评估了模型抵御这些偏见延续的能力。为此，我们构建了两个数据集：其一用于评估LLM对阿拉伯人与西方人的偏见，其二用于测试模型面对夸大负面特征（“越狱”）提示时的安全性。我们对六个LLM——GPT-4、GPT-4o、LlaMA 3.1（8B 与 405B）、Mistral 7B 以及 Claude 3.5 Sonnet 进行了评估。我们发现，79%的情形呈现出对阿拉伯人的负面偏见，其中 LlaMA 3.1-405B 的偏见最为显著。我们的越狱测试表明，尽管 GPT-4o 是优化版，但它最为脆弱，其次是 LlaMA 3.1-8B 和 Mistral 7B。除 Claude 外，所有的 LLM 在三个类别中的攻击成功率均超 87%。我们还发现 Claude 3.5 Sonnet 最为安全，不过它在八个类别中的七个仍存在偏见。尽管 GPT-4o 是 GPT4 的优化版本，但我们发现它更易出现偏见和越狱情况，这暗示了优化存在缺陷。我们的发现凸显了 LLMs 迫切需要更有力的偏见缓解策略以及更强的安全举措。

> Large language models (LLMs) are widely used but raise ethical concerns due to embedded social biases. This study examines LLM biases against Arabs versus Westerners across eight domains, including women's rights, terrorism, and anti-Semitism and assesses model resistance to perpetuating these biases. To this end, we create two datasets: one to evaluate LLM bias toward Arabs versus Westerners and another to test model safety against prompts that exaggerate negative traits ("jailbreaks"). We evaluate six LLMs -- GPT-4, GPT-4o, LlaMA 3.1 (8B & 405B), Mistral 7B, and Claude 3.5 Sonnet. We find 79% of cases displaying negative biases toward Arabs, with LlaMA 3.1-405B being the most biased. Our jailbreak tests reveal GPT-4o as the most vulnerable, despite being an optimized version, followed by LlaMA 3.1-8B and Mistral 7B. All LLMs except Claude exhibit attack success rates above 87% in three categories. We also find Claude 3.5 Sonnet the safest, but it still displays biases in seven of eight categories. Despite being an optimized version of GPT4, We find GPT-4o to be more prone to biases and jailbreaks, suggesting optimization flaws. Our findings underscore the pressing need for more robust bias mitigation strategies and strengthened security measures in LLMs.

[Arxiv](https://arxiv.org/abs/2410.24049)