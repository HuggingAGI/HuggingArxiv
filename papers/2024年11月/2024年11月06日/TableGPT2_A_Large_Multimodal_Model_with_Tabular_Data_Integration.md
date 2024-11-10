# TableGPT2：一个具有表格数据集成的大型多模态模型

发布时间：2024年11月06日

`LLM应用` `商业智能` `数据集成`

> TableGPT2: A Large Multimodal Model with Tabular Data Integration

# 摘要

> 像 GPTs、Claude、LLaMA 和 Qwen 这样的模型的出现重塑了人工智能应用，为各行业带来了大量新机遇。然而，尽管表格数据在众多现实领域具有基础作用，但它的整合仍显著不发达。
  这种差距至关重要，主要有三个原因。首先，数据库或数据仓库数据集成对于高级应用至关重要；其次，大量且基本未开发的表格数据资源具有巨大的分析潜力；第三，商业智能领域特别需要许多当前的 LLMs 可能难以提供的适应性强、精确的解决方案。
  作为回应，我们引入了 TableGPT2，这是一个经过严格预训练和微调的模型，使用了超过 593.8 万个表格和 236 万个高质量的查询-表格-输出元组，这是之前研究中前所未有的表格相关数据规模。这种广泛的训练使 TableGPT2 在以表格为中心的任务中表现出色，同时保持强大的通用语言和编码能力。
  TableGPT2 的关键创新之一是其新颖的表格编码器，专门设计用于捕获模式级别和单元格级别的信息。该编码器增强了模型处理现实应用中常见的模糊查询、缺失列名和不规则表格的能力。与视觉语言模型类似，这种开创性的方法与解码器集成，形成了一个强大的大型多模态模型。
  我们认为结果令人信服：在超过 23 个基准指标中，与之前的基准中立 LLMs 相比，TableGPT2 在 7B 模型中平均性能提高了 35.20％，在 72B 模型中提高了 49.32％，同时保持了强大的通用能力。

> The emergence of models like GPTs, Claude, LLaMA, and Qwen has reshaped AI applications, presenting vast new opportunities across industries. Yet, the integration of tabular data remains notably underdeveloped, despite its foundational role in numerous real-world domains.
  This gap is critical for three main reasons. First, database or data warehouse data integration is essential for advanced applications; second, the vast and largely untapped resource of tabular data offers immense potential for analysis; and third, the business intelligence domain specifically demands adaptable, precise solutions that many current LLMs may struggle to provide.
  In response, we introduce TableGPT2, a model rigorously pre-trained and fine-tuned with over 593.8K tables and 2.36M high-quality query-table-output tuples, a scale of table-related data unprecedented in prior research. This extensive training enables TableGPT2 to excel in table-centric tasks while maintaining strong general language and coding abilities.
  One of TableGPT2's key innovations is its novel table encoder, specifically designed to capture schema-level and cell-level information. This encoder strengthens the model's ability to handle ambiguous queries, missing column names, and irregular tables commonly encountered in real-world applications. Similar to visual language models, this pioneering approach integrates with the decoder to form a robust large multimodal model.
  We believe the results are compelling: over 23 benchmarking metrics, TableGPT2 achieves an average performance improvement of 35.20% in the 7B model and 49.32% in the 72B model over prior benchmark-neutral LLMs, with robust general-purpose capabilities intact.

[Arxiv](https://arxiv.org/abs/2411.02059)