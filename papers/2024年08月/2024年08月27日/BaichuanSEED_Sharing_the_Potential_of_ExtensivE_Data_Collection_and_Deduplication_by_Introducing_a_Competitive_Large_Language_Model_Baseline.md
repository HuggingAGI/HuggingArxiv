# BaichuanSEED 项目旨在展示通过引入竞争性大型语言模型基线，实现大规模数据收集与去重的技术潜力。

发布时间：2024年08月27日

`LLM理论` `人工智能` `数据处理`

> BaichuanSEED: Sharing the Potential of ExtensivE Data Collection and Deduplication by Introducing a Competitive Large Language Model Baseline

# 摘要

> 大型语言模型（LLM）的强大能力很大程度上取决于其预训练数据集的精选，这些数据集常被视为商业机密。为解决这一难题，我们公开了通用的数据处理流程细节，并通过设立竞争性LLM基线来验证其效能。该流程从广泛收集数据开始，通过扩容和重新加权提升数据质量。我们利用此流程处理了3万亿个令牌，预训练出70亿参数的模型BaichuanSEED，并进行了简便而高效的监督微调。BaichuanSEED在训练全程保持稳定表现，与顶尖商业模型如Qwen1.5和Llama3在多项基准测试中不相上下。此外，我们还探索了针对数学和编程等下游任务的优化可能。

> The general capabilities of Large Language Models (LLM) highly rely on the composition and selection on extensive pretraining datasets, treated as commercial secrets by several institutions. To mitigate this issue, we open-source the details of a universally applicable data processing pipeline and validate its effectiveness and potential by introducing a competitive LLM baseline. Specifically, the data processing pipeline consists of broad collection to scale up and reweighting to improve quality. We then pretrain a 7B model BaichuanSEED with 3T tokens processed by our pipeline without any deliberate downstream task-related optimization, followed by an easy but effective supervised fine-tuning stage. BaichuanSEED demonstrates consistency and predictability throughout training and achieves comparable performance on comprehensive benchmarks with several commercial advanced large language models, such as Qwen1.5 and Llama3. We also conduct several heuristic experiments to discuss the potential for further optimization of downstream tasks, such as mathematics and coding.

[Arxiv](https://arxiv.org/abs/2408.15079)