# 言谈不等于行动：探讨大型语言模型在词汇蕴含识别方面的局限性

发布时间：2024年06月21日

`LLM理论

这篇论文主要探讨了大型语言模型（LLM）在理解和处理动词间的词汇蕴含关系方面的能力，特别是在不同的提示策略和零/少样本环境下的表现。研究内容涉及模型的性能评估和改进，这属于对LLM理论层面的探讨和分析，因此应归类于LLM理论。` `语言学`

> Talking the Talk Does Not Entail Walking the Walk: On the Limits of Large Language Models in Lexical Entailment Recognition

# 摘要

> 动词是语言的支柱，赋予句子结构与意义，但其复杂的语义细节一直是难题。理解动词间的词汇蕴含关系对于把握句子含义和动词特性至关重要。本研究探讨了八种大型语言模型在不同提示策略和零/少样本环境下，从WordNet和HyperLex两个词汇库中识别动词间词汇蕴含关系的能力。研究发现，尽管效果不一，这些模型在处理此类任务时表现尚佳，且少样本提示能提升其性能。然而，所有测试的大型语言模型均未能完美解决此任务，凸显了该领域进一步研究的必要性。

> Verbs form the backbone of language, providing the structure and meaning to sentences. Yet, their intricate semantic nuances pose a longstanding challenge. Understanding verb relations through the concept of lexical entailment is crucial for comprehending sentence meanings and grasping verb dynamics. This work investigates the capabilities of eight Large Language Models in recognizing lexical entailment relations among verbs through differently devised prompting strategies and zero-/few-shot settings over verb pairs from two lexical databases, namely WordNet and HyperLex. Our findings unveil that the models can tackle the lexical entailment recognition task with moderately good performance, although at varying degree of effectiveness and under different conditions. Also, utilizing few-shot prompting can enhance the models' performance. However, perfectly solving the task arises as an unmet challenge for all examined LLMs, which raises an emergence for further research developments on this topic.

[Arxiv](https://arxiv.org/abs/2406.14894)