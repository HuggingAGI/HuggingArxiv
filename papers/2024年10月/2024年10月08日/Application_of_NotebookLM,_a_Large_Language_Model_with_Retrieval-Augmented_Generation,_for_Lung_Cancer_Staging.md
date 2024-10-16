# NotebookLM，一款结合检索增强生成技术的大型语言模型，正被用于肺癌分期研究。

发布时间：2024年10月08日

`RAG` `放射学`

> Application of NotebookLM, a Large Language Model with Retrieval-Augmented Generation, for Lung Cancer Staging

# 摘要

> 在放射学领域，大型语言模型如 ChatGPT 正迅速成为焦点，但其临床应用的可靠性因幻觉和引用不足等问题而受到质疑。为此，我们探索了最新的检索增强生成技术 (RAG)，使模型能引用可靠的外部知识 (REK)。本研究特别评估了新推出的 RAG-LLM，NotebookLM，在肺癌分期中的表现。我们总结了日本的肺癌分期指南作为 REK 提供给 NotebookLM，并让其根据 CT 结果对 100 个虚构病例进行分期。同时，我们使用 GPT-4 Omni (GPT-4o) 进行相同任务，比较有和无 REK 的情况。结果显示，NotebookLM 的诊断准确率达 86%，远超 GPT-4o 的 39%（有 REK）和 25%（无 REK）。此外，NotebookLM 在 REK 中查找参考位置的准确率高达 95%。结论指出，NotebookLM 通过 REK 成功实现了肺癌分期，表现优于 GPT-4o，并能高效辅助放射科医生评估其响应的可靠性，减少幻觉风险。这凸显了 RAG-LLM 在图像诊断中的巨大潜力。

> Purpose: In radiology, large language models (LLMs), including ChatGPT, have recently gained attention, and their utility is being rapidly evaluated. However, concerns have emerged regarding their reliability in clinical applications due to limitations such as hallucinations and insufficient referencing. To address these issues, we focus on the latest technology, retrieval-augmented generation (RAG), which enables LLMs to reference reliable external knowledge (REK). Specifically, this study examines the utility and reliability of a recently released RAG-equipped LLM (RAG-LLM), NotebookLM, for staging lung cancer.
  Materials and methods: We summarized the current lung cancer staging guideline in Japan and provided this as REK to NotebookLM. We then tasked NotebookLM with staging 100 fictional lung cancer cases based on CT findings and evaluated its accuracy. For comparison, we performed the same task using a gold-standard LLM, GPT-4 Omni (GPT-4o), both with and without the REK.
  Results: NotebookLM achieved 86% diagnostic accuracy in the lung cancer staging experiment, outperforming GPT-4o, which recorded 39% accuracy with the REK and 25% without it. Moreover, NotebookLM demonstrated 95% accuracy in searching reference locations within the REK.
  Conclusion: NotebookLM successfully performed lung cancer staging by utilizing the REK, demonstrating superior performance compared to GPT-4o. Additionally, it provided highly accurate reference locations within the REK, allowing radiologists to efficiently evaluate the reliability of NotebookLM's responses and detect possible hallucinations. Overall, this study highlights the potential of NotebookLM, a RAG-LLM, in image diagnosis.

[Arxiv](https://arxiv.org/abs/2410.10869)