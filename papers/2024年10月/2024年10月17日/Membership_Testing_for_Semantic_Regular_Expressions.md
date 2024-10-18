# 语义正则表达式的成员资格检测

发布时间：2024年10月17日

`LLM应用` `计算机科学`

> Membership Testing for Semantic Regular Expressions

# 摘要

> SMORE（Chen 等人，2023 年）最近引入了语义正则表达式，通过查询外部资源（如数据库和 LLM）扩展了经典形式。这些模式能识别包含特定语义概念（如城市、名人、政治实体）引用的文本行。他们的研究侧重于从正负示例中自动合成这些表达式。本文探讨了成员测试问题：首先，我们设计了一种基于 NFA 的两遍算法，用于判断字符串 $w$ 是否匹配 SemRE $r$，时间复杂度为 $O(|r|^2 |w|^2 + |r| |w|^3)$，假设预言机查询时间为单位时间。在非嵌套查询的常见情况下，该算法仅需 $O(|r|^2 |w|^2)$ 时间。实验证明，该算法显著优于动态规划基线，且在预言机交互时间上仅增加约 $2 \times$ 的开销。其次，我们揭示了 SemRE 成员测试与图论中的三角形查找问题之间的联系，暗示开发既实用又更快的算法可能颇具挑战。经典正则表达式算法侧重于优化时间和内存，而我们的重点在于最小化预言机调用成本。我们证明了必要的预言机查询数量下限为 $Ω(|w|^2)$。

> SMORE (Chen et al., 2023) recently proposed the concept of semantic regular expressions that extend the classical formalism with a primitive to query external oracles such as databases and large language models (LLMs). Such patterns can be used to identify lines of text containing references to semantic concepts such as cities, celebrities, political entities, etc. The focus in their paper was on automatically synthesizing semantic regular expressions from positive and negative examples. In this paper, we study the membership testing problem:
  First, We present a two-pass NFA-based algorithm to determine whether a string $w$ matches a semantic regular expression (SemRE) $r$ in $O(|r|^2 |w|^2 + |r| |w|^3)$ time, assuming the oracle responds to each query in unit time. In common situations, where oracle queries are not nested, we show that this procedure runs in $O(|r|^2 |w|^2)$ time. Experiments with a prototype implementation of this algorithm validate our theoretical analysis, and show that the procedure massively outperforms a dynamic programming-based baseline, and incurs a $\approx 2 \times$ overhead over the time needed for interaction with the oracle.
  Next, We establish connections between SemRE membership testing and the triangle finding problem from graph theory, which suggest that developing algorithms which are simultaneously practical and asymptotically faster might be challenging. Furthermore, algorithms for classical regular expressions primarily aim to optimize their time and memory consumption. In contrast, an important consideration in our setting is to minimize the cost of invoking the oracle. We demonstrate an $Ω(|w|^2)$ lower bound on the number of oracle queries necessary to make this determination.

[Arxiv](https://arxiv.org/abs/2410.13262)