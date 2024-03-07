# [WikiTableEdit 是一个专门针对通过自然语言指令进行表格编辑任务的基准测试工具，旨在评估和衡量模型在理解并执行基于文本的表格修改指令方面的性能。](https://arxiv.org/abs/2403.02962)

> WikiTableEdit: A Benchmark for Table Editing by Natural Language Instruction

发布时间：2024年03月05日

> 表格数据作为重要数据形态在网络中广泛存在，其多样化的格式给复杂和不规则表格的处理带来了手动调整难题。本研究关注大型语言模型（LLMs）在应对表格编辑任务时的表现。目前的研究主要集中于规律结构的表格，并借助指令生成SQL、Python或Excel脚本来操控表格。然而，对于那些含有跨多行合并单元格的不规则表格，采用代码编辑则较为棘手。为此，我们创新构建了WikiTableEdit数据集，基于WikiSQL数据集中的26,531个表格，自动生成描述六种基础操作及相应结果变化的自然语言说明，总共生成超过20万份样本实例。接下来，我们选取了几款有代表性的大型语言模型，在WikiTableEdit数据集上进行了评测，以此验证任务的挑战性。为了推动相关研究发展，我们将向社区公开这一数据集。

> Tabular data, as a crucial form of data representation, exists in diverse formats on the Web. When confronted with complex and irregular tables, manual modification becomes a laborious task. This paper investigates the performance of Large Language Models (LLMs) in the context of table editing tasks. Existing research mainly focuses on regular-shaped tables, wherein instructions are used to generate code in SQL, Python, or Excel Office-script for manipulating the tables. Nevertheless, editing tables with irregular structures, particularly those containing merged cells spanning multiple rows, poses a challenge when using code. To address this, we introduce the WikiTableEdit dataset. Leveraging 26,531 tables from the WikiSQL dataset, we automatically generate natural language instructions for six distinct basic operations and the corresponding outcomes, resulting in over 200,000 instances. Subsequently, we evaluate several representative large language models on the WikiTableEdit dataset to demonstrate the challenge of this task. The dataset will be released to the community to promote related researches.

`LLM应用`