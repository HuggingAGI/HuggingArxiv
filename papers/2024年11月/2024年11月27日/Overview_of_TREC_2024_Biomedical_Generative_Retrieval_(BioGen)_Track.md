# TREC 2024 生物医学生成式检索（BioGen）赛道概览

发布时间：2024年11月27日

`LLM应用` `生物医学` `语言模型`

> Overview of TREC 2024 Biomedical Generative Retrieval (BioGen) Track

# 摘要

> 随着大型语言模型（LLMs）的发展，生物医学领域在诸如生物医学问答、生物医学文献的通俗语言总结、临床笔记总结等众多任务上取得了显著的进步与提升。然而，幻觉或虚构仍是在生物医学等领域运用LLMs时面临的关键挑战之一。在诸如做出临床决策或评估生物医学研究等高风险情形下，不准确的情况可能尤为有害。有关LLMs将生成的陈述基于可验证来源的能力的评估研究显示，模型在普通用户生成的问题上表现明显欠佳，且常常无法参考相关来源。当寻求信息者希望从研究中获取证据以支撑LLMs的论断时，这可能会产生问题[3]。缺乏支持的陈述是在任何可能影响健康的应用中使用LLMs的主要阻碍。为克服这一阻碍，需要将生成的陈述基于可靠来源的方法以及实用的评估方法。为此，在我们于TREC 2024组织的试点任务中，我们引入了参考归因任务，以此来减少LLMs回答生物医学问题时产生的虚假陈述。

> With the advancement of large language models (LLMs), the biomedical domain has seen significant progress and improvement in multiple tasks such as biomedical question answering, lay language summarization of the biomedical literature, clinical note summarization, etc. However, hallucinations or confabulations remain one of the key challenges when using LLMs in the biomedical and other domains. Inaccuracies may be particularly harmful in high-risk situations, such as making clinical decisions or appraising biomedical research. Studies on the evaluation of the LLMs' abilities to ground generated statements in verifiable sources have shown that models perform significantly worse on lay-user generated questions, and often fail to reference relevant sources. This can be problematic when those seeking information want evidence from studies to back up the claims from LLMs[3]. Unsupported statements are a major barrier to using LLMs in any applications that may affect health. Methods for grounding generated statements in reliable sources along with practical evaluation approaches are needed to overcome this barrier. Towards this, in our pilot task organized at TREC 2024, we introduced the task of reference attribution as a means to mitigate the generation of false statements by LLMs answering biomedical questions.

[Arxiv](https://arxiv.org/abs/2411.18069)