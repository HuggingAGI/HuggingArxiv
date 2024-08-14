# LongWriter：激发长上下文 LLM 生成万字长文的能力

发布时间：2024年08月13日

`LLM应用` `人工智能` `数据科学`

> LongWriter: Unleashing 10,000+ Word Generation from Long Context LLMs

# 摘要

> 当前的长上下文大型语言模型 (LLM) 虽能处理多达 100,000 个令牌的输入，但在生成超过 2,000 字的输出时仍显吃力。我们通过实验发现，模型的生成能力受限于其在监督微调 (SFT) 期间所接触的样本长度。简言之，现有 SFT 数据集中长输出示例的匮乏限制了模型的输出能力。为此，我们推出了 AgentWrite，一个基于代理的流水线，它将超长生成任务分解为子任务，使 LLM 能够生成超过 20,000 字的连贯文本。借助 AgentWrite，我们创建了 LongWriter-6k 数据集，包含 6,000 个 SFT 数据，输出长度从 2k 到 32k 字不等。通过整合这一数据集进行模型训练，我们成功将模型的输出长度扩展至 10,000 字以上，且保持了输出质量。此外，我们还开发了 LongBench-Write 基准，用于评估超长生成能力。我们的 9B 参数模型，经 DPO 优化后，在该基准上表现卓越，甚至超越了更大规模的专有模型。我们的研究表明，现有的长上下文 LLM 已具备更大的输出潜力，只需在模型对齐过程中使用更长的输出数据，即可释放这一潜能。相关代码和模型已公开在：https://github.com/THUDM/LongWriter。

> Current long context large language models (LLMs) can process inputs up to 100,000 tokens, yet struggle to generate outputs exceeding even a modest length of 2,000 words. Through controlled experiments, we find that the model's effective generation length is inherently bounded by the sample it has seen during supervised fine-tuning (SFT). In other words, their output limitation is due to the scarcity of long-output examples in existing SFT datasets. To address this, we introduce AgentWrite, an agent-based pipeline that decomposes ultra-long generation tasks into subtasks, enabling off-the-shelf LLMs to generate coherent outputs exceeding 20,000 words. Leveraging AgentWrite, we construct LongWriter-6k, a dataset containing 6,000 SFT data with output lengths ranging from 2k to 32k words. By incorporating this dataset into model training, we successfully scale the output length of existing models to over 10,000 words while maintaining output quality. We also develop LongBench-Write, a comprehensive benchmark for evaluating ultra-long generation capabilities. Our 9B parameter model, further improved through DPO, achieves state-of-the-art performance on this benchmark, surpassing even much larger proprietary models. In general, our work demonstrates that existing long context LLM already possesses the potential for a larger output window--all you need is data with extended output during model alignment to unlock this capability. Our code & models are at: https://github.com/THUDM/LongWriter.

[Arxiv](https://arxiv.org/abs/2408.07055)