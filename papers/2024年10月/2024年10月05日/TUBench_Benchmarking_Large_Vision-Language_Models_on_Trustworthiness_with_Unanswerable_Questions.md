# TUBench：针对大型视觉语言模型在处理无法回答问题时的可信度进行基准测试

发布时间：2024年10月05日

`LLM应用` `人工智能` `计算机视觉`

> TUBench: Benchmarking Large Vision-Language Models on Trustworthiness with Unanswerable Questions

# 摘要

> 大型视觉语言模型 (LVLMs) 在视觉和语言理解方面取得了显著进展，但仍面临幻觉问题，即生成与输入不符的内容。传统基准如 MME 和 POPE 通过可回答的视觉问答 (VQA) 问题评估幻觉，但忽略了因图像信息不足而无法回答的问题。为此，我们推出了 TUBench，一个专门用于评估 LVLMs 在无法回答问题上的可靠性的基准。TUBench 包含大量精心设计的高质量无法回答的问题，涵盖代码、常识、几何和数学推理等多个领域。我们对 28 个领先模型进行了全面评估，其中 Gemini-1.5-Pro 以 69.2% 的平均准确率领先，GPT-4o 以 66.7% 紧随其后。TUBench 可在 https://github.com/NLPCode/TUBench 获取。

> Large Vision-Language Models (LVLMs) have achieved remarkable progress on visual perception and linguistic interpretation. Despite their impressive capabilities across various tasks, LVLMs still suffer from the issue of hallucination, which involves generating content that is incorrect or unfaithful to the visual or textual inputs. Traditional benchmarks, such as MME and POPE, evaluate hallucination in LVLMs within the scope of Visual Question Answering (VQA) using answerable questions. However, some questions are unanswerable due to insufficient information in the images, and the performance of LVLMs on such unanswerable questions remains underexplored. To bridge this research gap, we propose TUBench, a benchmark specifically designed to evaluate the reliability of LVLMs using unanswerable questions. TUBench comprises an extensive collection of high-quality, unanswerable questions that are meticulously crafted using ten distinct strategies. To thoroughly evaluate LVLMs, the unanswerable questions in TUBench are based on images from four diverse domains as visual contexts: screenshots of code snippets, natural images, geometry diagrams, and screenshots of statistical tables. These unanswerable questions are tailored to test LVLMs' trustworthiness in code reasoning, commonsense reasoning, geometric reasoning, and mathematical reasoning related to tables, respectively. We conducted a comprehensive quantitative evaluation of 28 leading foundational models on TUBench, with Gemini-1.5-Pro, the top-performing model, achieving an average accuracy of 69.2%, and GPT-4o, the third-ranked model, reaching 66.7% average accuracy, in determining whether questions are answerable. TUBench is available at https://github.com/NLPCode/TUBench.

[Arxiv](https://arxiv.org/abs/2410.04107)