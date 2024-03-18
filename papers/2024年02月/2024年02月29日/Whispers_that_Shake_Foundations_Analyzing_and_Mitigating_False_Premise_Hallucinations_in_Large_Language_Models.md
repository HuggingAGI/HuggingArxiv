# [针对大型语言模型中出现的“虚假前提幻觉”问题，本研究深入剖析并探讨相应的缓解策略，这一现象犹如根基动摇的低语，挑战着我们对人工智能语言理解能力的认知边界。](https://arxiv.org/abs/2402.19103)

发布时间：2024年02月29日

`LLM理论`

> Whispers that Shake Foundations: Analyzing and Mitigating False Premise Hallucinations in Large Language Models

> 尽管大型语言模型（LLMs）展现出非凡能力，却难以摆脱幻觉问题，尤其是虚假前提幻觉——即模型在面对错误前提的问题时生成不实内容。本文深入剖析了这一现象，揭示了其内在机理：少量注意力头（我们标记为虚假前提头）搅扰了知识抽取流程，进而触发虚假前提幻觉。据此，我们创新性地提出了名为\textbf{FAITH}的有效方法，通过约束模型推理阶段中的虚假前提注意力头来缓解幻觉问题。令人赞叹的是，广泛的实验验证表明，只需约束模型中大约$1\%$的注意力头，就可令模型性能大幅提升近$20\%$。

> Large Language Models (LLMs) have shown impressive capabilities but still suffer from the issue of hallucinations. A significant type of this issue is the false premise hallucination, which we define as the phenomenon when LLMs generate hallucinated text when confronted with false premise questions. In this paper, we perform a comprehensive analysis of the false premise hallucination and elucidate its internal working mechanism: a small subset of attention heads (which we designate as false premise heads) disturb the knowledge extraction process, leading to the occurrence of false premise hallucination. Based on our analysis, we propose \textbf{FAITH} (\textbf{F}alse premise \textbf{A}ttention head constra\textbf{I}ining for mi\textbf{T}igating \textbf{H}allucinations), a novel and effective method to mitigate false premise hallucinations. It constrains the false premise attention heads during the model inference process. Impressively, extensive experiments demonstrate that constraining only approximately $1\%$ of the attention heads in the model yields a notable increase of nearly $20\%$ of model performance.

[Arxiv](https://arxiv.org/abs/2402.19103)