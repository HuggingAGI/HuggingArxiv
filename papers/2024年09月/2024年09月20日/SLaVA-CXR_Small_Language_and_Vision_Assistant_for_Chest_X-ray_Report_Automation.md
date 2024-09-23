# SLaVA-CXR：专为胸部 X 光报告自动化设计的小型语言与视觉助手

发布时间：2024年09月20日

`LLM应用` `放射学`

> SLaVA-CXR: Small Language and Vision Assistant for Chest X-ray Report Automation

# 摘要

> 受 LLM 成功启发，医疗领域 LLM 研究日益增多，旨在辅助临床医生。然而，医院使用闭源商业 LLM 面临隐私问题，而开源 LLM 开发需大量计算资源，这在资源有限地区尤为困难。为此，我们提出开源的 SLaVA-CXR，专用于胸部 X 光报告自动化。为高效训练，我们首创 Re$^3$Training 方法，模拟放射科医生认知发展，优化识别、推理和报告能力。同时，引入 RADEX 数据合成法，生成高质量多样化训练数据，确保隐私合规。实验证明，基于 2.7B 骨干的 SLaVA-CXR 不仅性能卓越，推理速度更提升 6 倍。

> Inspired by the success of large language models (LLMs), there is growing research interest in developing LLMs in the medical domain to assist clinicians. However, for hospitals, using closed-source commercial LLMs involves privacy issues, and developing open-source public LLMs requires large-scale computational resources, which are usually limited, especially in resource-efficient regions and low-income countries. We propose an open-source Small Language and Vision Assistant (SLaVA-CXR) that can be used for Chest X-Ray report automation. To efficiently train a small assistant, we first propose the Re$^3$Training method, which simulates the cognitive development of radiologists and optimizes the model in the Recognition, Reasoning, and Reporting training manner. Then, we introduce a data synthesis method, RADEX, which can generate a high-quality and diverse training corpus with privacy regulation compliance. The extensive experiments show that our SLaVA-CXR built on a 2.7B backbone not only outperforms but also achieves 6 times faster inference efficiency than previous state-of-the-art larger models.

[Arxiv](https://arxiv.org/abs/2409.13321)