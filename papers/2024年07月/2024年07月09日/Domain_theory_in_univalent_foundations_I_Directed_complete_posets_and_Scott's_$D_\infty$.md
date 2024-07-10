# 一致性基础中的域理论 I：探讨有向完备偏序集与 Scott 的 $D_\infty$

发布时间：2024年07月09日

`LLM理论` `编程语言` `拓扑学`

> Domain theory in univalent foundations I: Directed complete posets and Scott's $D_\infty$

# 摘要

> 我们基于构造性和预测性一致基础（即同伦类型理论）开发了领域理论。我们不采用Voevodsky的命题大小调整公理，也不依赖排中律或选择公理，确保了工作的构造性。领域理论专注于有向完全偏序集（dcpos）及其间的Scott连续映射，广泛应用于编程语言语义、高类型可计算性和拓扑学等领域。在预测性基础中，我们通常采用信息系统、抽象基或形式拓扑来处理大小问题，而非直接使用dcpos和Scott连续函数。然而，在我们的类型理论方法中，我们承认dcpos可能规模庞大，并利用类型宇宙来应对这一挑战。尽管先验上可能认为dcpos的迭代构造需要不断扩大的宇宙，且在预测性上难以实现，但我们通过精确追踪类型宇宙参数，证明了这类构造在预测性环境中是可行的。特别是，我们成功地在预测性框架下重建了Scott的$D_\infty$模型，该模型用于未类型化的$λ$-演算。这一成果在Agda证明助手中得到了形式化，其自动推断宇宙级别的功能对我们的研究至关重要。

> We develop domain theory in constructive and predicative univalent foundations (also known as homotopy type theory). That we work predicatively means that we do not assume Voevodsky's propositional resizing axioms. Our work is constructive in the sense that we do not rely on excluded middle or the axiom of (countable) choice. Domain theory studies so-called directed complete posets (dcpos) and Scott continuous maps between them and has applications in a variety of fields, such as programming language semantics, higher-type computability and topology. A common approach to deal with size issues in a predicative foundation is to work with information systems, abstract bases or formal topologies rather than dcpos, and approximable relations rather than Scott continuous functions. In our type-theoretic approach, we instead accept that dcpos may be large and work with type universes to account for this. A priori one might expect that iterative constructions of dcpos may result in a need for ever-increasing universes and are predicatively impossible. We show, through a careful tracking of type universe parameters, that such constructions can be carried out in a predicative setting. In particular, we give a predicative reconstruction of Scott's $D_\infty$ model of the untyped $λ$-calculus. Our work is formalised in the Agda proof assistant and its ability to infer universe levels has been invaluable for our purposes.

[Arxiv](https://arxiv.org/abs/2407.06952)