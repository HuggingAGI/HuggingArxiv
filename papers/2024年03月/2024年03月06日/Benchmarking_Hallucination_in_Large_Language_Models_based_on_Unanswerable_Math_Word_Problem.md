# 本研究通过利用无解数学题，对大型语言模型中出现的“幻想”现象进行基准评估，旨在深入理解并量化其在面对这类问题时的错误生成表现。

发布时间：2024年03月06日

`LLM应用`

> Benchmarking Hallucination in Large Language Models based on Unanswerable Math Word Problem

# 摘要

> LLMs在应对各类NLP任务时表现出极高效率，然而在面对模糊情境时容易出现臆断性的错误推测，称为“幻觉”。本研究针对此问题，提出了一种新颖的基于无解数学题目的方法，用于评估LLMs在QA任务中的幻觉现象，并创造性地构建了含有5200道涵盖五类问题的UMWP数据集。我们设计了一种融合文本相似性和数学表达检测的评估方案，以此判断LLM是否认识到题目无解。通过对包括GPT-3、InstructGPT、LLaMA和Claude等31款LLMs进行大规模实验，结果显示采用上下文学习及带有真实人类反馈的强化学习（RLHF）训练能显著提升模型抵抗幻觉的能力。实验揭示，运用MWP是评估LLMs幻觉问题的一种可靠而高效的方法，相关代码与数据已开放在https://github.com/Yuki-Asuuna/UMWP。

> Large language models (LLMs) are highly effective in various natural language processing (NLP) tasks. However, they are susceptible to producing unreliable conjectures in ambiguous contexts called hallucination. This paper presents a new method for evaluating LLM hallucination in Question Answering (QA) based on the unanswerable math word problem (MWP). To support this approach, we innovatively develop a dataset called Unanswerable Math Word Problem (UMWP) which comprises 5200 questions across five categories. We developed an evaluation methodology combining text similarity and mathematical expression detection to determine whether LLM considers the question unanswerable. The results of extensive experiments conducted on 31 LLMs, including GPT-3, InstructGPT, LLaMA, and Claude, demonstrate that in-context learning and reinforcement learning with human feedback (RLHF) training significantly enhance the model's ability to avoid hallucination. We show that utilizing MWP is a reliable and effective approach to assess hallucination. Our code and data are available at https://github.com/Yuki-Asuuna/UMWP.

[Arxiv](https://arxiv.org/abs/2403.03558)