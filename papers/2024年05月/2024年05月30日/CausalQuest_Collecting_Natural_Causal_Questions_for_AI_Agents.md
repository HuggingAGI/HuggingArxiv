# 因果探索：为AI代理搜集自然因果问题集

发布时间：2024年05月30日

`Agent

理由：这篇论文主要介绍了创建一个名为 CausalQuest 的数据集，该数据集旨在帮助训练 AI 理解因果关系。论文中提到通过人工与大型语言模型（LLMs）的合作来标注数据集，并训练了一个分类器来识别因果问题。这表明工作重点在于开发和利用 AI 系统（Agent）来处理和理解因果关系，而不是专注于 LLM 的理论研究或特定应用。因此，这篇论文更适合归类为Agent。` `社交媒体` `人工智能`

> CausalQuest: Collecting Natural Causal Questions for AI Agents

# 摘要

> 人类天生追求因果关系，不断探索事物背后的原因及其相互联系。为了培养能满足这一自然探索的AI，我们需要一个涵盖自然因果问题的全面数据集。现有的数据集要么过于人工，要么来源单一。为此，我们推出了CausalQuest，一个包含13,500个来自社交媒体、搜索引擎和AI助手的自然问题数据集。我们明确了因果问题的定义，并细化了分类。通过人工与LLMs的合作，我们精心标注了数据集，发现42%的人类问题涉及因果，多数旨在探究原因。基于此，我们训练了高效分类器（最高2.85亿参数），用于识别因果问题，F1分数高达0.877。最后，我们展望了基于此数据和模型的丰富研究前景。

> Humans have an innate drive to seek out causality. Whether fuelled by curiosity or specific goals, we constantly question why things happen, how they are interconnected, and many other related phenomena. To develop AI agents capable of addressing this natural human quest for causality, we urgently need a comprehensive dataset of natural causal questions. Unfortunately, existing datasets either contain only artificially-crafted questions that do not reflect real AI usage scenarios or have limited coverage of questions from specific sources. To address this gap, we present CausalQuest, a dataset of 13,500 naturally occurring questions sourced from social networks, search engines, and AI assistants. We formalize the definition of causal questions and establish a taxonomy for finer-grained classification. Through a combined effort of human annotators and large language models (LLMs), we carefully label the dataset. We find that 42% of the questions humans ask are indeed causal, with the majority seeking to understand the causes behind given effects. Using this dataset, we train efficient classifiers (up to 2.85B parameters) for the binary task of identifying causal questions, achieving high performance with F1 scores of up to 0.877. We conclude with a rich set of future research directions that can build upon our data and models.

[Arxiv](https://arxiv.org/abs/2405.20318)