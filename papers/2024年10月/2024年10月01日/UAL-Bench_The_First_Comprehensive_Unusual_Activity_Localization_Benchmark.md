# UAL-Bench：首个全面异常活动定位基准

发布时间：2024年10月01日

`LLM应用` `视频监控` `医疗诊断`

> UAL-Bench: The First Comprehensive Unusual Activity Localization Benchmark

# 摘要

> 在视频中识别异常活动，如人为失误或监控事件，具有重要应用价值。然而，现有视频理解模型在定位这些异常时表现不佳，可能是因为预训练数据集中对这些事件的表示不足。为此，我们推出了UAL-Bench，一个包含UAG-OOPS、UAG-SSBD、UAG-FunQA三个视频数据集和一个指令调优数据集OOPS-UAG-Instruct的综合基准，旨在提升模型能力。我们评估了视频-语言模型（Vid-LLMs）、指令调优的Vid-LLMs以及视觉-语言模型与大语言模型（VLM-LLM）的集成方法。结果表明，VLM-LLM在定位短时异常事件和预测其开始时间方面表现更佳。此外，我们提出了新指标R@1，TD <= p，以改进现有评估方法。研究还揭示了长时间视频，尤其是自闭症诊断场景中的挑战，并呼吁进一步发展定位技术。我们的工作不仅为异常活动定位设立了基准，还指出了现有模型的关键挑战，为未来研究提供了方向。

> Localizing unusual activities, such as human errors or surveillance incidents, in videos holds practical significance. However, current video understanding models struggle with localizing these unusual events likely because of their insufficient representation in models' pretraining datasets. To explore foundation models' capability in localizing unusual activity, we introduce UAL-Bench, a comprehensive benchmark for unusual activity localization, featuring three video datasets: UAG-OOPS, UAG-SSBD, UAG-FunQA, and an instruction-tune dataset: OOPS-UAG-Instruct, to improve model capabilities. UAL-Bench evaluates three approaches: Video-Language Models (Vid-LLMs), instruction-tuned Vid-LLMs, and a novel integration of Vision-Language Models and Large Language Models (VLM-LLM). Our results show the VLM-LLM approach excels in localizing short-span unusual events and predicting their onset (start time) more accurately than Vid-LLMs. We also propose a new metric, R@1, TD <= p, to address limitations in existing evaluation methods. Our findings highlight the challenges posed by long-duration videos, particularly in autism diagnosis scenarios, and the need for further advancements in localization techniques. Our work not only provides a benchmark for unusual activity localization but also outlines the key challenges for existing foundation models, suggesting future research directions on this important task.

[Arxiv](https://arxiv.org/abs/2410.01180)