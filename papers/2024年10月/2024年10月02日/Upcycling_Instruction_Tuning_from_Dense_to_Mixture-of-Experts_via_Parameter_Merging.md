# 通过参数合并技术，将指令调优从密集模型升级为专家混合模型，实现模型性能的提升。

发布时间：2024年10月02日

`LLM理论` `人工智能`

> Upcycling Instruction Tuning from Dense to Mixture-of-Experts via Parameter Merging

# 摘要

> MoE 在 LLM 中大放异彩，在众多 NLP 任务中表现卓越。然而，将 LLM 从密集模型转换为 MoE 的方法通常需要大量数据和后训练。本文提出 UpIT，一种高效的数据方法，将密集预训练模型调整为 MoE 指令模型。我们发现密集模型指令调优中的中间检查点自然适合专家，并引入遗传算法和参数合并，确保新专家的多样性。为确保每个专家按预期工作，我们用少量种子数据预优化路由器。实验证明 UpIT 在各种设置下表现优异且数据高效，专家和数据扩展稳定提升。进一步分析强调了确保专家多样性的重要性。

> Mixture-of-Experts (MoE) shines brightly in large language models (LLMs) and demonstrates outstanding performance in plentiful natural language processing tasks. However, existing methods transforming LLMs from dense to MoE face significant data requirements and typically rely on large-scale post-training. In this paper, we propose Upcycling Instruction Tuning (UpIT), a data-efficient approach for tuning a dense pre-trained model into a MoE instruction model. Specifically, we first point out that intermediate checkpoints during instruction tuning of the dense model are naturally suitable for specialized experts, and then propose an expert expansion stage to flexibly achieve models with flexible numbers of experts, where genetic algorithm and parameter merging are introduced to ensure sufficient diversity of new extended experts. To ensure that each specialized expert in the MoE model works as expected, we select a small amount of seed data that each expert excels to pre-optimize the router. Extensive experiments with various data scales and upcycling settings demonstrate the outstanding performance and data efficiency of UpIT, as well as stable improvement in expert or data scaling. Further analysis reveals the importance of ensuring expert diversity in upcycling.

[Arxiv](https://arxiv.org/abs/2410.01610)