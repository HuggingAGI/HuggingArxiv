# TextSquare：扩展文本导向的视觉指令调优

发布时间：2024年04月19日

`LLM应用` `视觉问答` `数据集构建`

> TextSquare: Scaling up Text-Centric Visual Instruction Tuning

# 摘要

> 随着多模态大型语言模型（MLLMs）的进展，文本中心视觉问答（VQA）领域取得了显著突破。尽管如此，开源模型相较于GPT4V和Gemini等顶尖模型仍有不足，这在一定程度上归咎于高质量指令调优数据的匮乏。为了解决这一问题，我们提出了一种创新方法，用于构建一个庞大且高质量的指令调优数据集——Square-10M，该数据集利用闭源MLLMs生成。整个数据构建流程，即Square流程，分为自我提问、解答、推理和评估四个阶段。通过Square-10M的实验，我们得出了三项重要发现：首先，我们的模型TextSquare在OCRBench上达到了62.2%的准确率，大幅超越了先前的开源顶尖模型，并为文本中心MLLMs设定了新的基准。其次，TextSquare在10个文本中心基准测试中的6个上超越了GPT4V和Gemini等顶级模型。此外，我们还证实了VQA推理数据在提供特定问题全面上下文洞察中的核心作用，这不仅提升了准确度，还显著减少了幻觉现象。具体来说，TextSquare在四个通用VQA和幻觉评估数据集上的平均准确率达到了75.1%，超越了之前的顶尖模型。最后，文本中心VQA数据集规模的扩展呈现出明显的规律：指令调优数据量的指数级增长与模型性能的提升成正比，这进一步证实了大规模和高质量数据集的必要性，以及Square-10M的卓越价值。

> Text-centric visual question answering (VQA) has made great strides with the development of Multimodal Large Language Models (MLLMs), yet open-source models still fall short of leading models like GPT4V and Gemini, partly due to a lack of extensive, high-quality instruction tuning data. To this end, we introduce a new approach for creating a massive, high-quality instruction-tuning dataset, Square-10M, which is generated using closed-source MLLMs. The data construction process, termed Square, consists of four steps: Self-Questioning, Answering, Reasoning, and Evaluation. Our experiments with Square-10M led to three key findings: 1) Our model, TextSquare, considerably surpasses open-source previous state-of-the-art Text-centric MLLMs and sets a new standard on OCRBench(62.2%). It even outperforms top-tier models like GPT4V and Gemini in 6 of 10 text-centric benchmarks. 2) Additionally, we demonstrate the critical role of VQA reasoning data in offering comprehensive contextual insights for specific questions. This not only improves accuracy but also significantly mitigates hallucinations. Specifically, TextSquare scores an average of 75.1% across four general VQA and hallucination evaluation datasets, outperforming previous state-of-the-art models. 3) Notably, the phenomenon observed in scaling text-centric VQA datasets reveals a vivid pattern: the exponential increase of instruction tuning data volume is directly proportional to the improvement in model performance, thereby validating the necessity of the dataset scale and the high quality of Square-10M.

![TextSquare：扩展文本导向的视觉指令调优](../../../paper_images/2404.12803/x1.png)

![TextSquare：扩展文本导向的视觉指令调优](../../../paper_images/2404.12803/x2.png)

![TextSquare：扩展文本导向的视觉指令调优](../../../paper_images/2404.12803/x3.png)

![TextSquare：扩展文本导向的视觉指令调优](../../../paper_images/2404.12803/x4.png)

![TextSquare：扩展文本导向的视觉指令调优](../../../paper_images/2404.12803/x5.png)

[Arxiv](https://arxiv.org/abs/2404.12803)