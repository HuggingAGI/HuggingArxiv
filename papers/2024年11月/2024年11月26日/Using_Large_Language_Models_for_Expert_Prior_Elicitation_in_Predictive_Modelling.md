# 在预测建模中运用大型语言模型来实现专家先验启发

发布时间：2024年11月26日

`LLM应用` `临床研究`

> Using Large Language Models for Expert Prior Elicitation in Predictive Modelling

# 摘要

> 大型语言模型（LLMs）通过在多样化数据上的训练，有效地获取了众多领域的广泛信息。然而，其计算的复杂性、高昂的成本以及缺乏透明度，阻碍了它们在专业任务中的直接运用。像在临床研究领域，获取专家注释或者关于预测模型的先验知识，往往既费钱又费时。本研究建议利用 LLMs 来获取预测模型的专家先验分布。此方法也为上下文学习提供了替代选择，在这种学习中，语言模型的任务是直接进行预测。我们对 LLM 引出的先验和无信息先验进行了比较，评估了 LLMs 是否能真实生成参数分布，并提出了用于上下文学习和先验引出的模型选择策略。我们的发现表明，在低数据环境下，与无信息先验相比，LLM 引出的先验参数分布大幅降低了预测误差。应用于临床问题时，这意味着所需的生物样本减少，降低了成本和资源。先验引出始终表现更优，且在更低成本下比上下文学习更可靠，使其成为我们设定中的首选替代方案。我们在包括临床应用的各种用例中展示了该方法的实用性。对于感染预测，使用 LLM 引出的先验，在达到与无信息先验相同精度的情况下，所需标签数量减少了 55%，且在研究中提前了 200 天。

> Large language models (LLMs), trained on diverse data effectively acquire a breadth of information across various domains. However, their computational complexity, cost, and lack of transparency hinder their direct application for specialised tasks. In fields such as clinical research, acquiring expert annotations or prior knowledge about predictive models is often costly and time-consuming. This study proposes using LLMs to elicit expert prior distributions for predictive models. This approach also provides an alternative to in-context learning, where language models are tasked with making predictions directly. We compare LLM-elicited and uninformative priors, evaluate whether LLMs truthfully generate parameter distributions, and propose a model selection strategy for in-context learning and prior elicitation. Our findings show that LLM-elicited prior parameter distributions significantly reduce predictive error compared to uninformative priors in low-data settings. Applied to clinical problems, this translates to fewer required biological samples, lowering cost and resources. Prior elicitation also consistently outperforms and proves more reliable than in-context learning at a lower cost, making it a preferred alternative in our setting. We demonstrate the utility of this method across various use cases, including clinical applications. For infection prediction, using LLM-elicited priors reduced the number of required labels to achieve the same accuracy as an uninformative prior by 55%, at 200 days earlier in the study.

[Arxiv](https://arxiv.org/abs/2411.17284)