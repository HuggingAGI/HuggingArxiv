# 表之树：释放大型语言模型的力量以增强大规模表的理解

发布时间：2024年11月13日

`LLM应用`

> Tree-of-Table: Unleashing the Power of LLMs for Enhanced Large-Scale Table Understanding

# 摘要

> 表格作为各种领域中的半结构化数据，其无处不在和价值使得理解其复杂性和大量信息需要先进的方法。尽管大型语言模型（LLMs）在推进自然语言理解前沿方面具有令人印象深刻的能力，但它们在大规模表格数据中的应用存在重大挑战，特别是在表格大小和复杂的错综复杂关系方面。现有的工作在小规模表格上显示出了希望，但在处理现实场景中较大、相互关联的表格所需的复杂推理任务时，往往会陷入困境。为了解决这一差距，我们引入了“表格之树”，这是一种旨在增强 LLMs 对大型和复杂表格的推理能力的新方法。我们的方法采用表格浓缩和分解，将相关数据提炼和重新组织为可管理的格式，然后构建一个分层的表格树，以促进树状推理。通过细致的表格树执行过程，我们系统地解开树状推理链以得出解决方案。在包括 WikiTQ、TableFact、FeTaQA 和 BIRD 在内的各种数据集上进行的实验表明，表格之树设定了新的基准，具有卓越的性能，在大规模表格推理中展示出了显著的效率和泛化能力。

> The ubiquity and value of tables as semi-structured data across various domains necessitate advanced methods for understanding their complexity and vast amounts of information. Despite the impressive capabilities of large language models (LLMs) in advancing the natural language understanding frontier, their application to large-scale tabular data presents significant challenges, specifically regarding table size and complex intricate relationships. Existing works have shown promise with small-scale tables but often flounder when tasked with the complex reasoning required by larger, interconnected tables found in real-world scenarios. To address this gap, we introduce "Tree-of-Table", a novel approach designed to enhance LLMs' reasoning capabilities over large and complex tables. Our method employs Table Condensation and Decomposition to distill and reorganize relevant data into a manageable format, followed by the construction of a hierarchical Table-Tree that facilitates tree-structured reasoning. Through a meticulous Table-Tree Execution process, we systematically unravel the tree-structured reasoning chain to derive the solutions. Experiments across diverse datasets, including WikiTQ, TableFact, FeTaQA, and BIRD, demonstrate that Tree-of-Table sets a new benchmark with superior performance, showcasing remarkable efficiency and generalization capabilities in large-scale table reasoning.

[Arxiv](https://arxiv.org/abs/2411.08516)