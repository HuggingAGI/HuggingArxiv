# CoSafe：探究大型语言模型在多轮对话中指代消解的安全性评估

发布时间：2024年06月25日

`Agent

理由：这篇论文主要探讨了大型语言模型（LLMs）在多轮对话中的共指消解安全性问题，并构建了一个数据集来评估不同模型的安全性能。这种研究更偏向于Agent的范畴，因为它关注的是模型在交互式对话环境中的行为和安全性，特别是在多轮对话中处理共指问题的能力。这与Agent的行为和决策过程紧密相关，因此归类为Agent。` `人工智能安全` `对话系统`

> CoSafe: Evaluating Large Language Model Safety in Multi-Turn Dialogue Coreference

# 摘要

> 随着大型语言模型（LLMs）的持续进化，保障其安全性成为研究的重中之重。以往的安全测试多聚焦于单一提示攻击或目标劫持，而我们首次深入探讨了LLMs在多轮对话中共指消解的安全性问题。我们精心构建了一个包含1,400个问题、覆盖14个类别的数据集，每个问题都设计了多轮对话中的安全攻击。通过细致评估五款主流开源LLMs，我们发现，在多轮对话共指安全攻击下，LLaMA2-Chat-7b模型的攻击成功率高达56%，而Mistral-7B-Instruct模型则低至13.9%。这一结果揭示了LLMs在对话共指交互中存在的安全风险。

> As large language models (LLMs) constantly evolve, ensuring their safety remains a critical research problem. Previous red-teaming approaches for LLM safety have primarily focused on single prompt attacks or goal hijacking. To the best of our knowledge, we are the first to study LLM safety in multi-turn dialogue coreference. We created a dataset of 1,400 questions across 14 categories, each featuring multi-turn coreference safety attacks. We then conducted detailed evaluations on five widely used open-source LLMs. The results indicated that under multi-turn coreference safety attacks, the highest attack success rate was 56% with the LLaMA2-Chat-7b model, while the lowest was 13.9% with the Mistral-7B-Instruct model. These findings highlight the safety vulnerabilities in LLMs during dialogue coreference interactions.

[Arxiv](https://arxiv.org/abs/2406.17626)