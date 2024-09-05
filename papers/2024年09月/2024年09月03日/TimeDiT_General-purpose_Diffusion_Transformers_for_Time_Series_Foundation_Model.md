# TimeDiT：专为时间序列设计的基础模型通用扩散变换器

发布时间：2024年09月03日

`LLM应用` `时间序列分析` `人工智能`

> TimeDiT: General-purpose Diffusion Transformers for Time Series Foundation Model

# 摘要

> 随着文本和视频基石模型技术的进步，时间序列基石模型引起了广泛关注。我们开发了基于时间自回归生成Transformer架构的模型家族，这些模型在大语言模型中表现出色。尽管实证结果乐观，但现有时间序列基石模型大多仅在类似文本的精心策划的基准数据集上测试。现实世界时间序列面临独特挑战，如跨领域可变通道大小、缺失值及多分辨率数据导致的信号采样间隔变化。时间自回归解码的单向性也限制了领域知识的整合，如物理定律的偏微分方程表达。为此，我们推出了时间扩散Transformer（TimeDiT），采用去噪扩散范式，利用Transformer架构捕捉时间依赖性，通过扩散过程生成高质量样本，无需严格假设目标分布，借助新颖掩蔽方案和通道对齐策略。我们还提出了无需微调的模型编辑策略，允许在采样过程中无缝整合外部知识，无需更新模型参数。在预测、插补和异常检测等多种任务上的广泛实验验证了TimeDiT的有效性。

> With recent advances in building foundation models for texts and video data, there is a surge of interest in foundation models for time series. A family of models have been developed, utilizing a temporal auto-regressive generative Transformer architecture, whose effectiveness has been proven in Large Language Models. While the empirical results are promising, almost all existing time series foundation models have only been tested on well-curated ``benchmark'' datasets very similar to texts. However, real-world time series exhibit unique challenges, such as variable channel sizes across domains, missing values, and varying signal sampling intervals due to the multi-resolution nature of real-world data. Additionally, the uni-directional nature of temporally auto-regressive decoding limits the incorporation of domain knowledge, such as physical laws expressed as partial differential equations (PDEs). To address these challenges, we introduce the Time Diffusion Transformer (TimeDiT), a general foundation model for time series that employs a denoising diffusion paradigm instead of temporal auto-regressive generation. TimeDiT leverages the Transformer architecture to capture temporal dependencies and employs diffusion processes to generate high-quality candidate samples without imposing stringent assumptions on the target distribution via novel masking schemes and a channel alignment strategy. Furthermore, we propose a finetuning-free model editing strategy that allows the seamless integration of external knowledge during the sampling process without updating any model parameters. Extensive experiments conducted on a varity of tasks such as forecasting, imputation, and anomaly detection, demonstrate the effectiveness of TimeDiT.

[Arxiv](https://arxiv.org/abs/2409.02322)