# 对大型语言模型在角色扮演时的偏差进行基准测评

发布时间：2024年11月01日

`LLM应用` `语言模型` `人工智能`

> Benchmarking Bias in Large Language Models during Role-Playing

# 摘要

> 大型语言模型（LLMs）已成为现代语言驱动应用的基石，对日常生活影响深远。利用其潜能的关键技术之一是角色扮演，LLMs 通过模拟多样角色来提升其在现实中的实用性。然而，虽然研究指出了LLM输出中存在社会偏见，但在角色扮演场景中这些偏见是否存在以及程度如何尚不明确。本文引入了BiasLens，这是一个公平测试框架，旨在系统性地揭示角色扮演时LLMs中的偏见。我们的方法借助LLMs在11个人口统计属性的综合集合中生成550个社会角色，产生33000个针对各类偏见形式的角色专属问题。这些问题包括是/否、多项选择和开放式等格式，旨在促使LLMs采用特定角色并做出相应回应。我们采用规则和LLM相结合的策略来识别有偏见的回答，并通过人工评估严格验证。以生成的问题为基准，我们对OpenAI、Mistral AI、Meta、阿里巴巴和DeepSeek发布的六个先进LLMs进行了广泛评估。我们的基准显示，所研究的LLMs中存在72716个有偏见的回答，单个模型产生的有偏见回答在7754至16963个之间，凸显了角色扮演情境中偏见的普遍存在。为支持后续研究，我们已公开了基准以及所有脚本和实验结果。

> Large Language Models (LLMs) have become foundational in modern language-driven applications, profoundly influencing daily life. A critical technique in leveraging their potential is role-playing, where LLMs simulate diverse roles to enhance their real-world utility. However, while research has highlighted the presence of social biases in LLM outputs, it remains unclear whether and to what extent these biases emerge during role-playing scenarios. In this paper, we introduce BiasLens, a fairness testing framework designed to systematically expose biases in LLMs during role-playing. Our approach uses LLMs to generate 550 social roles across a comprehensive set of 11 demographic attributes, producing 33,000 role-specific questions targeting various forms of bias. These questions, spanning Yes/No, multiple-choice, and open-ended formats, are designed to prompt LLMs to adopt specific roles and respond accordingly. We employ a combination of rule-based and LLM-based strategies to identify biased responses, rigorously validated through human evaluation. Using the generated questions as the benchmark, we conduct extensive evaluations of six advanced LLMs released by OpenAI, Mistral AI, Meta, Alibaba, and DeepSeek. Our benchmark reveals 72,716 biased responses across the studied LLMs, with individual models yielding between 7,754 and 16,963 biased responses, underscoring the prevalence of bias in role-playing contexts. To support future research, we have publicly released the benchmark, along with all scripts and experimental results.

[Arxiv](https://arxiv.org/abs/2411.00585)