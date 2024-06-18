# 幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估

发布时间：2024年06月16日

`LLM应用

理由：这篇论文介绍了一种名为AUTOHALLUSION的方法，用于自动生成基准测试，以评估大型视觉-语言模型（LVLMs）在处理图像时可能产生的幻觉问题。这种方法通过创造多样化的幻觉示例来帮助检测和控制幻觉，并对多个顶级模型进行了评估。因此，这项工作属于LLM应用类别，因为它专注于开发和应用技术来改进和测试现有的LLM模型，而不是理论研究或Agent系统的开发。` `人工智能` `图像处理`

> AUTOHALLUSION: Automatic Generation of Hallucination Benchmarks for Vision-Language Models

# 摘要

> 大型视觉-语言模型（LVLMs）有时会因图像中的特定线索而产生幻觉，错误地推理出异常或假设的对象。尽管已有一些基准测试针对此问题，但它们依赖于手工挑选的极端案例，这些案例的失败模式难以推广，且微调可能降低其有效性。为此，我们开发了AUTOHALLUSION，这是一种自动生成基准的方法，通过几种关键策略创造多样化的幻觉示例。它通过添加异常对象、保留或排除共现对象、移除紧密相关的对象等方式，利用上下文线索合成图像，并生成与语言模块先验相悖的问题。模型需克服上下文偏差以找到正确答案，错误答案则揭示了幻觉的存在。AUTOHALLUSION不仅降低了创建新基准的成本，还揭示了幻觉的常见模式和原因，为检测和控制幻觉提供了重要线索。对GPT-4V(ision)、Gemini Pro Vision、Claude 3和LLaVA-1.5等顶级模型的评估显示，在AUTOHALLUSION的测试中，幻觉诱发的成功率高达97.7%和98.7%，为解决这一问题奠定了基础。

> Large vision-language models (LVLMs) hallucinate: certain context cues in an image may trigger the language module's overconfident and incorrect reasoning on abnormal or hypothetical objects. Though a few benchmarks have been developed to investigate LVLM hallucinations, they mainly rely on hand-crafted corner cases whose fail patterns may hardly generalize, and finetuning on them could undermine their validity. These motivate us to develop the first automatic benchmark generation approach, AUTOHALLUSION, that harnesses a few principal strategies to create diverse hallucination examples. It probes the language modules in LVLMs for context cues and uses them to synthesize images by: (1) adding objects abnormal to the context cues; (2) for two co-occurring objects, keeping one and excluding the other; or (3) removing objects closely tied to the context cues. It then generates image-based questions whose ground-truth answers contradict the language module's prior. A model has to overcome contextual biases and distractions to reach correct answers, while incorrect or inconsistent answers indicate hallucinations. AUTOHALLUSION enables us to create new benchmarks at the minimum cost and thus overcomes the fragility of hand-crafted benchmarks. It also reveals common failure patterns and reasons, providing key insights to detect, avoid, or control hallucinations. Comprehensive evaluations of top-tier LVLMs, e.g., GPT-4V(ision), Gemini Pro Vision, Claude 3, and LLaVA-1.5, show a 97.7% and 98.7% success rate of hallucination induction on synthetic and real-world datasets of AUTOHALLUSION, paving the way for a long battle against hallucinations.

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/cover_pic.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/x1.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/x2.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/heatmap4.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/init.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/results.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/init.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/results.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/init.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/results.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/init.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/results.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/init.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/results.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/init.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/results.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/init.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/results.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/init.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/results.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/init.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/results.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/init.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/results.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/init.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/results.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/init.png)

![幻觉基准自动生成：AUTOHALLUSION 助力视觉-语言模型评估](../../../paper_images/2406.10900/results.png)

[Arxiv](https://arxiv.org/abs/2406.10900)