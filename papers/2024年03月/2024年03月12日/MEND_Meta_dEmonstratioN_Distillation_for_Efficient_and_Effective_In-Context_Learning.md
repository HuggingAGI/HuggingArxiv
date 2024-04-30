# MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。

发布时间：2024年03月12日

`LLM应用` `人工智能`

> MEND: Meta dEmonstratioN Distillation for Efficient and Effective In-Context Learning

# 摘要

> 大型语言模型（LLMs）在上下文学习（ICL）方面展现出了卓越的能力，能够结合少量输入输出对（示例）对特定测试输入进行预测。但引入示例会使自注意力机制的计算成本呈指数级增长。现有方法试图将复杂的示例简化为简洁的向量，却往往需要特定任务的重新训练或以牺牲模型的ICL性能为代价。为了应对这些挑战，我们引入了Meta dEmonstratioN Distillation（MEND）技术，这是一种无需针对新任务重新训练即可将长示例转化为向量的语言模型。MEND利用知识蒸馏技术，增强了与LLM的一致性，实现了效率与效果的双赢。通过包含元蒸馏预训练和微调的两阶段训练流程，MEND获得了蒸馏示例的元知识。在七个多样化的ICL任务领域的全面评估中，无论是使用仅解码器模型（GPT-2）还是编码器-解码器模型（T5），MEND都展现了其强大的性能。它不仅能够匹敌传统的ICL，常常还能超越其他尖端的蒸馏模型，并且在大幅度降低计算需求的同时，为大型语言模型的实际应用提供了更好的可扩展性和效率。

> Large Language models (LLMs) have demonstrated impressive in-context learning (ICL) capabilities, where a LLM makes predictions for a given test input together with a few input-output pairs (demonstrations). Nevertheless, the inclusion of demonstrations leads to a quadratic increase in the computational overhead of the self-attention mechanism. Existing solutions attempt to distill lengthy demonstrations into compact vectors. However, they often require task-specific retraining or compromise LLM's in-context learning performance. To mitigate these challenges, we present Meta dEmonstratioN Distillation (MEND), where a language model learns to distill any lengthy demonstrations into vectors without retraining for a new downstream task. We exploit the knowledge distillation to enhance alignment between MEND and LLM, achieving both efficiency and effectiveness simultaneously. MEND is endowed with the meta-knowledge of distilling demonstrations through a two-stage training process, which includes meta-distillation pretraining and fine-tuning. Comprehensive evaluations across seven diverse ICL task partitions using decoder-only (GPT-2) and encoder-decoder (T5) attest to MEND's prowess. It not only matches but often outperforms the Vanilla ICL as well as other state-of-the-art distillation models, while significantly reducing the computational demands. This innovation promises enhanced scalability and efficiency for the practical deployment of large language models

![MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。](../../../paper_images/2403.06914/x1.png)

![MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。](../../../paper_images/2403.06914/x2.png)

![MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。](../../../paper_images/2403.06914/x3.png)

![MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。](../../../paper_images/2403.06914/x4.png)

![MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。](../../../paper_images/2403.06914/x5.png)

![MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。](../../../paper_images/2403.06914/x6.png)

![MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。](../../../paper_images/2403.06914/x7.png)

![MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。](../../../paper_images/2403.06914/x8.png)

![MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。](../../../paper_images/2403.06914/x9.png)

![MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。](../../../paper_images/2403.06914/x10.png)

![MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。](../../../paper_images/2403.06914/x11.png)

![MEND：通过元示范展示的蒸馏技术，实现高效且有效的情境内学习。](../../../paper_images/2403.06914/x12.png)

[Arxiv](https://arxiv.org/abs/2403.06914)