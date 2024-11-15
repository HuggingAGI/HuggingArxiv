# 把所有部分整合起来：验证多跳多模态的声明

发布时间：2024年11月14日

`LLM应用` `多模态` `主张验证`

> Piecing It All Together: Verifying Multi-Hop Multimodal Claims

# 摘要

> 现有的主张验证数据集往往不要求系统进行复杂推理或有效解读多模态证据。为此，我们推出新任务：多跳多模态主张验证。该任务要求模型对来自不同来源（如文本、图像和表格）的多份证据进行推理，判断组合的多模态证据是支持还是反驳给定主张。为研究此任务，我们构建了 MMCV 这一大型数据集，其中包含 16k 个多跳主张及与之匹配的多模态证据，由大型语言模型生成并完善，还融入了人类反馈的额外输入。我们发现，即便对于最新的顶尖多模态大型语言模型，MMCV 也颇具难度，尤其在推理跳数增多时。另外，我们在 MMCV 的一个子集上确立了人类性能基准。期望此数据集及其评估任务能推动未来多模态多跳主张验证方面的研究。

> Existing claim verification datasets often do not require systems to perform complex reasoning or effectively interpret multimodal evidence. To address this, we introduce a new task: multi-hop multimodal claim verification. This task challenges models to reason over multiple pieces of evidence from diverse sources, including text, images, and tables, and determine whether the combined multimodal evidence supports or refutes a given claim. To study this task, we construct MMCV, a large-scale dataset comprising 16k multi-hop claims paired with multimodal evidence, generated and refined using large language models, with additional input from human feedback. We show that MMCV is challenging even for the latest state-of-the-art multimodal large language models, especially as the number of reasoning hops increases. Additionally, we establish a human performance benchmark on a subset of MMCV. We hope this dataset and its evaluation task will encourage future research in multimodal multi-hop claim verification.

[Arxiv](https://arxiv.org/abs/2411.09547)