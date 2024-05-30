# 大型语言模型是否具有变色龙般的适应性？

发布时间：2024年05月29日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在回答主观问题时表现出的文化、年龄和性别偏见，并研究了这些偏见如何受输入提示的影响。此外，论文还提出了新的度量方法来量化LLMs与真实数据之间的差异。这些内容主要关注LLMs的理论特性和行为分析，因此属于LLM理论分类。` `社会科学` `人工智能`

> Are Large Language Models Chameleons?

# 摘要

> 大型语言模型（LLMs）是否拥有独特的世界观和个性倾向？通过超过100万次的模拟实验，我们发现LLMs在回答主观问题时，其回答与欧洲社会调查（ESS）的真实数据相比，显示出显著的文化、年龄和性别偏见。这些偏见主要受输入提示的影响。为了量化LLMs与真实数据之间的差异，我们探讨了包括加权平均和基于Jaccard相似性的新度量方法。研究结果强调，在利用LLMs模拟个体或集体行为之前，必须深入分析提示的稳定性和变异性，因为LLMs的模仿能力仅能达到近似水平。

> Do large language models (LLMs) have their own worldviews and personality tendencies? Simulations in which an LLM was asked to answer subjective questions were conducted more than 1 million times. Comparison of the responses from different LLMs with real data from the European Social Survey (ESS) suggests that the effect of prompts on bias and variability is fundamental, highlighting major cultural, age, and gender biases. Methods for measuring the difference between LLMs and survey data are discussed, such as calculating weighted means and a new proposed measure inspired by Jaccard similarity. We conclude that it is important to analyze the robustness and variability of prompts before using LLMs to model individual decisions or collective behavior, as their imitation abilities are approximate at best.

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/freehms_men_p09.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/freehms_women_p09.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/gincdif_men_p09.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/gincdif_women_p09.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/freehms_men_isco_p09.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/freehms_women_isco_p09.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/freehms_men_p09_inv.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/freehms_women_p09_inv.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/res_md_gpt.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/res_jac_gpt.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/freehms_men_llama_7.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/freehms_women_llama_7.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/gincdif_gpt.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/gincdif_llama_7b.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/freehms_men_p09_t2.png)

![大型语言模型是否具有变色龙般的适应性？](../../../paper_images/2405.19323/freehms_women_p09_t2.png)

[Arxiv](https://arxiv.org/abs/2405.19323)