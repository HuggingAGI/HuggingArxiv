# BlueLM-V-3B：关于移动设备上多模态大型语言模型的算法与系统协同设计

发布时间：2024年11月15日

`LLM应用` `移动平台` `模型部署`

> BlueLM-V-3B: Algorithm and System Co-Design for Multimodal Large Language Models on Mobile Devices

# 摘要

> 多模态大型语言模型（MLLMs）的出现及愈发流行，在增强日常生活的诸多方面颇具潜力，比如改善交流、助力学习以及解决问题。手机作为日常不可或缺的伴侣，是 MLLMs 最为有效且易获取的部署平台，能够无缝融入日常任务。但由于内存大小和计算能力的限制，在手机上部署 MLLMs 面临挑战，若不进行大量优化，难以实现流畅实时处理。本文中，我们推出了 BlueLM-V-3B，这是一种专为在移动平台高效部署 MLLMs 而定制的算法与系统协同设计方案。具体来说，我们重新设计了主流 MLLMs 采用的动态分辨率方案，并针对硬件感知部署进行了系统优化，以优化手机上的模型推理。BlueLM-V-3B 有以下关键亮点：（1）尺寸小：BlueLM-V-3B 拥有 27 亿参数的语言模型和 4 亿参数的视觉编码器。（2）速度快：在联发科技天玑 9300 处理器上，采用 4 位 LLM 权重量化，BlueLM-V-3B 的生成速度达 24.4 个 token/秒。（3）性能强：在参数≤40 亿的模型中，BlueLM-V-3B 在 OpenCompass 基准测试中的平均分数高达 66.1，超越了一系列参数规模大得多的模型（如 MiniCPM-V-2.6、InternVL2-8B）。

> The emergence and growing popularity of multimodal large language models (MLLMs) have significant potential to enhance various aspects of daily life, from improving communication to facilitating learning and problem-solving. Mobile phones, as essential daily companions, represent the most effective and accessible deployment platform for MLLMs, enabling seamless integration into everyday tasks. However, deploying MLLMs on mobile phones presents challenges due to limitations in memory size and computational capability, making it difficult to achieve smooth and real-time processing without extensive optimization. In this paper, we present BlueLM-V-3B, an algorithm and system co-design approach specifically tailored for the efficient deployment of MLLMs on mobile platforms. To be specific, we redesign the dynamic resolution scheme adopted by mainstream MLLMs and implement system optimization for hardware-aware deployment to optimize model inference on mobile phones. BlueLM-V-3B boasts the following key highlights: (1) Small Size: BlueLM-V-3B features a language model with 2.7B parameters and a vision encoder with 400M parameters. (2) Fast Speed: BlueLM-V-3B achieves a generation speed of 24.4 token/s on the MediaTek Dimensity 9300 processor with 4-bit LLM weight quantization. (3) Strong Performance: BlueLM-V-3B has attained the highest average score of 66.1 on the OpenCompass benchmark among models with $\leq$ 4B parameters and surpassed a series of models with much larger parameter sizes (e.g., MiniCPM-V-2.6, InternVL2-8B).

[Arxiv](https://arxiv.org/abs/2411.10640)