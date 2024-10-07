# 从概率角度探讨大型语言模型的遗忘与对齐问题

发布时间：2024年10月04日

`LLM理论` `人工智能` `机器学习`

> A Probabilistic Perspective on Unlearning and Alignment for Large Language Models

# 摘要

> 大型语言模型（LLM）的综合评估仍是一个开放的研究课题。现有评估方法依赖于贪婪解码生成的确定性点估计，但这种评估方式无法全面捕捉模型的输出分布，导致对模型能力的评估失准。特别是在遗忘和校准等关键场景中，精确的模型评估尤为重要。为此，我们首次提出了 LLM 的概率评估框架，推导出具有高概率保证的新指标，这些指标独立于具体应用，使从业者能在部署前更可靠地评估模型能力。通过遗忘案例研究，我们发现确定性评估误判了遗忘效果，而概率评估则揭示了这些模型中大部分甚至所有所谓的遗忘信息仍可访问。此外，我们提出了一种基于熵优化和自适应温度缩放的新型遗忘损失，显著提升了近期基准测试中的遗忘效果。从点估计转向输出分布的概率评估，是我们迈向 LLM 综合评估的重要一步。https://github.com/yascho/probabilistic-unlearning

> Comprehensive evaluation of Large Language Models (LLMs) is an open research problem. Existing evaluations rely on deterministic point estimates generated via greedy decoding. However, we find that deterministic evaluations fail to capture the whole output distribution of a model, yielding inaccurate estimations of model capabilities. This is particularly problematic in critical contexts such as unlearning and alignment, where precise model evaluations are crucial. To remedy this, we introduce the first formal probabilistic evaluation framework in LLMs. Namely, we derive novel metrics with high-probability guarantees concerning the output distribution of a model. Our metrics are application-independent and allow practitioners to make more reliable estimates about model capabilities before deployment. Through a case study focused on unlearning, we reveal that deterministic evaluations falsely indicate successful unlearning, whereas our probabilistic evaluations demonstrate that most if not all of the supposedly unlearned information remains accessible in these models. Additionally, we propose a novel unlearning loss based on entropy optimization and adaptive temperature scaling, which significantly improves unlearning in probabilistic settings on recent benchmarks. Our proposed shift from point estimates to probabilistic evaluations of output distributions represents an important step toward comprehensive evaluations of LLMs. https://github.com/yascho/probabilistic-unlearning

[Arxiv](https://arxiv.org/abs/2410.03523)