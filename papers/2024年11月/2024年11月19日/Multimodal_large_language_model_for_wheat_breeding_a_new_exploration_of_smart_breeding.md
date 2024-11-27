# 用于小麦育种的多模态大型语言模型：智能育种的全新探索

发布时间：2024年11月19日

`RAG`

> Multimodal large language model for wheat breeding: a new exploration of smart breeding

# 摘要

> 无人机遥感技术已成为作物育种的关键技术，能实现作物表型数据的高通量、无损采集。不过，育种的多学科特性给知识挖掘带来了技术阻碍和效率难题。所以，开发智能育种目标工具以挖掘跨领域多模态数据至关重要。基于不同的预训练开源多模态大语言模型（如 Qwen-VL、InternVL、Deepseek-VL），本研究运用有监督微调（SFT）、检索增强生成（RAG）和基于人类反馈的强化学习（RLHF）技术，将跨领域知识注入多模态大语言模型，进而构建多个用于小麦育种的多模态大语言模型（WBLMs）。上述 WBLMs 采用本研究新创建的评估基准予以评估。结果显示，运用 SFT、RAG 和 RLHF 技术以及 InternVL2-8B 构建的 WBLM 性能领先。随后，利用 WBLM 开展了后续实验。消融实验表明，SFT、RAG 和 RLHF 技术的组合能够提升整体生成性能，提高生成质量，平衡生成答案的及时性与适应性，并减少幻觉和偏差。WBLM 在同时运用跨领域数据（遥感、表型、天气、种质）进行小麦产量预测时表现最佳，R2 和 RMSE 分别为 0.821 和 489.254 千克/公顷。此外，WBLM 可为表型估计、环境压力评估、目标种质筛选、栽培技术推荐和种子价格查询等任务生成专业的决策支持答案。

> UAV remote sensing technology has become a key technology in crop breeding, which can achieve high-throughput and non-destructive collection of crop phenotyping data. However, the multidisciplinary nature of breeding has brought technical barriers and efficiency challenges to knowledge mining. Therefore, it is important to develop a smart breeding goal tool to mine cross-domain multimodal data. Based on different pre-trained open-source multimodal large language models (MLLMs) (e.g., Qwen-VL, InternVL, Deepseek-VL), this study used supervised fine-tuning (SFT), retrieval-augmented generation (RAG), and reinforcement learning from human feedback (RLHF) technologies to inject cross-domain knowledge into MLLMs, thereby constructing multiple multimodal large language models for wheat breeding (WBLMs). The above WBLMs were evaluated using the newly created evaluation benchmark in this study. The results showed that the WBLM constructed using SFT, RAG and RLHF technologies and InternVL2-8B has leading performance. Then, subsequent experiments were conducted using the WBLM. Ablation experiments indicated that the combination of SFT, RAG, and RLHF technologies can improve the overall generation performance, enhance the generated quality, balance the timeliness and adaptability of the generated answer, and reduce hallucinations and biases. The WBLM performed best in wheat yield prediction using cross-domain data (remote sensing, phenotyping, weather, germplasm) simultaneously, with R2 and RMSE of 0.821 and 489.254 kg/ha, respectively. Furthermore, the WBLM can generate professional decision support answers for phenotyping estimation, environmental stress assessment, target germplasm screening, cultivation technique recommendation, and seed price query tasks.

[Arxiv](https://arxiv.org/abs/2411.15203)