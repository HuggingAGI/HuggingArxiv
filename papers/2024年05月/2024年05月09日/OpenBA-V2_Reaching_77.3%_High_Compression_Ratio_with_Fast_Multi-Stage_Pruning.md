# OpenBA-V2：以迅捷的多阶段剪枝技术，实现了高达77.3%的卓越压缩比，为模型瘦身开辟了新境界。

发布时间：2024年05月09日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的压缩技术，通过多阶段压缩和持续预训练的方法，从一个大型的OpenBA模型精炼出一个更小规模的模型，同时保持了性能。这种方法和技术属于对LLMs理论层面的研究和改进，因此归类于LLM理论。论文中提到的模型压缩、训练策略和数据利用等技术，是对LLMs理论的深入探讨，旨在解决LLMs在实际应用中的部署成本和推理开销问题。` `模型压缩`

> OpenBA-V2: Reaching 77.3% High Compression Ratio with Fast Multi-Stage Pruning

# 摘要

> 大型语言模型（LLMs）因其卓越能力在多个领域占据重要地位，但其庞大的参数规模带来了高昂的部署成本和推理开销，限制了实际应用。为此，我们推出了OpenBA-V2，一个通过多阶段压缩和持续预训练从15B OpenBA模型精炼而来的3.4B模型。OpenBA-V2通过采用更多数据、灵活的训练目标以及层剪枝、神经剪枝和词汇剪枝等技术，实现了77.3%的压缩率，同时几乎不牺牲性能。在与同规模开源模型的较量中，OpenBA-V2在常识推理和命名实体识别等任务上表现卓越，与15B OpenBA模型不相上下。这一成就表明，通过精妙的训练策略和数据利用，LLMs可以被高效压缩，为资源受限环境下的部署提供了可能。

> Large Language Models (LLMs) have played an important role in many fields due to their powerful capabilities.However, their massive number of parameters leads to high deployment requirements and incurs significant inference costs, which impedes their practical applications. Training smaller models is an effective way to address this problem. Therefore, we introduce OpenBA-V2, a 3.4B model derived from multi-stage compression and continual pre-training from the original 15B OpenBA model. OpenBA-V2 utilizes more data, more flexible training objectives, and techniques such as layer pruning, neural pruning, and vocabulary pruning to achieve a compression rate of 77.3\% with minimal performance loss. OpenBA-V2 demonstrates competitive performance compared to other open-source models of similar size, achieving results close to or on par with the 15B OpenBA model in downstream tasks such as common sense reasoning and Named Entity Recognition (NER). OpenBA-V2 illustrates that LLMs can be compressed into smaller ones with minimal performance loss by employing advanced training objectives and data strategies, which may help deploy LLMs in resource-limited scenarios.

[Arxiv](https://arxiv.org/abs/2405.05957)