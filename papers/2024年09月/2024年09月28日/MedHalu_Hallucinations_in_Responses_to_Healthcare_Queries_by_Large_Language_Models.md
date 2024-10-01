# MedHalu: 大型语言模型在处理医疗查询时出现的幻觉问题

发布时间：2024年09月28日

`LLM应用` `人工智能`

> MedHalu: Hallucinations in Responses to Healthcare Queries by Large Language Models

# 摘要

> 尽管 LLM 在语言理解和生成方面表现出色，但它们仍可能产生听起来合理但事实错误的幻觉信息。随着 LLM 驱动的聊天机器人普及，普通人可能频繁询问健康问题，面临被幻觉误导的风险，进而引发社会和医疗问题。为此，我们首次对 LLM 在真实医疗查询中的幻觉现象进行了研究，并推出了 MedHalu 数据集，涵盖多样化的健康话题及相应的幻觉响应，并标记了幻觉类型和文本范围。我们还设计了 MedHaluDetect 框架，用于评估 LLM 的幻觉检测能力。通过对比医疗专家、LLM 和普通人的评估结果，我们发现 LLM 在幻觉检测上表现不佳，甚至有时不如普通人。为解决这一问题，我们提出了“专家参与”方法，通过融入专家推理来提升 LLM 的幻觉检测能力，显著提高了 GPT-4 等模型的性能。

> The remarkable capabilities of large language models (LLMs) in language understanding and generation have not rendered them immune to hallucinations. LLMs can still generate plausible-sounding but factually incorrect or fabricated information. As LLM-empowered chatbots become popular, laypeople may frequently ask health-related queries and risk falling victim to these LLM hallucinations, resulting in various societal and healthcare implications. In this work, we conduct a pioneering study of hallucinations in LLM-generated responses to real-world healthcare queries from patients. We propose MedHalu, a carefully crafted first-of-its-kind medical hallucination dataset with a diverse range of health-related topics and the corresponding hallucinated responses from LLMs with labeled hallucination types and hallucinated text spans. We also introduce MedHaluDetect framework to evaluate capabilities of various LLMs in detecting hallucinations. We also employ three groups of evaluators -- medical experts, LLMs, and laypeople -- to study who are more vulnerable to these medical hallucinations. We find that LLMs are much worse than the experts. They also perform no better than laypeople and even worse in few cases in detecting hallucinations. To fill this gap, we propose expert-in-the-loop approach to improve hallucination detection through LLMs by infusing expert reasoning. We observe significant performance gains for all the LLMs with an average macro-F1 improvement of 6.3 percentage points for GPT-4.

[Arxiv](https://arxiv.org/abs/2409.19492)