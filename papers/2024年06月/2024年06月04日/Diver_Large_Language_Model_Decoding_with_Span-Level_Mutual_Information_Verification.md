# Diver：利用跨度级互信息验证优化大型语言模型解码

发布时间：2024年06月04日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在解码过程中的优化方法，特别是通过点互信息（PMI）分数来量化和优化输出。这种研究侧重于LLM的理论和算法改进，而不是具体的应用场景或Agent的行为，也不是关于检索增强生成（RAG）的具体应用。因此，它更符合LLM理论的分类。` `机器学习`

> Diver: Large Language Model Decoding with Span-Level Mutual Information Verification

# 摘要

> 大型语言模型（LLMs）在接收到特定任务指令时，其适应能力令人印象深刻。然而，当面对输入的偏差时，采用标准解码策略的LLMs往往力不从心。理想的LLM输出应忠实反映输入信息，这一点可通过点互信息（PMI）分数来量化。为此，我们创新性地提出了Diver方法，它通过跨度级PMI验证来优化LLM的解码过程。在推理阶段，Diver首先定位可能产生多个候选跨度的偏差点，接着计算这些候选跨度对输入的对数似然增益，从而得出PMI分数。最终，依据PMI重新排序的输出分布，选出最优跨度。我们在多个下游任务上验证了Diver的效果，结果显示，Diver在性能和通用性上均大幅超越了现有解码技术。

> Large language models (LLMs) have shown impressive capabilities in adapting to various tasks when provided with task-specific instructions. However, LLMs using standard decoding strategies often struggle with deviations from the inputs. Intuitively, compliant LLM outputs should reflect the information present in the input, which can be measured by point-wise mutual information (PMI) scores. Therefore, we propose Diver, a novel approach that enhances LLM Decoding through span-level PMI verification. During inference, Diver first identifies divergence steps that may lead to multiple candidate spans. Subsequently, it calculates the PMI scores by assessing the log-likelihood gains of the input if the candidate spans are generated. Finally, the optimal span is selected based on the PMI re-ranked output distributions. We evaluate our method across various downstream tasks, and empirical results demonstrate that Diver significantly outperforms existing decoding methods in both performance and versatility.

![Diver：利用跨度级互信息验证优化大型语言模型解码](../../../paper_images/2406.02120/x1.png)

![Diver：利用跨度级互信息验证优化大型语言模型解码](../../../paper_images/2406.02120/x2.png)

![Diver：利用跨度级互信息验证优化大型语言模型解码](../../../paper_images/2406.02120/x3.png)

![Diver：利用跨度级互信息验证优化大型语言模型解码](../../../paper_images/2406.02120/x4.png)

![Diver：利用跨度级互信息验证优化大型语言模型解码](../../../paper_images/2406.02120/x5.png)

![Diver：利用跨度级互信息验证优化大型语言模型解码](../../../paper_images/2406.02120/x6.png)

[Arxiv](https://arxiv.org/abs/2406.02120)