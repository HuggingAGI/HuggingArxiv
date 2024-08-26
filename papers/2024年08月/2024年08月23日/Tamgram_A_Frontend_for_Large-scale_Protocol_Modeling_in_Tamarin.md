# Tamgram：Tamarin 大规模协议建模的前端工具

发布时间：2024年08月23日

`Agent` `网络安全` `软件工程`

> Tamgram: A Frontend for Large-scale Protocol Modeling in Tamarin

# 摘要

> 自动化安全协议验证工具，如 ProVerif 和 Tamarin，正广泛应用于验证复杂的大型现实世界协议。尽管这些工具在自动化处理大规模协议所需的复杂推理方面表现出色，但在建模语言方面仍有改进空间，尤其是在编写和维护大型协议规范方面。为此，我们引入了 Tamgram，一种高级协议建模语言，其形式语义可转换为 Tamarin 的多集重写语义。Tamgram 不仅支持直接编写 Tamarin 原生代码，还通过高级结构简化了大型规范的构建，特别是那些涉及协议状态操作的结构。我们证明了 Tamgram 在 Tamarin 迹语义下的健全性和完备性，探讨了不同的翻译策略，并找到了一种性能与手动编码 Tamarin 规范相当的最优策略。通过一系列案例研究，包括一个小型案例集和一个大型案例，我们展示了 Tamgram 的实际应用价值。

> Automated security protocol verifiers such as ProVerif and Tamarin have been increasingly applied to verify large scale complex real-world protocols. While their ability to automate difficult reasoning processes required to handle protocols at that scale is impressive, there remains a gap in the modeling languages used. In particular, providing support for writing and maintaining large protocol specifications. This work attempts to fill this gap by introducing a high-level protocol modeling language, called Tamgram, with a formal semantics that can be translated to the multiset rewriting semantics of Tamarin. Tamgram supports writing native Tamarin code directly, but also allows for easier structuring of large specifications through various high-level constructs, in particular those needed to manipulate states in protocols. We prove the soundness and the completeness of Tamgram with respect to the trace semantics of Tamarin, discuss different translation strategies, and identify an optimal strategy that yields performance comparable to manually coded Tamarin specifications. Finally we show the practicality of Tamgram with a set of small case studies and one large scale case study.

[Arxiv](https://arxiv.org/abs/2408.13138)