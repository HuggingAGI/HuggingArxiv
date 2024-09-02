# NDP：将下一个分布预测作为更广泛的目标

发布时间：2024年08月30日

`LLM理论`

> NDP: Next Distribution Prediction as a More Broad Target

# 摘要

> 大型语言模型 (LLM) 在基于下一个标记预测 (NTP) 范式训练中展现了强大的能力。然而，现有的 NTP 范式存在若干限制，特别是与计划任务复杂性和推理过程中的错误传播相关。在我们的工作中，我们扩展了对 NTP 的批评，强调其局限性也源于训练目标狭窄：预测次优的单热分布。为了支持这一批评，我们进行了一项预实验，将强大 LLM 的输出分布视为高效的世界数据压缩。通过评估 $n$-gram 分布与 LLM 的单热分布之间的相似性，我们观察到 $n$-gram 分布与 LLM 的输出分布更为接近。基于这一洞察，我们引入了下一个分布预测 (NDP)，它使用 $n$-gram 分布替代单热目标，无需额外在线训练时间即可增强学习。我们在翻译、通用任务、语言迁移和医学领域适应等多个领域进行了实验。与 NTP 相比，NDP 在翻译任务中可实现高达 +2.97 COMET 的改进，在通用任务中平均改进 +0.61，在医学领域平均改进 +10.75。这展示了解决目标狭窄问题的具体好处，为未来改进 NTP 的工作指明了新方向。

> Large language models (LLMs) trained on next-token prediction (NTP) paradigm have demonstrated powerful capabilities. However, the existing NTP paradigm contains several limitations, particularly related to planned task complications and error propagation during inference. In our work, we extend the critique of NTP, highlighting its limitation also due to training with a narrow objective: the prediction of a sub-optimal one-hot distribution. To support this critique, we conducted a pre-experiment treating the output distribution from powerful LLMs as efficient world data compression. By evaluating the similarity between the $n$-gram distribution and the one-hot distribution with LLMs, we observed that the $n$-gram distributions align more closely with the output distribution of LLMs. Based on this insight, we introduce Next Distribution Prediction (NDP), which uses $n$-gram distributions to replace the one-hot targets, enhancing learning without extra online training time. We conducted experiments across translation, general task, language transfer, and medical domain adaptation. Compared to NTP, NDP can achieve up to +2.97 COMET improvement in translation tasks, +0.61 average improvement in general tasks, and incredible +10.75 average improvement in the medical domain. This demonstrates the concrete benefits of addressing the target narrowing problem, pointing to a new direction for future work on improving NTP.

[Arxiv](https://arxiv.org/abs/2408.17377)