# 扩展摘要领域：借助大型语言模型提升长文本抽取式摘要的效率

发布时间：2024年08月28日

`LLM应用` `数字内容管理`

> Scaling Up Summarization: Leveraging Large Language Models for Long Text Extractive Summarization

# 摘要

> 在数字文本爆炸性增长的时代，高效摘要工具变得至关重要。尽管大型语言模型 (LLM) 在 NLP 任务中表现出色，但其在抽取式摘要中的应用仍有待深入。本文推出的 EYEGLAXS 框架，专为长文本的抽取式摘要设计，采用 LLAMA2-7B 和 ChatGLM2-6B 模型，确保事实准确与语法正确，避免了生成式方法的常见问题。通过集成 Flash Attention 和参数高效微调 (PEFT) 技术，EYEGLAXS 有效应对了 LLM 的计算与资源挑战，并在 PubMed 和 ArXiv 等数据集上刷新了性能记录。此外，我们的研究还探讨了 LLM 在不同序列长度处理上的适应性及其在小型数据集上的训练效率，为抽取式文本摘要领域树立了新标杆，并启发了未来研究的新方向。

> In an era where digital text is proliferating at an unprecedented rate, efficient summarization tools are becoming indispensable. While Large Language Models (LLMs) have been successfully applied in various NLP tasks, their role in extractive text summarization remains underexplored. This paper introduces EYEGLAXS (Easy Yet Efficient larGe LAnguage model for eXtractive Summarization), a framework that leverages LLMs, specifically LLAMA2-7B and ChatGLM2-6B, for extractive summarization of lengthy text documents. Instead of abstractive methods, which often suffer from issues like factual inaccuracies and hallucinations, EYEGLAXS focuses on extractive summarization to ensure factual and grammatical integrity. Utilizing state-of-the-art techniques such as Flash Attention and Parameter-Efficient Fine-Tuning (PEFT), EYEGLAXS addresses the computational and resource challenges typically associated with LLMs. The system sets new performance benchmarks on well-known datasets like PubMed and ArXiv. Furthermore, we extend our research through additional analyses that explore the adaptability of LLMs in handling different sequence lengths and their efficiency in training on smaller datasets. These contributions not only set a new standard in the field but also open up promising avenues for future research in extractive text summarization.

[Arxiv](https://arxiv.org/abs/2408.15801)