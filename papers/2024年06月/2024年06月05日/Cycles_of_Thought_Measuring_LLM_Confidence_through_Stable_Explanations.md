# 思维的循环：借助稳定解释洞察 LLM 的信心之源

发布时间：2024年06月05日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的不确定性量化问题，提出了一种新的框架来评估LLM的不确定性。这种方法通过分析答案解释的分布来实现，将模型与解释视为分类器，并计算后验答案分布。这种研究属于对LLM理论层面的深入探讨，因为它关注的是LLM的内部机制和性能评估，而不是直接的应用或Agent的行为。因此，它更适合归类为LLM理论。` `机器学习`

> Cycles of Thought: Measuring LLM Confidence through Stable Explanations

# 摘要

> 在众多高风险机器学习应用中，模型识别自身预测不确定性的能力至关重要。尽管大型语言模型（LLMs）在多项测试中已能媲美甚至超越人类表现，但它们对错误答案的过度自信仍是一个公认的缺陷。由于计算成本高昂且多数模型闭源，传统的不确定性量化方法难以直接应用于LLMs。近期虽有多种黑盒方法提出，但多依赖于自我表达的信心等启发式手段。我们提出了一种新框架，通过分析答案解释的分布来评估LLM的不确定性。虽然利用解释并非首创，但我们将每对模型与解释视为测试时的分类器，从而计算出最可能分类器的后验答案分布。我们通过特定实例展示了这一框架，特别是使用解释蕴含作为分类器似然性，显著提升了信心分数指标（如AURC和AUROC）在五个数据集上的表现。我们认为，这证明了我们的框架是量化LLMs不确定性的既合理又有效的方法。

> In many high-risk machine learning applications it is essential for a model to indicate when it is uncertain about a prediction. While large language models (LLMs) can reach and even surpass human-level accuracy on a variety of benchmarks, their overconfidence in incorrect responses is still a well-documented failure mode. Traditional methods for ML uncertainty quantification can be difficult to directly adapt to LLMs due to the computational cost of implementation and closed-source nature of many models. A variety of black-box methods have recently been proposed, but these often rely on heuristics such as self-verbalized confidence. We instead propose a framework for measuring an LLM's uncertainty with respect to the distribution of generated explanations for an answer. While utilizing explanations is not a new idea in and of itself, by interpreting each possible model+explanation pair as a test-time classifier we can calculate a posterior answer distribution over the most likely of these classifiers. We demonstrate how a specific instance of this framework using explanation entailment as our classifier likelihood improves confidence score metrics (in particular AURC and AUROC) over baselines across five different datasets. We believe these results indicate that our framework is both a well-principled and effective way of quantifying uncertainty in LLMs.

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/x1.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/x2.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/stability_prompt_v2.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/token_prob_prompt.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/lingusitic_prompt.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/cot_prompt.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/topk_prompt.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/conditional_prompt.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/example_curves.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/mmlu_law_explanation_p_likely.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/aurc_vs_explanations.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/auroc_vs_explanations.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/ece_vs_explanations.png)

![思维的循环：借助稳定解释洞察 LLM 的信心之源](../../../paper_images/2406.03441/tta_prompt.png)

[Arxiv](https://arxiv.org/abs/2406.03441)