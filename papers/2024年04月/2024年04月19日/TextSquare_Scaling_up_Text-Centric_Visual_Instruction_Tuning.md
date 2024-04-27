# TextSquare：全面提升基于文本的视觉指令调优

发布时间：2024年04月19日

`LLM应用` `视觉问答`

> TextSquare: Scaling up Text-Centric Visual Instruction Tuning

# 摘要

> 随着多模态大型语言模型（MLLMs）的发展，以文本为核心的视觉问答（VQA）领域取得了显著进展。但开源模型与 GPT4V 和 Gemini 等行业佼佼者相比仍有差距，这在一定程度上归因于缺少大量且优质的指令调优数据。为了解决这一问题，我们提出了一种创新的方法，用于创建一个庞大且高质量的指令调优数据集 Square-10M，该数据集利用闭源 MLLMs 生成。数据构建流程，即 Square 流程，包含自我提问、解答、推理和评估四个阶段。通过 Square-10M 的实验，我们得出了三项重要发现：首先，我们的模型 TextSquare 显著超越了此前开源的最先进文本中心 MLLMs，在 OCRBench 上创造了新的记录（62.2%），并在 10 个文本中心基准测试中的 6 项上超越了 GPT4V 和 Gemini 等顶尖模型。其次，我们证实了 VQA 推理数据在提供针对特定问题的综合上下文洞察中的关键性作用，这不仅提升了准确度，还显著减少了幻觉现象。具体来说，TextSquare 在四个通用 VQA 和幻觉评估数据集上的平均得分达到 75.1%，超越了此前的最先进模型。最后，我们在扩展文本中心 VQA 数据集时观察到的现象呈现出明显的规律：指令调优数据量的指数级增长与模型性能的提升成正比，这进一步证实了数据集规模和 Square-10M 高质量的重要性。

> Text-centric visual question answering (VQA) has made great strides with the development of Multimodal Large Language Models (MLLMs), yet open-source models still fall short of leading models like GPT4V and Gemini, partly due to a lack of extensive, high-quality instruction tuning data. To this end, we introduce a new approach for creating a massive, high-quality instruction-tuning dataset, Square-10M, which is generated using closed-source MLLMs. The data construction process, termed Square, consists of four steps: Self-Questioning, Answering, Reasoning, and Evaluation. Our experiments with Square-10M led to three key findings: 1) Our model, TextSquare, considerably surpasses open-source previous state-of-the-art Text-centric MLLMs and sets a new standard on OCRBench(62.2%). It even outperforms top-tier models like GPT4V and Gemini in 6 of 10 text-centric benchmarks. 2) Additionally, we demonstrate the critical role of VQA reasoning data in offering comprehensive contextual insights for specific questions. This not only improves accuracy but also significantly mitigates hallucinations. Specifically, TextSquare scores an average of 75.1% across four general VQA and hallucination evaluation datasets, outperforming previous state-of-the-art models. 3) Notably, the phenomenon observed in scaling text-centric VQA datasets reveals a vivid pattern: the exponential increase of instruction tuning data volume is directly proportional to the improvement in model performance, thereby validating the necessity of the dataset scale and the high quality of Square-10M.

![TextSquare：全面提升基于文本的视觉指令调优](../../../paper_images/2404.12803/x1.png)

![TextSquare：全面提升基于文本的视觉指令调优](../../../paper_images/2404.12803/x2.png)

![TextSquare：全面提升基于文本的视觉指令调优](../../../paper_images/2404.12803/x3.png)

![TextSquare：全面提升基于文本的视觉指令调优](../../../paper_images/2404.12803/x4.png)

![TextSquare：全面提升基于文本的视觉指令调优](../../../paper_images/2404.12803/x5.png)

[Arxiv](https://arxiv.org/abs/2404.12803)