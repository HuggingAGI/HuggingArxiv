# LLM 在生物医学问答中抵御错误信息的能力

发布时间：2024年10月27日

`RAG` `生物医学` `语言模型`

> LLM Robustness Against Misinformation in Biomedical Question Answering

# 摘要

> 检索增强生成（RAG）方法被用于减少大型语言模型（LLM）在问答中的虚构，其方式是检索并提供来自外部知识源的额外上下文（比如将该上下文添加到提示中）。但注入错误信息可能会误导 LLM 给出错误答案。
    在本文中，我们对四个 LLM（Gemma 2、GPT-4o-mini、Llama~3.1 和 Mixtral）在回答生物医学问题时抵御错误信息的有效性和鲁棒性进行了评估。我们从三种情形评估了是/否问题和自由形式问题的答案准确性：普通 LLM 作答（不提供上下文）、“完美”增强生成（提供正确上下文）以及提示注入攻击（提供错误上下文）。结果显示，Llama 3.1（70B 参数）在普通情形（0.651）和“完美”RAG 情形（0.802）中准确性均为最高。不过，在“完美”RAG 情形下，各模型间的准确性差距近乎消失，这表明其有可能弱化 LLM 因规模产生的有效性差异。
    我们进一步从两方面进行评估，一是 LLM 生成恶意上下文的能力，二是 LLM 抵御提示注入攻击的鲁棒性，并使用了攻击成功率（ASR）、受攻击时的准确性以及准确性下降幅度等指标。作为攻击者，我们使用相同的四个 LLM（Gemma 2、GPT-4o-mini、Llama 3.1 和 Mixtral）生成注入目标模型提示的错误上下文。有趣的是，Llama 被证明是最有效的攻击者，在目标模型中，对于普通答案致使准确性下降高达 0.48，对于“完美”RAG 致使准确性下降高达 0.63。我们的分析表明，鲁棒性排名会因评估指标的不同而有所变化，凸显了评估 LLM 对对抗性攻击的抵御能力的复杂性。

> The retrieval-augmented generation (RAG) approach is used to reduce the confabulation of large language models (LLMs) for question answering by retrieving and providing additional context coming from external knowledge sources (e.g., by adding the context to the prompt). However, injecting incorrect information can mislead the LLM to generate an incorrect answer.
  In this paper, we evaluate the effectiveness and robustness of four LLMs against misinformation - Gemma 2, GPT-4o-mini, Llama~3.1, and Mixtral - in answering biomedical questions. We assess the answer accuracy on yes-no and free-form questions in three scenarios: vanilla LLM answers (no context is provided), "perfect" augmented generation (correct context is provided), and prompt-injection attacks (incorrect context is provided). Our results show that Llama 3.1 (70B parameters) achieves the highest accuracy in both vanilla (0.651) and "perfect" RAG (0.802) scenarios. However, the accuracy gap between the models almost disappears with "perfect" RAG, suggesting its potential to mitigate the LLM's size-related effectiveness differences.
  We further evaluate the ability of the LLMs to generate malicious context on one hand and the LLM's robustness against prompt-injection attacks on the other hand, using metrics such as attack success rate (ASR), accuracy under attack, and accuracy drop. As adversaries, we use the same four LLMs (Gemma 2, GPT-4o-mini, Llama 3.1, and Mixtral) to generate incorrect context that is injected in the target model's prompt. Interestingly, Llama is shown to be the most effective adversary, causing accuracy drops of up to 0.48 for vanilla answers and 0.63 for "perfect" RAG across target models. Our analysis reveals that robustness rankings vary depending on the evaluation measure, highlighting the complexity of assessing LLM resilience to adversarial attacks.

[Arxiv](https://arxiv.org/abs/2410.21330)