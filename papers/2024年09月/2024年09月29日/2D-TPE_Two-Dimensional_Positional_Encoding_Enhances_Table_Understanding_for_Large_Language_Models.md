# 二维位置编码（2D-TPE）为大语言模型理解表格提供了强大助力。

发布时间：2024年09月29日

`LLM应用` `数据分析` `人工智能`

> 2D-TPE: Two-Dimensional Positional Encoding Enhances Table Understanding for Large Language Models

# 摘要

> 表格在各领域中广泛用于简洁表示结构化信息。然而，现有方法常将二维表格展平为一维序列，导致空间关系和上下文信息丢失。本文通过两个实验，揭示了这种展平操作对 LLM 性能的负面影响。为此，我们提出了一种名为“2D-TPE”的简单而有效的位置编码方法，使每个注意力头能动态选择令牌排列顺序，从而保留表格结构。实验证明，2D-TPE 在多个基准上优于基线，强调了保留表格结构的重要性。此外，2D-TPE 在处理大型表格时展现出更好的可扩展性。

> Tables are ubiquitous across various domains for concisely representing structured information. Empowering large language models (LLMs) to reason over tabular data represents an actively explored direction. However, since typical LLMs only support one-dimensional~(1D) inputs, existing methods often flatten the two-dimensional~(2D) table structure into a sequence of tokens, which can severely disrupt the spatial relationships and result in an inevitable loss of vital contextual information. In this paper, we first empirically demonstrate the detrimental impact of such flattening operations on the performance of LLMs in capturing the spatial information of tables through two elaborate proxy tasks. Subsequently, we introduce a simple yet effective positional encoding method, termed ``2D-TPE'' (Two-Dimensional Table Positional Encoding), to address this challenge. 2D-TPE enables each attention head to dynamically select a permutation order of tokens within the context for attending to them, where each permutation represents a distinct traversal mode for the table, such as column-wise or row-wise traversal. 2D-TPE effectively mitigates the risk of losing essential spatial information while preserving computational efficiency, thus better preserving the table structure. Extensive experiments across five benchmarks demonstrate that 2D-TPE outperforms strong baselines, underscoring the importance of preserving the table structure for accurate table comprehension. Comprehensive analysis further reveals the substantially better scalability of 2D-TPE to large tables than baselines.

[Arxiv](https://arxiv.org/abs/2409.19700)