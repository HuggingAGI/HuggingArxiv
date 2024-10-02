# 知识库问答中的语义解析：候选表达式的应用

发布时间：2024年10月01日

`LLM应用` `知识图谱` `问答系统`

> Semantic Parsing with Candidate Expressions for Knowledge Base Question Answering

# 摘要

> 语义解析器将自然语言转化为逻辑形式，以便在知识库上评估并生成指称。最新的语义解析器利用了 seq2seq 预训练模型或大型语言模型，将逻辑形式视为令牌序列。为确保语法和语义的正确性，解析器采用语法进行受限解码。然而，尽管逻辑形式包含 KB 元素的表示，现有语法却难以充分利用 KB 的丰富信息。为此，我们提出了一种增强候选表达式的语法，用于在大型 KB 上进行语义解析。该语法将动作定义为产生规则，并在推理过程中在类型和候选表达式的约束下预测动作。我们将其应用于知识库问答，候选表达式的约束有助于生成有效的 KB 元素。实验结果显示，无论是在强监督还是弱监督下训练，候选表达式的约束均显著提升了解析器的准确性，使其在 KQA Pro 和 Overnight 基准测试中达到了最先进的水平。

> Semantic parsers convert natural language to logical forms, which can be evaluated on knowledge bases (KBs) to produce denotations. Recent semantic parsers have been developed with sequence-to-sequence (seq2seq) pre-trained language models (PLMs) or large language models, where the models treat logical forms as sequences of tokens. For syntactic and semantic validity, the semantic parsers use grammars that enable constrained decoding. However, the grammars lack the ability to utilize large information of KBs, although logical forms contain representations of KB elements, such as entities or relations. In this work, we propose a grammar augmented with candidate expressions for semantic parsing on a large KB with a seq2seq PLM. The grammar defines actions as production rules, and our semantic parser predicts actions during inference under the constraints by types and candidate expressions. We apply the grammar to knowledge base question answering, where the constraints by candidate expressions assist a semantic parser to generate valid KB elements. In experiments on two benchmarks, KQA Pro and Overnight, the constraints by candidate expressions increased the accuracy of our semantic parser, whether it was trained with strong supervision or weak supervision. Our semantic parser achieved state-of-the-art accuracies on KQA Pro and Overnight.

[Arxiv](https://arxiv.org/abs/2410.00414)