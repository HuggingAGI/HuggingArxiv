# 大型音频-语言模型真的能听懂吗？通过多任务评估和逐步音频推理，我们正努力解决幻觉问题。

发布时间：2024年10月21日

`LLM应用` `音频处理` `语音识别`

> Can Large Audio-Language Models Truly Hear? Tackling Hallucinations with Multi-Task Assessment and Stepwise Audio Reasoning

# 摘要

> 近期，大规模音频-语言模型（LALM）在理解和推理音频与语音信息方面表现出色。然而，这些模型仍面临幻觉、顺序识别错误和声源归因错误等挑战，影响了其可靠性和实际应用。为此，我们设计了三个任务：对象存在性、时间顺序和对象属性，以系统评估模型对关键音频信息的理解。实验结果显示，模型在这些基本任务上存在局限，凸显了改进模型在识别声音事件、确定事件序列和识别声源方面的必要性。为提升性能，我们提出了一种多轮链式思维方法，显著改善了模型在各项任务中的表现。

> Recent advancements in large audio-language models (LALMs) have shown impressive capabilities in understanding and reasoning about audio and speech information. However, these models still face challenges, including hallucinating non-existent sound events, misidentifying the order of sound events, and incorrectly attributing sound sources, which undermine their reliability and real-world application. To systematically evaluate these issues, we propose three distinct tasks: object existence, temporal order, and object attribute within audio. These tasks assess the models' comprehension of critical audio information aspects. Our experimental results reveal limitations in these fundamental tasks, underscoring the need for better models in recognizing specific sound events, determining event sequences, and identifying sound sources. To improve performance in these areas, we introduce a multi-turn chain-of-thought approach, which demonstrates significantly improved model performance across the proposed tasks.

[Arxiv](https://arxiv.org/abs/2410.16130)