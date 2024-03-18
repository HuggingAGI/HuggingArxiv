# AdaShield方案：针对多模态大型语言模型，利用自适应防护提示技术有效抵御基于结构的攻击威胁。

发布时间：2024年03月14日

`LLM应用` `人工智能安全` `多模态模型`

> AdaShield: Safeguarding Multimodal Large Language Models from Structure-based Attack via Adaptive Shield Prompting

> 随着 MLLMs 的普及应用，对其安全防护的需求日益迫切。然而，融合了多元模态的 MLLMs 暴露于新的安全隐患之中，容易遭受基于结构的越狱攻击，即通过向图像中植入“有害文本”等语义信息来误导模型。本文的目标是抵御这类风险，为此我们创新性地提出了\textbf{AdaShield}——一种自适应防御提示技术，只需在输入前端附加防御型提示，无需对 MLLMs 进行微调或增设额外模块（例如后期内容检测器），即可有效对抗基于结构的越狱攻击。起始阶段，我们精心设计了一款静态防御提示，逐层深入分析图像与指令内容，并针对恶意查询制定了应对策略。更进一步，我们构建了一个包含目标 MLLM 与基于 LLM 的防御提示生成器（Defender）在内的自适应自动优化框架，二者相互协作、循环迭代生成防御提示。大量实验证明，在各类主流基于结构的越狱攻击及良性数据集上，我们的方法能够显著提升 MLLMs 的抗攻击稳健性，同时保证模型在常规良性任务中的性能表现。相关代码已开源，访问地址为：https://github.com/rain305f/AdaShield。

> With the advent and widespread deployment of Multimodal Large Language Models (MLLMs), the imperative to ensure their safety has become increasingly pronounced. However, with the integration of additional modalities, MLLMs are exposed to new vulnerabilities, rendering them prone to structured-based jailbreak attacks, where semantic content (e.g., "harmful text") has been injected into the images to mislead MLLMs. In this work, we aim to defend against such threats. Specifically, we propose \textbf{Ada}ptive \textbf{Shield} Prompting (\textbf{AdaShield}), which prepends inputs with defense prompts to defend MLLMs against structure-based jailbreak attacks without fine-tuning MLLMs or training additional modules (e.g., post-stage content detector). Initially, we present a manually designed static defense prompt, which thoroughly examines the image and instruction content step by step and specifies response methods to malicious queries. Furthermore, we introduce an adaptive auto-refinement framework, consisting of a target MLLM and a LLM-based defense prompt generator (Defender). These components collaboratively and iteratively communicate to generate a defense prompt. Extensive experiments on the popular structure-based jailbreak attacks and benign datasets show that our methods can consistently improve MLLMs' robustness against structure-based jailbreak attacks without compromising the model's general capabilities evaluated on standard benign tasks. Our code is available at https://github.com/rain305f/AdaShield.

![AdaShield方案：针对多模态大型语言模型，利用自适应防护提示技术有效抵御基于结构的攻击威胁。](../../../paper_images/2403.09513/x1.png)

![AdaShield方案：针对多模态大型语言模型，利用自适应防护提示技术有效抵御基于结构的攻击威胁。](../../../paper_images/2403.09513/x2.png)

![AdaShield方案：针对多模态大型语言模型，利用自适应防护提示技术有效抵御基于结构的攻击威胁。](../../../paper_images/2403.09513/x3.png)

![AdaShield方案：针对多模态大型语言模型，利用自适应防护提示技术有效抵御基于结构的攻击威胁。](../../../paper_images/2403.09513/x4.png)

![AdaShield方案：针对多模态大型语言模型，利用自适应防护提示技术有效抵御基于结构的攻击威胁。](../../../paper_images/2403.09513/x5.png)

![AdaShield方案：针对多模态大型语言模型，利用自适应防护提示技术有效抵御基于结构的攻击威胁。](../../../paper_images/2403.09513/x6.png)

[Arxiv](https://arxiv.org/abs/2403.09513)