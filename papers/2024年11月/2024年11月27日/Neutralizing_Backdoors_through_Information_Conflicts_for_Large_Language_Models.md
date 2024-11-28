# 通过信息冲突为大型语言模型消除后门

发布时间：2024年11月27日

`LLM应用` `网络安全`

> Neutralizing Backdoors through Information Conflicts for Large Language Models

# 摘要

> 大型语言模型（LLMs）进步显著，在各类自然语言处理（NLP）任务，从理解到推理，都表现卓越。然而，它们易受后门攻击，标准查询时模型正常，特定触发激活时却会生成有害响应或意外输出。现有的后门防御常有不足，要么只检测不清除，要么依赖对触发属性的严苛假设，要么对多触发后门等高级攻击无效。本文中，我们借助内部和外部机制构建信息冲突，提出一种消除LLMs后门行为的新方法。内部，利用轻量级数据集训练冲突模型，再与被植入后门的模型融合，在模型参数内存中嵌入矛盾信息以中和恶意行为。外部，把有说服力的矛盾证据纳入提示，挑战模型内部的后门知识。在4个常用LLMs上的分类和对话任务实验结果显示，我们的方法优于8种先进的后门防御基线。能将高级后门攻击的成功率降低多达98%，同时保持干净数据准确率超90%。而且，我们的方法对自适应后门攻击具有强鲁棒性。代码发表时将开源。

> Large language models (LLMs) have seen significant advancements, achieving superior performance in various Natural Language Processing (NLP) tasks, from understanding to reasoning. However, they remain vulnerable to backdoor attacks, where models behave normally for standard queries but generate harmful responses or unintended output when specific triggers are activated. Existing backdoor defenses often suffer from drawbacks that they either focus on detection without removal, rely on rigid assumptions about trigger properties, or prove to be ineffective against advanced attacks like multi-trigger backdoors. In this paper, we present a novel method to eliminate backdoor behaviors from LLMs through the construction of information conflicts using both internal and external mechanisms. Internally, we leverage a lightweight dataset to train a conflict model, which is then merged with the backdoored model to neutralize malicious behaviors by embedding contradictory information within the model's parametric memory. Externally, we incorporate convincing contradictory evidence into the prompt to challenge the model's internal backdoor knowledge. Experimental results on classification and conversational tasks across 4 widely used LLMs demonstrate that our method outperforms 8 state-of-the-art backdoor defense baselines. We can reduce the attack success rate of advanced backdoor attacks by up to 98% while maintaining over 90% clean data accuracy. Furthermore, our method has proven to be robust against adaptive backdoor attacks. The code will be open-sourced upon publication.

[Arxiv](https://arxiv.org/abs/2411.18280)