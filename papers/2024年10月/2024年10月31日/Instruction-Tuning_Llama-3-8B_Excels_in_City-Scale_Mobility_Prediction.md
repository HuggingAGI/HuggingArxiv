# Instruction-Tuning 的 Llama-3-8B 在城市规模的移动性预测中表现卓越

发布时间：2024年10月31日

`LLM应用` `城市规划` `灾害应对`

> Instruction-Tuning Llama-3-8B Excels in City-Scale Mobility Prediction

# 摘要

> 人类移动性预测在灾害应对、城市规划和疫情预测等应用里起着关键作用。传统方法往往依赖精心设计的特定领域模型，且通常聚焦于短期预测，难以在多样的城市环境中推广。在本研究中，我们引入了 Llama-3-8B-Mob，这是一个经指令调优微调的大型语言模型，以问答形式用于长期全市移动性预测。我们用来自日本四个大都市区的大规模人类移动性数据验证了该方法，重点预测未来 15 天的个人轨迹。结果显示，Llama-3-8B-Mob 在长期人类移动性建模上表现卓越，在多个预测指标上超越了前沿水平。它还展现出强大的零样本泛化能力，即便仅在单个城市的有限样本上微调，也能有效推广到其他城市。源代码见 https://github.com/TANGHULU6/Llama3-8B-Mob 。

> Human mobility prediction plays a critical role in applications such as disaster response, urban planning, and epidemic forecasting. Traditional methods often rely on designing crafted, domain-specific models, and typically focus on short-term predictions, which struggle to generalize across diverse urban environments. In this study, we introduce Llama-3-8B-Mob, a large language model fine-tuned with instruction tuning, for long-term citywide mobility prediction -- in a Q&A manner. We validate our approach using large-scale human mobility data from four metropolitan areas in Japan, focusing on predicting individual trajectories over the next 15 days. The results demonstrate that Llama-3-8B-Mob excels in modeling long-term human mobility -- surpassing the state-of-the-art on multiple prediction metrics. It also displays strong zero-shot generalization capabilities -- effectively generalizing to other cities even when fine-tuned only on limited samples from a single city. Source codes are available at https://github.com/TANGHULU6/Llama3-8B-Mob.

[Arxiv](https://arxiv.org/abs/2410.23692)