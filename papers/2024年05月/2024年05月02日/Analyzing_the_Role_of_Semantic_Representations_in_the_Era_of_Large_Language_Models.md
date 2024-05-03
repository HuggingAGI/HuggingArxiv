# 在大型语言模型盛行的当下，深入探讨语义表示的角色与重要性。

发布时间：2024年05月02日

`LLM应用` `机器学习`

> Analyzing the Role of Semantic Representations in the Era of Large Language Models

# 摘要

> 在传统NLP模型中，专家们精心构建的语义表示等特征集曾是关键。但在大型语言模型（LLMs）盛行的今天，众多任务已简化为标准化的序列生成问题。本文旨在探究：在LLMs主导的当下，语义表示的功能何在？我们特别关注了抽象意义表示（AMR）在五项多样化NLP任务中的应用。我们引入了一种新颖的AMR驱动的思维链提示技术，命名为AMRCoT，却发现其效果往往适得其反。为了深入理解AMR的潜力，我们开展了一系列深入的分析实验。实验结果表明，AMR对输入样本的正负影响难以预判，但问题多出现在多词短语、命名实体识别以及LLM将AMR推理与预测结果相连结的最终步骤。基于此，我们建议未来的研究应聚焦于这些关键领域，以优化LLMs中的语义表示。相关代码已在GitHub上公开：https://github.com/causalNLP/amr_llm。

> Traditionally, natural language processing (NLP) models often use a rich set of features created by linguistic expertise, such as semantic representations. However, in the era of large language models (LLMs), more and more tasks are turned into generic, end-to-end sequence generation problems. In this paper, we investigate the question: what is the role of semantic representations in the era of LLMs? Specifically, we investigate the effect of Abstract Meaning Representation (AMR) across five diverse NLP tasks. We propose an AMR-driven chain-of-thought prompting method, which we call AMRCoT, and find that it generally hurts performance more than it helps. To investigate what AMR may have to offer on these tasks, we conduct a series of analysis experiments. We find that it is difficult to predict which input examples AMR may help or hurt on, but errors tend to arise with multi-word expressions, named entities, and in the final inference step where the LLM must connect its reasoning over the AMR to its prediction. We recommend focusing on these areas for future work in semantic representations for LLMs. Our code: https://github.com/causalNLP/amr_llm.

[Arxiv](https://arxiv.org/abs/2405.01502)