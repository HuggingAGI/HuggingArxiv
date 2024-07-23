# 在 CLIP 时代，我们需重新审视领域适应与泛化的策略。

发布时间：2024年07月21日

`LLM应用` `计算机视觉`

> Rethinking Domain Adaptation and Generalization in the Era of CLIP

# 摘要

> 近期研究强调了领域适应中从源领域到目标领域学习共享知识的重要性。大型视觉-语言预训练模型 CLIP 在零-shot 识别上表现出色，通过参数高效调整可进一步提升其特定任务性能。研究发现，简单的领域先验能增强 CLIP 在特定领域的零-shot 识别能力，且其适应性较少依赖源领域数据。我们还为 CLIP 的零-shot 适应和伪标签自训练设立了基准，并提出从多未标记领域提升其任务泛化能力，这一实际且独特的场景。我们相信，这些发现将促使人们重新审视领域适应基准及相关算法在 CLIP 时代的作用。

> In recent studies on domain adaptation, significant emphasis has been placed on the advancement of learning shared knowledge from a source domain to a target domain. Recently, the large vision-language pre-trained model, i.e., CLIP has shown strong ability on zero-shot recognition, and parameter efficient tuning can further improve its performance on specific tasks. This work demonstrates that a simple domain prior boosts CLIP's zero-shot recognition in a specific domain. Besides, CLIP's adaptation relies less on source domain data due to its diverse pre-training dataset. Furthermore, we create a benchmark for zero-shot adaptation and pseudo-labeling based self-training with CLIP. Last but not least, we propose to improve the task generalization ability of CLIP from multiple unlabeled domains, which is a more practical and unique scenario. We believe our findings motivate a rethinking of domain adaptation benchmarks and the associated role of related algorithms in the era of CLIP.

![在 CLIP 时代，我们需重新审视领域适应与泛化的策略。](../../../paper_images/2407.15173/x1.png)

![在 CLIP 时代，我们需重新审视领域适应与泛化的策略。](../../../paper_images/2407.15173/x2.png)

[Arxiv](https://arxiv.org/abs/2407.15173)