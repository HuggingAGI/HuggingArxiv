# 高效的针对文本和表格的学习查询执行 [技术报告]

发布时间：2024年10月29日

`LLM应用` `数据库` `多模态处理`

> Efficient Learned Query Execution over Text and Tables [Technical Report]

# 摘要

> 在本文中，我们推出了 ELEET 这一全新的执行引擎，它能让文本和表格一同作为一等公民被无缝查询及处理。为达成文本与表格的无缝融合，ELEET 借助了诸如连接和联合之类的已学习多模态运算符（MMOps），将结构化和非结构化的文本数据完美结合。尽管像 GPT-4 这样的大型语言模型（LLM）是实现此类学习多模态操作的不错选择，但我们特意不顺应这一潮流来启用 MMOps，因为这会在查询运行时产生高额开销。相反，为启用 MMOps，ELEET 配备了一个更高效的小型语言模型（SLM），专门用于从文本中提取结构化数据。得益于我们新颖的架构和预训练流程，ELEET 模型能够以低开销实现高精度提取。在评估中，我们将基于 ELEET 的查询执行与借助 GPT-4 等 LLM 的基线进行对比，结果表明 ELEET 能在不损失准确性的前提下，将表格和文本的多模态查询速度提升高达 575 倍。

> In this paper, we present ELEET, a novel execution engine that allows one to seamlessly query and process text as a first-class citizen along with tables. To enable such a seamless integration of text and tables, ELEET leverages learned multi-modal operators (MMOps) such as joins and unions that seamlessly combine structured with unstructured textual data. While large language models (LLM) such as GPT-4 are interesting candidates to enable such learned multimodal operations, we deliberately do not follow this trend to enable MMOps, since it would result in high overhead at query runtime. Instead, to enable MMOps, ELEET comes with a more efficient small language model (SLM) that is targeted to extract structured data from text. Thanks to our novel architecture and pre-training procedure, the ELEET-model enables high-accuracy extraction with low overheads. In our evaluation, we compare query execution based on ELEET to baselines leveraging LLMs such as GPT-4 and show that ELEET can speed up multi-modal queries over tables and text by up to 575x without sacrificing accuracy.

[Arxiv](https://arxiv.org/abs/2410.22522)