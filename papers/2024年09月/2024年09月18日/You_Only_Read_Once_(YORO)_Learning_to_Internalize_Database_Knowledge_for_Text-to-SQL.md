# YORO：通过一次阅读，将数据库知识内化，实现文本到 SQL 的转换。

发布时间：2024年09月18日

`LLM应用` `数据库` `人工智能`

> You Only Read Once (YORO): Learning to Internalize Database Knowledge for Text-to-SQL

# 摘要

> 尽管文本到SQL任务取得了显著进展，但现有方法反复编码数据库模式，导致高昂的推理成本并忽略关键数据库知识。为此，我们提出YORO，一种在训练时将数据库知识内化到模型参数中，推理时无需编码模式的新范式。YORO大幅缩短输入长度（66%-98%），在三个基准测试中与传统系统表现相当，尤其在大数据库上表现突出。此外，YORO在处理复杂值检索问题（如缩写）时表现优异。

> While significant progress has been made on the text-to-SQL task, recent solutions repeatedly encode the same database schema for every question, resulting in unnecessary high inference cost and often overlooking crucial database knowledge. To address these issues, we propose You Only Read Once (YORO), a novel paradigm that directly internalizes database knowledge into the parametric knowledge of a text-to-SQL model during training and eliminates the need for schema encoding during inference. YORO significantly reduces the input token length by 66%-98%. Despite its shorter inputs, our empirical results demonstrate YORO's competitive performances with traditional systems on three benchmarks as well as its significant outperformance on large databases. Furthermore, YORO excels in handling questions with challenging value retrievals such as abbreviation.

[Arxiv](https://arxiv.org/abs/2409.12172)