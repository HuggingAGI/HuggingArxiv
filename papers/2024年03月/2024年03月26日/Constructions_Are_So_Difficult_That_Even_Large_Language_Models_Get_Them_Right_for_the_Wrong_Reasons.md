# 即便是先进的大型语言模型，在处理复杂构建（Constructions）时也常误打误撞地得出正确结果。

发布时间：2024年03月26日

`RAG` `计算语言学
</example>`

> Constructions Are So Difficult That Even Large Language Models Get Them Right for the Wrong Reasons

> 本文提出了一项双视角贡献：NLP视角下，我们设计了一个词汇重叠度高的NLI挑战性数据集，降低了模型仅通过标记差异判断逻辑蕴含的可能性，并发现GPT-4和Llama 2在此任务上表现出明显的偏见且失败。我们进一步构建了挑战性子任务，以深入解析这一失败现象。计算语言学视角下，我们发现一类含有三种形容词的句式，其无法仅凭表面特征进行区分。我们通过多种方式检验LLM对这些句式的把握，结果显示它们在区分这些句式时存在多种失败模式，说明LLM未能充分理解其含义或掌握短语核心的词汇特性。

> In this paper, we make a contribution that can be understood from two perspectives: from an NLP perspective, we introduce a small challenge dataset for NLI with large lexical overlap, which minimises the possibility of models discerning entailment solely based on token distinctions, and show that GPT-4 and Llama 2 fail it with strong bias. We then create further challenging sub-tasks in an effort to explain this failure. From a Computational Linguistics perspective, we identify a group of constructions with three classes of adjectives which cannot be distinguished by surface features. This enables us to probe for LLM's understanding of these constructions in various ways, and we find that they fail in a variety of ways to distinguish between them, suggesting that they don't adequately represent their meaning or capture the lexical properties of phrasal heads.

[Arxiv](https://arxiv.org/abs/2403.17760)