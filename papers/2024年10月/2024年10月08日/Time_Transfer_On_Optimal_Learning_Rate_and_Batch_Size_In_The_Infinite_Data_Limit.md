# 时间转移：探索无限数据条件下最优学习率与批量大小的奥秘

发布时间：2024年10月08日

`LLM理论` `机器学习` `数据科学`

> Time Transfer: On Optimal Learning Rate and Batch Size In The Infinite Data Limit

# 摘要

> 在 LLM 的最佳扩展中，超参数调整的高成本（尤其是学习率和批量大小）是一个主要难题。尽管 $μ$P 技术为无限模型大小下的 $η$ 提供了扩展规则，但在无限数据大小下的最佳扩展行为仍未解。我们首次揭示了三种最佳 $η$ 扩展机制的相互作用，并发现这些转换受批量大小 $B$ 及其与随时间变化的临界批量大小 $B_\mathrm{crit}$ 的关系影响。此外，我们发现最佳批量大小与 $B_\mathrm{crit}$ 正相关，即使学习率最佳调整，固定批量大小也会随时间变得次优。令人惊讶的是，$μ$P 模型扩展中保留了这些动态，挑战了 $B_\mathrm{crit}$ 仅依赖于损失值的传统观点。我们还发现，损失对学习率变化的敏感性随数据量增加而降低，且在 $μ$P 模型扩展中保持不变。我们希望这些发现为统一的数据和模型扩展最佳图景奠定基础。

> One of the main challenges in optimal scaling of large language models (LLMs) is the prohibitive cost of hyperparameter tuning, particularly learning rate $η$ and batch size $B$. While techniques like $μ$P (Yang et al., 2022) provide scaling rules for optimal $η$ transfer in the infinite model size limit, the optimal scaling behavior in the infinite data size limit ($T \to \infty$) remains unknown. We fill in this gap by observing for the first time an interplay of three optimal $η$ scaling regimes: $η\propto \sqrt{T}$, $η\propto 1$, and $η\propto 1/\sqrt{T}$ with transitions controlled by $B$ and its relation to the time-evolving critical batch size $B_\mathrm{crit} \propto T$. Furthermore, we show that the optimal batch size is positively correlated with $B_\mathrm{crit}$: keeping it fixed becomes suboptimal over time even if learning rate is scaled optimally. Surprisingly, our results demonstrate that the observed optimal $η$ and $B$ dynamics are preserved with $μ$P model scaling, challenging the conventional view of $B_\mathrm{crit}$ dependence solely on loss value. Complementing optimality, we examine the sensitivity of loss to changes in learning rate, where we find the sensitivity to decrease with $T \to \infty$ and to remain constant with $μ$P model scaling. We hope our results make the first step towards a unified picture of the joint optimal data and model scaling.

[Arxiv](https://arxiv.org/abs/2410.05838)