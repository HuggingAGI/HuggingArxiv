# MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。

发布时间：2024年03月21日

`LLM应用` `计算机视觉`

> MathVerse: Does Your Multi-modal LLM Truly See the Diagrams in Visual Math Problems?

# 摘要

> MLLMs 凭借其在视觉环境中的出色表现为人们所瞩目，但其解决视觉数学问题的能力仍有待深入探究与评价。我们探索现有基准，在富含视觉内容的文本问题中寻找潜在助力 MLMMs 不依赖于解析输入图形直接得出答案的可能性。为此，我们创新设计了一个全方位视觉数学评测基准——MathVerse，旨在公平且深入地评估 MLLMs 的能力。我们精挑细选了2612道来自公开资源的高品质、跨学科且附带图表的数学题目，每道题目经由人工标注转换成六个信息含量各异的多模态版本，总计生成了15000个测试样本。通过这种方式，MathVerse 能够全面检验 MLLMs 究竟能否真正理解并运用图形进行数学推理及其理解程度。另外，我们还提出了一个细致入微的 Chain-of-Thought (CoT) 评估策略。不同于简单的对错判断，该策略借助 GPT-4(V) 自适应抽取关键推理步骤，并结合详尽的错误分析给每个步骤评分，以此揭示 MLLMs 在推理过程中各个环节的质量。我们期待 MathVerse 基准能为 MLLMs 未来的发展提供宝贵的独特见解，更多详情请访问项目主页：https://mathverse-cuhk.github.io。

> The remarkable progress of Multi-modal Large Language Models (MLLMs) has garnered unparalleled attention, due to their superior performance in visual contexts. However, their capabilities in visual math problem-solving remain insufficiently evaluated and understood. We investigate current benchmarks to incorporate excessive visual content within textual questions, which potentially assist MLLMs in deducing answers without truly interpreting the input diagrams. To this end, we introduce MathVerse, an all-around visual math benchmark designed for an equitable and in-depth evaluation of MLLMs. We meticulously collect 2,612 high-quality, multi-subject math problems with diagrams from publicly available sources. Each problem is then transformed by human annotators into six distinct versions, each offering varying degrees of information content in multi-modality, contributing to 15K test samples in total. This approach allows MathVerse to comprehensively assess whether and how much MLLMs can truly understand the visual diagrams for mathematical reasoning. In addition, we propose a Chain-of-Thought (CoT) evaluation strategy for a fine-grained assessment of the output answers. Rather than naively judging True or False, we employ GPT-4(V) to adaptively extract crucial reasoning steps, and then score each step with detailed error analysis, which can reveal the intermediate CoT reasoning quality by MLLMs. We hope the MathVerse benchmark may provide unique insights to guide the future development of MLLMs. Project page: https://mathverse-cuhk.github.io

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x1.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x2.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x3.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x4.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x5.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x6.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x7.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x8.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x9.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x10.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x11.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x12.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x13.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x14.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x15.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x16.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x17.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x18.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x19.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x20.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x21.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x22.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x23.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x24.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x25.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x26.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x27.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x28.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x29.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x30.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x31.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x32.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x33.png)

![MathVerse：探究多模态LLM在解决视觉数学问题时，是否真能洞悉其中的图表信息。](../../../paper_images/2403.14624/x34.png)

[Arxiv](https://arxiv.org/abs/2403.14624)