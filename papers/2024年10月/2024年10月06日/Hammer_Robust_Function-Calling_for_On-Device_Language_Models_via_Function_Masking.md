# Hammer：利用函数掩码技术，为设备上的语言模型提供更稳健的函数调用功能。

发布时间：2024年10月06日

`Agent` `软件开发` `人工智能`

> Hammer: Robust Function-Calling for On-Device Language Models via Function Masking

# 摘要

> 大型语言模型在结合外部工具和API调用时，展现了作为自主代理的强大能力。然而，要充分发挥其执行复杂任务的潜力，关键在于提升其函数调用能力。本文指出，现有模型在不同基准测试中的性能差异显著，常因特定命名惯例而误导。为此，我们推出了Hammer，一种专为设备上函数调用设计的新型基础模型。Hammer通过增强数据集和函数掩码技术，提高了对无关函数的识别能力，减少了误导。实证评估表明，Hammer不仅超越了现有大型模型，还在多样基准测试中展现了卓越的泛化能力，达到了最先进水平。我们的开源贡献包括专用数据集、调优框架和Hammer模型，为函数调用性能树立了新标杆。

> Large language models have demonstrated impressive value in performing as autonomous agents when equipped with external tools and API calls. Nonetheless, effectively harnessing their potential for executing complex tasks crucially relies on enhancements in their function calling capabilities. This paper identifies a critical gap in existing function calling models, where performance varies significantly across benchmarks, often due to being misled by specific naming conventions. To address such an issue, we introduce Hammer, a novel family of foundation models specifically engineered for on-device function calling. Hammer employs an augmented dataset that enhances models' sensitivity to irrelevant functions and incorporates function masking techniques to minimize misleading. Our empirical evaluations reveal that Hammer not only outperforms larger models but also demonstrates robust generalization across diverse benchmarks, achieving sota results. Our open source contributions include a specialized dataset for irrelevance detection, a tuning framework for enhanced generalization, and the Hammer models, establishing a new standard for function calling performance.

[Arxiv](https://arxiv.org/abs/2410.04587)