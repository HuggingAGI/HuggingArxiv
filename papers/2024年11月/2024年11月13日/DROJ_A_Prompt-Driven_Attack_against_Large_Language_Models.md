# DROJ：针对大型语言模型的提示驱动式攻击

发布时间：2024年11月13日

`LLM应用` `模型安全`

> DROJ: A Prompt-Driven Attack against Large Language Models

# 摘要

> 大型语言模型（LLMs）在各类自然语言处理任务中表现出色。因其基于互联网来源的数据集训练，LLMs 有时会生成不良内容，所以需要大量与人类反馈相契合来避免此类输出。即便进行了大规模的契合工作，LLMs 仍易遭受对抗性越狱攻击，这类攻击通常是被操纵的提示，旨在绕开安全机制并引发有害回应。在此，我们推出一种全新的方法——定向表示优化越狱（DROJ），它在嵌入层面优化越狱提示，将有害查询的隐藏表示转向更易引发模型肯定回应的方向。我们对 LLaMA-2-7b-chat 模型的评估显示，DROJ 实现了 100％基于关键字的攻击成功率（ASR），成功避免了直接拒绝。不过，该模型偶尔会给出重复且无价值的回应。为缓解这一情况，我们引入了一个有用的系统提示，以提升模型回应的实用性。我们的代码可在 https://github.com/Leon-Leyang/LLM-Safeguard 获取。

> Large Language Models (LLMs) have demonstrated exceptional capabilities across various natural language processing tasks. Due to their training on internet-sourced datasets, LLMs can sometimes generate objectionable content, necessitating extensive alignment with human feedback to avoid such outputs. Despite massive alignment efforts, LLMs remain susceptible to adversarial jailbreak attacks, which usually are manipulated prompts designed to circumvent safety mechanisms and elicit harmful responses. Here, we introduce a novel approach, Directed Rrepresentation Optimization Jailbreak (DROJ), which optimizes jailbreak prompts at the embedding level to shift the hidden representations of harmful queries towards directions that are more likely to elicit affirmative responses from the model. Our evaluations on LLaMA-2-7b-chat model show that DROJ achieves a 100\% keyword-based Attack Success Rate (ASR), effectively preventing direct refusals. However, the model occasionally produces repetitive and non-informative responses. To mitigate this, we introduce a helpfulness system prompt that enhances the utility of the model's responses. Our code is available at https://github.com/Leon-Leyang/LLM-Safeguard.

[Arxiv](https://arxiv.org/abs/2411.09125)