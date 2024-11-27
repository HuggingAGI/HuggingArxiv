# 是真正的推理还是看似推理？对 LLM 中传递推理的诊断性研究

发布时间：2024年10月26日

`LLM应用` `语言模型`

> Reasoning or a Semblance of it? A Diagnostic Study of Transitive Reasoning in LLMs

# 摘要

> 在推理基准上对大型语言模型（LLMs）进行评估，展现出它们解决组合问题的能力。然而，这些模型到底是在进行真正的逻辑推理，还是仅仅依靠隐含线索来生成答案，我们了解甚少。在本文中，我们通过在 QASC 和 Bamboogle 这两个组合数据集中操纵事实，探究了 LLaMA 2 和 Flan-T5 这两种不同的 LLM 架构的传递推理能力。我们控制了可能影响模型性能的潜在线索，比如（a）测试输入各部分之间的单词/短语重叠；（b）模型在预训练或微调期间的固有知识；（c）命名实体。我们的发现显示，虽然两个模型都利用了（a），但 Flan-T5 对（b 和 c）实验的适应性更强，其方差小于 LLaMA 2。这意味着模型或许能通过在已知相关的数据集上进行微调来形成对传递性的理解，这一假设有待未来的工作去验证。

> Evaluating Large Language Models (LLMs) on reasoning benchmarks demonstrates their ability to solve compositional questions. However, little is known of whether these models engage in genuine logical reasoning or simply rely on implicit cues to generate answers. In this paper, we investigate the transitive reasoning capabilities of two distinct LLM architectures, LLaMA 2 and Flan-T5, by manipulating facts within two compositional datasets: QASC and Bamboogle. We controlled for potential cues that might influence the models' performance, including (a) word/phrase overlaps across sections of test input; (b) models' inherent knowledge during pre-training or fine-tuning; and (c) Named Entities. Our findings reveal that while both models leverage (a), Flan-T5 shows more resilience to experiments (b and c), having less variance than LLaMA 2. This suggests that models may develop an understanding of transitivity through fine-tuning on knowingly relevant datasets, a hypothesis we leave to future work.

[Arxiv](https://arxiv.org/abs/2410.20200)