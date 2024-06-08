# MultifacetEval：探究大型语言模型医学知识掌握度的多维度评估

发布时间：2024年06月05日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在医疗领域的应用，特别是在医学知识掌握程度方面的评估。通过创建和使用MultifacetEval评估框架以及相关的数据集（MultiDiseK和MultiMedQA），研究者们评估了LLMs在医学知识的多维度上的表现，并指出了这些模型在实际医疗任务中的不足。因此，这篇论文更偏向于LLM的应用层面，即如何评估和改进LLMs在特定领域（医疗）的应用性能。` `评估与测试`

> MultifacetEval: Multifaceted Evaluation to Probe LLMs in Mastering Medical Knowledge

# 摘要

> 大型语言模型（LLMs）在医疗领域如MedQA基准上虽有亮眼表现，但与现实医疗场景中的实际效能相比，仍有显著差距。本文通过多维度的审查模式，深入探究了LLMs对医学知识的掌握程度，揭示了这一差距的根源。我们创新性地推出了MultifacetEval评估框架，旨在全面评估LLMs在医学知识的多维度（比较、纠正、区分和验证）上的掌握情况。基于此框架，我们创建了MultiDiseK和MultiMedQA两个多维度评估数据集，实验结果揭示了LLMs在医学知识掌握上的不足，缺乏深度、精确性和全面性。因此，这些模型尚未能胜任实际医疗任务。相关代码和数据集已公开于https://github.com/THUMLP/MultifacetEval。

> Large language models (LLMs) have excelled across domains, also delivering notable performance on the medical evaluation benchmarks, such as MedQA. However, there still exists a significant gap between the reported performance and the practical effectiveness in real-world medical scenarios. In this paper, we aim to explore the causes of this gap by employing a multifaceted examination schema to systematically probe the actual mastery of medical knowledge by current LLMs. Specifically, we develop a novel evaluation framework MultifacetEval to examine the degree and coverage of LLMs in encoding and mastering medical knowledge at multiple facets (comparison, rectification, discrimination, and verification) concurrently. Based on the MultifacetEval framework, we construct two multifaceted evaluation datasets: MultiDiseK (by producing questions from a clinical disease knowledge base) and MultiMedQA (by rephrasing each question from a medical benchmark MedQA into multifaceted questions). The experimental results on these multifaceted datasets demonstrate that the extent of current LLMs in mastering medical knowledge is far below their performance on existing medical benchmarks, suggesting that they lack depth, precision, and comprehensiveness in mastering medical knowledge. Consequently, current LLMs are not yet ready for application in real-world medical tasks. The codes and datasets are available at https://github.com/THUMLP/MultifacetEval.

![MultifacetEval：探究大型语言模型医学知识掌握度的多维度评估](../../../paper_images/2406.02919/example_2.png)

![MultifacetEval：探究大型语言模型医学知识掌握度的多维度评估](../../../paper_images/2406.02919/multifaceted.png)

![MultifacetEval：探究大型语言模型医学知识掌握度的多维度评估](../../../paper_images/2406.02919/method.png)

![MultifacetEval：探究大型语言模型医学知识掌握度的多维度评估](../../../paper_images/2406.02919/VCQ.png)

![MultifacetEval：探究大型语言模型医学知识掌握度的多维度评估](../../../paper_images/2406.02919/disek_1.png)

![MultifacetEval：探究大型语言模型医学知识掌握度的多维度评估](../../../paper_images/2406.02919/fig.png)

![MultifacetEval：探究大型语言模型医学知识掌握度的多维度评估](../../../paper_images/2406.02919/medqa_cotsc_6.png)

![MultifacetEval：探究大型语言模型医学知识掌握度的多维度评估](../../../paper_images/2406.02919/muldkb_five_6.png)

[Arxiv](https://arxiv.org/abs/2406.02919)