# 你的模型是否真的擅长数学推理？通过检查清单来评估其数学推理能力。

发布时间：2024年07月11日

`LLM应用` `人工智能`

> Is Your Model Really A Good Math Reasoner? Evaluating Mathematical Reasoning with Checklist

# 摘要

> 大型语言模型（LLM）的卓越数学推理能力是其核心优势之一。然而，如何全面评估这些能力，并在实际应用中体现用户体验，成为了一个亟待解决的问题。当前的评估标准过于侧重问题解决，可能导致模型过拟合，无法真实反映其数学推理水平。为此，我们提出了MATHCHECK，一个专为测试任务泛化和推理鲁棒性设计的检查清单，以及一个高效的自动生成工具。MATHCHECK涵盖多种数学推理任务和鲁棒性测试，旨在全面评估模型的数学推理能力和行为表现。我们基于MATHCHECK开发了MATHCHECK-GSM和MATHCHECK-GEO，分别针对数学文本和多模态推理进行评估，是对现有基准如GSM8k、GeoQA等的升级。通过这些工具，我们评估了超过20个LLM和11个MLLM的综合数学推理能力。结果显示，尽管如GPT-4o等前沿模型在多项测试中表现出色，但其他模型家族的表现则显著下滑。进一步实验证明，MATHCHECK相比传统基准更能准确反映模型的真实数学能力，并更线性地展现数学智能，验证了我们的设计理念。借助MATHCHECK，我们能够深入进行模型行为分析，全面探究其数学推理能力。

> Exceptional mathematical reasoning ability is one of the key features that demonstrate the power of large language models (LLMs). How to comprehensively define and evaluate the mathematical abilities of LLMs, and even reflect the user experience in real-world scenarios, has emerged as a critical issue. Current benchmarks predominantly concentrate on problem-solving capabilities, which presents a substantial risk of model overfitting and fails to accurately represent genuine mathematical reasoning abilities. In this paper, we argue that if a model really understands a problem, it should be robustly and readily applied across a diverse array of tasks. Motivated by this, we introduce MATHCHECK, a well-designed checklist for testing task generalization and reasoning robustness, as well as an automatic tool to generate checklists efficiently. MATHCHECK includes multiple mathematical reasoning tasks and robustness test types to facilitate a comprehensive evaluation of both mathematical reasoning ability and behavior testing. Utilizing MATHCHECK, we develop MATHCHECK-GSM and MATHCHECK-GEO to assess mathematical textual reasoning and multi-modal reasoning capabilities, respectively, serving as upgraded versions of benchmarks including GSM8k, GeoQA, UniGeo, and Geometry3K. We adopt MATHCHECK-GSM and MATHCHECK-GEO to evaluate over 20 LLMs and 11 MLLMs, assessing their comprehensive mathematical reasoning abilities. Our results demonstrate that while frontier LLMs like GPT-4o continue to excel in various abilities on the checklist, many other model families exhibit a significant decline. Further experiments indicate that, compared to traditional math benchmarks, MATHCHECK better reflects true mathematical abilities and represents mathematical intelligence more linearly, thereby supporting our design. On our MATHCHECK, we can easily conduct detailed behavior analysis to deeply investigate models.

![你的模型是否真的擅长数学推理？通过检查清单来评估其数学推理能力。](../../../paper_images/2407.08733/x1.png)

![你的模型是否真的擅长数学推理？通过检查清单来评估其数学推理能力。](../../../paper_images/2407.08733/x2.png)

![你的模型是否真的擅长数学推理？通过检查清单来评估其数学推理能力。](../../../paper_images/2407.08733/x3.png)

![你的模型是否真的擅长数学推理？通过检查清单来评估其数学推理能力。](../../../paper_images/2407.08733/x4.png)

![你的模型是否真的擅长数学推理？通过检查清单来评估其数学推理能力。](../../../paper_images/2407.08733/x5.png)

![你的模型是否真的擅长数学推理？通过检查清单来评估其数学推理能力。](../../../paper_images/2407.08733/x6.png)

![你的模型是否真的擅长数学推理？通过检查清单来评估其数学推理能力。](../../../paper_images/2407.08733/x7.png)

![你的模型是否真的擅长数学推理？通过检查清单来评估其数学推理能力。](../../../paper_images/2407.08733/x8.png)

![你的模型是否真的擅长数学推理？通过检查清单来评估其数学推理能力。](../../../paper_images/2407.08733/x9.png)

![你的模型是否真的擅长数学推理？通过检查清单来评估其数学推理能力。](../../../paper_images/2407.08733/case_geo_diagram.jpg)

[Arxiv](https://arxiv.org/abs/2407.08733)