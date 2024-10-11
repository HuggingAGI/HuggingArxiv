# 利用期望最大化技术，揭示大型语言模型的训练数据之谜。

发布时间：2024年10月09日

`LLM理论` `数据隐私` `机器学习`

> Detecting Training Data of Large Language Models via Expectation Maximization

# 摘要

> 大型语言模型（LLM）的广泛应用虽带来了显著进步，但其训练数据的细节仍未公开，这对其性能至关重要。成员推断攻击（MIAs）旨在判断特定数据是否被用于训练特定模型。MIAs 不仅能洞察 LLM 的输出，还能帮助检测数据污染及隐私版权问题。然而，将 MIAs 应用于 LLM 面临独特挑战，如海量预训练数据和成员身份的不确定性。此外，构建评估 MIA 方法的基准也颇具挑战，因训练与测试数据分布常未知。本文提出 EM-MIA，一种利用期望最大化算法迭代优化成员与前缀分数的新型 MIA 方法，已在 WikiMIA 数据集上取得领先成果。为进一步评估，我们创建了 OLMoMIA 基准，通过控制训练与测试数据的重叠度来调整任务难度。EM-MIA 和 OLMoMIA 不仅为 LLM 提供了强大的 MIA 工具，也为未来研究提供了宝贵资源。

> The widespread deployment of large language models (LLMs) has led to impressive advancements, yet information about their training data, a critical factor in their performance, remains undisclosed. Membership inference attacks (MIAs) aim to determine whether a specific instance was part of a target model's training data. MIAs can offer insights into LLM outputs and help detect and address concerns such as data contamination and compliance with privacy and copyright standards. However, applying MIAs to LLMs presents unique challenges due to the massive scale of pre-training data and the ambiguous nature of membership. Additionally, creating appropriate benchmarks to evaluate MIA methods is not straightforward, as training and test data distributions are often unknown. In this paper, we introduce EM-MIA, a novel MIA method for LLMs that iteratively refines membership scores and prefix scores via an expectation-maximization algorithm, leveraging the duality that the estimates of these scores can be improved by each other. Membership scores and prefix scores assess how each instance is likely to be a member and discriminative as a prefix, respectively. Our method achieves state-of-the-art results on the WikiMIA dataset. To further evaluate EM-MIA, we present OLMoMIA, a benchmark built from OLMo resources, which allows us to control the difficulty of MIA tasks with varying degrees of overlap between training and test data distributions. We believe that EM-MIA serves as a robust MIA method for LLMs and that OLMoMIA provides a valuable resource for comprehensively evaluating MIA approaches, thereby driving future research in this critical area.

[Arxiv](https://arxiv.org/abs/2410.07582)