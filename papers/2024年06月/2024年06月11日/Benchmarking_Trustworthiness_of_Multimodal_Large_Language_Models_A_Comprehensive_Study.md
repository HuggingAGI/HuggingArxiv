# 全面评估多模态大型语言模型的信任度：深度探究

发布时间：2024年06月11日

`LLM应用

这篇论文主要关注多模态大型语言模型（MLLMs）的可信度问题，并推出了一个综合基准MultiTrust来评估这些模型在真实性、安全性、鲁棒性、公平性和隐私等方面的表现。论文通过广泛的测试揭示了MLLMs在多模态环境下的风险和问题，并强调了提升这些模型可靠性的必要性。此外，论文还发布了一个可扩展工具箱，以推动可信度研究的标准化。这些内容主要涉及LLM的应用层面，特别是在多模态环境下的应用和评估，因此应归类为LLM应用。` `人工智能` `多模态技术`

> Benchmarking Trustworthiness of Multimodal Large Language Models: A Comprehensive Study

# 摘要

> 多模态大型语言模型（MLLMs）虽在多任务中表现卓越，但其可信度问题依旧显著。当前文献对可信MLLMs的评估尚不充分，缺乏全面视角以洞察未来改进。为此，我们推出了MultiTrust，首个针对MLLMs可信度的综合基准，涵盖真实性、安全性、鲁棒性、公平性与隐私五大核心维度。该基准采用严格评估策略，兼顾多模态风险与跨模态影响，涉及32项任务及自编制数据集。通过21款现代MLLMs的广泛测试，我们揭示了先前未见的风险与问题，凸显多模态复杂性，强调需采用先进技术提升可靠性。例如，专有模型在处理视觉混淆图像时仍显吃力，易受多模态攻击；MLLMs在文本中易泄露隐私，且在推理中即使与无关图像结合，亦显露意识形态与文化偏见，显示多模态加剧了基础LLMs的内在风险。此外，我们发布了一个可扩展工具箱，旨在推动可信度研究的标准化，助力该领域未来发展。相关代码与资源已公开，详情请访问：https://multi-trust.github.io/。

> Despite the superior capabilities of Multimodal Large Language Models (MLLMs) across diverse tasks, they still face significant trustworthiness challenges. Yet, current literature on the assessment of trustworthy MLLMs remains limited, lacking a holistic evaluation to offer thorough insights into future improvements. In this work, we establish MultiTrust, the first comprehensive and unified benchmark on the trustworthiness of MLLMs across five primary aspects: truthfulness, safety, robustness, fairness, and privacy. Our benchmark employs a rigorous evaluation strategy that addresses both multimodal risks and cross-modal impacts, encompassing 32 diverse tasks with self-curated datasets. Extensive experiments with 21 modern MLLMs reveal some previously unexplored trustworthiness issues and risks, highlighting the complexities introduced by the multimodality and underscoring the necessity for advanced methodologies to enhance their reliability. For instance, typical proprietary models still struggle with the perception of visually confusing images and are vulnerable to multimodal jailbreaking and adversarial attacks; MLLMs are more inclined to disclose privacy in text and reveal ideological and cultural biases even when paired with irrelevant images in inference, indicating that the multimodality amplifies the internal risks from base LLMs. Additionally, we release a scalable toolbox for standardized trustworthiness research, aiming to facilitate future advancements in this important field. Code and resources are publicly available at: https://multi-trust.github.io/.

[Arxiv](https://arxiv.org/abs/2406.07057)