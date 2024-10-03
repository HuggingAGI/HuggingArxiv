# 自动演示提示：借助生成的输出作为演示，提升批量提示的效果

发布时间：2024年10月02日

`LLM应用` `机器学习`

> Auto-Demo Prompting: Leveraging Generated Outputs as Demonstrations for Enhanced Batch Prompting

# 摘要

> 批量提示在 LLM 中常用于同时处理多个输入，以提升计算效率。然而，批量增大时，模型处理长上下文输入的困难常导致性能下降。现有方法多依赖批量数据排列和多数投票，而非改进批量提示本身。本文提出“自动演示提示”，利用批次中早期问答对作为后续推理的演示，正式分析了其在自回归生成过程中的作用，展示了如何优化模型内部表示。该方法有效结合了批量提示和少样本提示的优势，实验证明其在多个 NLP 任务中能有效缓解性能下降，甚至超越单个提示。此外，它为批量提示中应用少样本学习技术（如演示选择）提供了新思路，成为现实应用的强大工具。

> Batch prompting is a common technique in large language models (LLMs) used to process multiple inputs simultaneously, aiming to improve computational efficiency. However, as batch sizes increase, performance degradation often occurs due to the model's difficulty in handling lengthy context inputs. Existing methods that attempt to mitigate these issues rely solely on batch data arrangement and majority voting rather than improving the design of the batch prompt itself. In this paper, we address these limitations by proposing "Auto-Demo Prompting," a novel approach that leverages the question-output pairs from earlier questions within a batch as demonstrations for subsequent answer inference. We provide a formal theoretical analysis of how Auto-Demo Prompting functions within the autoregressive generation process of LLMs, illustrating how it utilizes prior outputs to optimize the model's internal representations. Our method effectively bridges the gap between batch prompting and few-shot prompting, enhancing performance with only a slight compromise in token usage. Experimental results across five NLP tasks demonstrate its effectiveness in mitigating performance degradation and occasionally outperforming single prompts. Furthermore, it opens new avenues for applying few-shot learning techniques, such as demonstration selection, within batch prompting, making it a robust solution for real-world applications.

[Arxiv](https://arxiv.org/abs/2410.01724)