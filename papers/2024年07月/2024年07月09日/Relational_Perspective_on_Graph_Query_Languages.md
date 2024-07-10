# 图查询语言的关系视角探析

发布时间：2024年07月09日

`LLM理论` `数据库` `图数据库`

> Relational Perspective on Graph Query Languages

# 摘要

> 我们探讨了图数据库查询的关系视角，这一视角虽为多种图数据库系统的基础，但理论研究甚少。该视角构建了一个强大且统一的框架，用于研究图数据库查询，其算法与复杂性源自经典理论。我们展示了两个具体应用：  首先，我们查询属性图。属性图数据模型超越了以往的图模型，并支撑了新的图查询语言标准GQL。我们证明，该标准主要可通过关系演算的扩展来表达，包括传递闭包算子（FO[TC]）和存在二阶量词（ESO），从而获得最优数据复杂度界限及模式验证等扩展。  其次，我们将具体领域数据（如数字）融入图数据库查询。利用嵌入的有限模型理论及FO[TC]和ESO的通用受限量词崩溃（RQC）结果，我们为含算术与比较的GQL设定了最优数据复杂度界限。同时，我们揭示了在嵌入有限图上，通过数据操作的常规数据路径查询可在FO[TC]中实现，且保持非确定性对数空间的数据复杂度。

> We study a relational perspective of graph database querying. Such a perspective underlies various graph database systems but very few theoretical investigations have been conducted on it. This perspective offers a powerful and unified framework to study graph database querying, by which algorithms and complexity follow from classical results. We provide two concrete applications.
  The first is querying property graphs. The property graph data model supersedes previously proposed graph models and underlies the new standard GQL for graph query languages. We show that this standard can be, by and large, expressed by extensions of relational calculus with transitive closure operators (FO[TC]) and existential second-order quantifiers (ESO). With this, we obtain optimal data complexity bounds, along with extensions including schema validation.
  The second application is incorporating data from concrete domains (e.g., numbers) in graph database querying. We use embedded finite model theory and, by exploiting a generic Restricted Quantifier Collapse (RQC) result for FO[TC] and ESO, we obtain optimal data complexity bounds for GQL with arithmetics and comparisons. Moreover, we show that Regular Data Path Querying with operations on data (i.e. using register automata formalisms) can be captured in FO[TC] over embedded finite graphs while preserving nondeterministic logspace data complexity.

[Arxiv](https://arxiv.org/abs/2407.06766)