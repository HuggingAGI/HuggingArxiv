# 从河流谷地损失景观的视角，理解 Warmup-Stable-Decay 学习率。

发布时间：2024年10月07日

`LLM理论` `人工智能` `机器学习`

> Understanding Warmup-Stable-Decay Learning Rates: A River Valley Loss Landscape Perspective

# 摘要

> 当前训练语言模型需要预设固定计算预算，因为典型余弦学习率依赖于总步数。而 Warmup-Stable-Decay (WSD) 计划则采用恒定学习率，生成一个理论上可无限延续的主分支，无需预设预算。随后，在任意预算下，可随时从主分支分支出一个快速衰减学习率的分支，生成强大模型。WSD 经验上生成非传统损失曲线：稳定阶段损失高企，衰减阶段则急剧下降。我们推测预训练损失呈现河流谷地景观，类似底部有河的深谷。据此，稳定阶段高学习率导致大幅振荡，但沿河快速前进；衰减阶段则迅速降低学习率，减少振荡，接近河流，揭示真实优化进展。高学习率持续阶段与快速衰减阶段分别推动河流与山脉方向进展，均至关重要。分析预测与观察一致，并表明此景观可从简单双字母组数据预训练中出现。受此启发，引入 WSD-S，重用先前检查点衰减阶段，仅保留一个主分支，从衰减检查点恢复。WSD-S 在单次运行中，从 0.1B 到 1.2B 参数规模下，在各种预算中获得多个语言模型检查点，表现优于 WSD 和 Cyclic-Cosine。

> Training language models currently requires pre-determining a fixed compute budget because the typical cosine learning rate schedule depends on the total number of steps. In contrast, the Warmup-Stable-Decay (WSD) schedule uses a constant learning rate to produce a main branch of iterates that can in principle continue indefinitely without a pre-specified compute budget. Then, given any compute budget, one can branch out from the main branch at a proper at any time with a rapidly decaying learning rate to produce a strong model. Empirically, WSD generates a non-traditional loss curve: the loss remains elevated during the stable phase but sharply declines during the decay phase. Towards explaining this phenomenon, we conjecture that pretraining loss exhibits a river valley landscape, which resembles a deep valley with a river at its bottom. Under this assumption, we show that during the stable phase, the iterate undergoes large oscillations due to the high learning rate, yet it progresses swiftly along the river. During the decay phase, the rapidly dropping learning rate minimizes the iterate's oscillations, moving it closer to the river and revealing true optimization progress. Therefore, the sustained high learning rate phase and fast decaying phase are responsible for progress in the river and the mountain directions respectively, and are both critical. Our analysis predicts phenomenons consistent with empirical observations and shows that this landscape can emerge from pretraining on a simple bi-gram dataset. Inspired by the theory, we introduce WSD-S, a variant of WSD that reuses previous checkpoints' decay phases and keeps only one main branch, where we resume from a decayed checkpoint. WSD-S empirically outperforms WSD and Cyclic-Cosine in obtaining multiple language model checkpoints across various compute budgets in a single run for parameters scaling from 0.1B to 1.2B.

[Arxiv](https://arxiv.org/abs/2410.05192)