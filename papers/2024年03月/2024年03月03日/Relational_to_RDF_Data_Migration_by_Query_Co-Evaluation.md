# [借助查询协同求值技术，实现从关系型数据向 RDF 数据的迁移步骤 1 直译：关系型数据到 RDF 数据迁移通过查询协同求值实现步骤 2 简洁优雅翻译：本研究探讨了一种基于查询协同求值的方法，用于实现关系型数据库与 RDF 数据间的高效迁移。](https://arxiv.org/abs/2403.01630)

> Relational to RDF Data Migration by Query Co-Evaluation

发布时间：2024年03月03日

> 本文提出一种创新算法，可将输入的关系数据库转化为RDF三元组集，进而实现如将CSV数据无缝融入FIBO等金融OWL本体。此算法以各输入表格对应的一个关系合取查询集作为输入，查询基于输出RDF模式的“主语-谓语-宾语”三列结构与输入表格的关系模式进行匹配。算法生成的独特RDF三元组集确保了在给定关系查询下，输入数据有唯一回路映射；其中可能包含空白节点，并且通过简单的形式化方法如等式定理证明和项模型构建即可获取。同时，鉴于三列RDF模式内在结构较弱，我们探讨了运用（广义）图同态原理撰写实际应用中通常规模较大的关系合取查询的方法。最后，我们结合FIBO金融本体，演示了该算法及映射语言的实际应用案例。

> In this paper we define a new algorithm to convert an input relational database to an output set of RDF triples. The algorithm can be used to e.g. load CSV data into a financial OWL ontology such as FIBO. The algorithm takes as input a set of relational conjunctive (select-from-where) queries, one for each input table, from the three column (subject, predicate, object) output RDF schema to the input table's relational schema. The algorithm's output is the only set of RDF triples for which a unique round-trip of the input data under the relational queries exists. The output may contain blank nodes, is unique up to unique isomorphism, and can be obtained using elementary formal methods (equational theorem proving and term model construction specifically). We also describe how (generalized) homomorphisms between graphs can be used to write such relational conjunctive (select-from-where) queries, which, due to the lack of structure in the three-column RDF schema, tend to be large in practice. We demonstrate examples of both the algorithm and mapping language on the FIBO financial ontology.

`Agent`