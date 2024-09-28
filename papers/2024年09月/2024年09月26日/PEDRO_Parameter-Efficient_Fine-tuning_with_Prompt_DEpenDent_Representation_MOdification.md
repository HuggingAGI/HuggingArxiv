# PEDRO：通过提示依赖表示修改实现参数高效微调

发布时间：2024年09月26日

`LLM理论` `人工智能` `云计算`

> PEDRO: Parameter-Efficient Fine-tuning with Prompt DEpenDent Representation MOdification

# 摘要

> 由于 LLM 的庞大体积，它们通常采用单一主干多租户框架部署。在这种模式下，单个 LLM 实例需通过多种参数高效微调（PEFT）模型服务多个用户或任务。尽管已有如 LoRA 等有效 PEFT 技术，但仍需一种在推理高效且在下游任务中表现优异的 PEFT 方法。本研究提出了一种名为 \underline{P}rompt D\underline{E}pen\underline{D}ent \underline{R}epresentation M\underline{O}dification (PEDRO) 的新 PEFT 方法。PEDRO 在每个 Transformer 层中集成轻量级向量生成器，根据输入提示生成向量，并通过点积操作修改 LLM 的隐藏表示，从而优化语义输出和生成内容。实验结果显示：(a) PEDRO 在使用相似参数时超越了最新 PEFT 基准。(b) 在单一主干多租户部署中，PEDRO 比 LoRA 更高效，展现出巨大的工业应用潜力。

> Due to their substantial sizes, large language models (LLMs) are typically deployed within a single-backbone multi-tenant framework. In this setup, a single instance of an LLM backbone must cater to multiple users or tasks through the application of various parameter-efficient fine-tuning (PEFT) models. Despite the availability of numerous effective PEFT techniques such as LoRA, there remains a need for a PEFT approach that achieves both high efficiency during inference and competitive performance on downstream tasks. In this research, we introduce a new and straightforward PEFT methodology named \underline{P}rompt D\underline{E}pen\underline{D}ent \underline{R}epresentation M\underline{O}dification (PEDRO). The proposed method involves integrating a lightweight vector generator into each Transformer layer, which generates vectors contingent upon the input prompts. These vectors then modify the hidden representations created by the LLM through a dot product operation, thereby influencing the semantic output and generated content of the model. Extensive experimentation across a variety of tasks indicates that: (a) PEDRO surpasses recent PEFT benchmarks when using a similar number of tunable parameters. (b) Under the single-backbone multi-tenant deployment model, PEDRO exhibits superior efficiency compared to LoRA, indicating significant industrial potential.

[Arxiv](https://arxiv.org/abs/2409.17834)