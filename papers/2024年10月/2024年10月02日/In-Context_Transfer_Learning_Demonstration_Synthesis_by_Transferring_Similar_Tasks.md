# 上下文迁移学习：借助相似任务实现演示合成

发布时间：2024年10月02日

`LLM应用` `人工智能`

> In-Context Transfer Learning: Demonstration Synthesis by Transferring Similar Tasks

# 摘要

> ICL 通过提供任务演示，帮助 LLM 适应各种任务。然而，标注演示成本高，许多方法尝试用 LLM 从头合成演示，但质量受限。为此，我们借鉴迁移学习，提出 ICTL，通过转移相似源任务的标注演示来合成目标任务演示。ICTL 分两步：源采样和目标转移。首先，我们设定优化目标，最小化转移误差以采样与目标任务相似的源演示。接着，利用 LLM 将采样的源演示转移到目标任务，确保格式和定义一致。实验显示，ICTL 在 Super-NI 上平均比从头合成高出 2.0%，验证了其有效性。

> In-context learning (ICL) is an effective approach to help large language models (LLMs) adapt to various tasks by providing demonstrations of the target task. Considering the high cost of labeling demonstrations, many methods propose synthesizing demonstrations from scratch using LLMs. However, the quality of the demonstrations synthesized from scratch is limited by the capabilities and knowledge of LLMs. To address this, inspired by transfer learning, we propose In-Context Transfer Learning (ICTL), which synthesizes target task demonstrations by transferring labeled demonstrations from similar source tasks. ICTL consists of two steps: source sampling and target transfer. First, we define an optimization objective, which minimizes transfer error to sample source demonstrations similar to the target task. Then, we employ LLMs to transfer the sampled source demonstrations to the target task, matching the definition and format of the target task. Experiments on Super-NI show that ICTL outperforms synthesis from scratch by 2.0% on average, demonstrating the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2410.01548)