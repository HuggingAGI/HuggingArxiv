# 大型语言模型在调查回复中显露出与人类相似的社会期望倾向，这表明它们在模拟人类社会行为方面取得了显著进展。然而，这种偏差的存在也引发了对模型在处理敏感问题时可能产生的误导性影响的担忧。

发布时间：2024年05月09日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）中的内在偏见，特别是社会期望偏差，这是对LLMs理论理解的深化。通过实验框架和人格调查问卷，研究者揭示了LLMs在模拟人类行为时可能表现出的偏差，这不仅对LLMs的应用有影响，也对理解这些模型的内部工作机制和潜在局限性有重要意义。因此，这篇论文更倾向于LLM理论的范畴，因为它关注的是模型本身的特性和行为，而不是直接的应用场景或特定的技术方法。` `人工智能伦理` `心理学测试`

> Large Language Models Show Human-like Social Desirability Biases in Survey Responses

# 摘要

> 随着LLMs被广泛用于模拟人类行为，揭示其内在偏见变得至关重要。我们通过五大人格调查问卷构建了一个实验框架，意外地发现了LLMs中隐藏的社会期望偏差。实验中，我们调整了LLMs接触的问题数量，发现它们能感知到评估的时机，并倾向于在人格测试中给出更符合社会期望的答案，如提高外向性得分、降低神经质得分等。这种偏差在GPT-4/3.5、Claude 3、Llama 3和PaLM-2等模型中普遍存在，且在最新模型中更为显著。即使问题顺序随机或改写，偏差依然存在。尽管反向编码问题能减轻偏差，但无法根除，这表明偏差并非源于顺从性。我们的研究揭示了LLMs中新兴的社会期望偏差，并提醒我们在使用心理测量测试评估LLMs或将其作为人类代理时需谨慎。

> As Large Language Models (LLMs) become widely used to model and simulate human behavior, understanding their biases becomes critical. We developed an experimental framework using Big Five personality surveys and uncovered a previously undetected social desirability bias in a wide range of LLMs. By systematically varying the number of questions LLMs were exposed to, we demonstrate their ability to infer when they are being evaluated. When personality evaluation is inferred, LLMs skew their scores towards the desirable ends of trait dimensions (i.e., increased extraversion, decreased neuroticism, etc). This bias exists in all tested models, including GPT-4/3.5, Claude 3, Llama 3, and PaLM-2. Bias levels appear to increase in more recent models, with GPT-4's survey responses changing by 1.20 (human) standard deviations and Llama 3's by 0.98 standard deviations-very large effects. This bias is robust to randomization of question order and paraphrasing. Reverse-coding all the questions decreases bias levels but does not eliminate them, suggesting that this effect cannot be attributed to acquiescence bias. Our findings reveal an emergent social desirability bias and suggest constraints on profiling LLMs with psychometric tests and on using LLMs as proxies for human participants.

[Arxiv](https://arxiv.org/abs/2405.06058)