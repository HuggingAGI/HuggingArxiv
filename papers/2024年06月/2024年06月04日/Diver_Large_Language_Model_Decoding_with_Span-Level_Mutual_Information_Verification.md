# Diver：大型语言模型解码中的跨度级互信息验证技术

发布时间：2024年06月04日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在解码策略上的创新，特别是在处理输入偏差时的表现。论文提出的Diver方法通过点互信息（PMI）分数来优化LLM的解码过程，这是一种理论上的改进，旨在提高模型输出的忠实度和准确性。因此，这项工作更偏向于LLM的理论研究，而不是具体的应用、Agent行为或RAG（Retrieval-Augmented Generation）相关的研究。` `机器学习`

> Diver: Large Language Model Decoding with Span-Level Mutual Information Verification

# 摘要

> 大型语言模型（LLMs）在接收特定任务指令时表现出色，但面对输入偏差时，传统解码策略往往力不从心。理想情况下，LLM的输出应忠实反映输入信息，这一点可通过点互信息（PMI）分数来评估。为此，我们创新性地提出了Diver方法，它通过跨度级PMI验证优化LLM解码。在推理阶段，Diver首先识别可能产生多个候选跨度的偏离点，然后计算这些候选跨度对输入对数似然增益的影响，以确定PMI分数。最终，依据PMI重新排序的输出分布，选出最优跨度。我们在多个下游任务上验证了Diver，结果显示它在性能和通用性上均大幅超越现有解码技术。

> Large language models (LLMs) have shown impressive capabilities in adapting to various tasks when provided with task-specific instructions. However, LLMs using standard decoding strategies often struggle with deviations from the inputs. Intuitively, compliant LLM outputs should reflect the information present in the input, which can be measured by point-wise mutual information (PMI) scores. Therefore, we propose Diver, a novel approach that enhances LLM Decoding through span-level PMI verification. During inference, Diver first identifies divergence steps that may lead to multiple candidate spans. Subsequently, it calculates the PMI scores by assessing the log-likelihood gains of the input if the candidate spans are generated. Finally, the optimal span is selected based on the PMI re-ranked output distributions. We evaluate our method across various downstream tasks, and empirical results demonstrate that Diver significantly outperforms existing decoding methods in both performance and versatility.

![Diver：大型语言模型解码中的跨度级互信息验证技术](../../../paper_images/2406.02120/x1.png)

![Diver：大型语言模型解码中的跨度级互信息验证技术](../../../paper_images/2406.02120/x2.png)

![Diver：大型语言模型解码中的跨度级互信息验证技术](../../../paper_images/2406.02120/x3.png)

![Diver：大型语言模型解码中的跨度级互信息验证技术](../../../paper_images/2406.02120/x4.png)

![Diver：大型语言模型解码中的跨度级互信息验证技术](../../../paper_images/2406.02120/x5.png)

![Diver：大型语言模型解码中的跨度级互信息验证技术](../../../paper_images/2406.02120/x6.png)

[Arxiv](https://arxiv.org/abs/2406.02120)