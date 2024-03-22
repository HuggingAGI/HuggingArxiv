# RAmBLA 是一个专注于评估大型语言模型（LLM）在生物医学领域作为助手时可靠性的评估框架。

发布时间：2024年03月21日

`LLM应用` `生物医学`

> RAmBLA: A Framework for Evaluating the Reliability of LLMs as Assistants in the Biomedical Domain

> 随着LLMs在包括生物医学等各领域的广泛应用，其在现实场景下的可靠性尚待深入研究。为此，我们提出了RAmBLA这一针对生物医学LLM助手可靠性的评估框架，并考察了四个最前沿的基础LLM能否在该领域成为可靠的助手。我们发现，应对复杂提示稳健处理、具备高准确率及避免产生虚幻信息是LLM在此类情境中发挥作用的三大关键指标。我们设计了一系列贴近真实互动场景的短篇任务和需LLM生成自由文本响应的任务，并通过与真实回答的语义相似度对比，利用另一个评估用LLM来评判这些LLM的表现。

> Large Language Models (LLMs) increasingly support applications in a wide range of domains, some with potential high societal impact such as biomedicine, yet their reliability in realistic use cases is under-researched. In this work we introduce the Reliability AssesMent for Biomedical LLM Assistants (RAmBLA) framework and evaluate whether four state-of-the-art foundation LLMs can serve as reliable assistants in the biomedical domain. We identify prompt robustness, high recall, and a lack of hallucinations as necessary criteria for this use case. We design shortform tasks and tasks requiring LLM freeform responses mimicking real-world user interactions. We evaluate LLM performance using semantic similarity with a ground truth response, through an evaluator LLM.

[Arxiv](https://arxiv.org/abs/2403.14578)