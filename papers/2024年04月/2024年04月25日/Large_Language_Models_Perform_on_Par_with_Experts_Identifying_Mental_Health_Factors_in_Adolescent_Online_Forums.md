# 在青少年在线论坛中，大型语言模型展现出与专家相媲美的能力，精准识别出心理健康相关因素。

发布时间：2024年04月25日

`LLM应用` `心理健康` `数据集构建`

> Large Language Models Perform on Par with Experts Identifying Mental Health Factors in Adolescent Online Forums

# 摘要

> 近年来，儿童和青少年的心理健康问题日益严重。随着大型语言模型（LLMs）的兴起，我们看到了以更低的成本和更高效的时间来扩大监测和干预的希望。尽管学校霸凌和饮食失调等问题日益突出，但目前对于这些领域的研究，尤其是在开放信息提取——即答案集未预先设定的情况下——的表现尚未有深入探讨。本研究构建了一个新的数据集，包含12至19岁青少年在Reddit上的帖子，由专业精神病学家按照创伤、不稳定状况、疾病状况、症状、自杀倾向、治疗等类别进行标注，并与两款顶尖的LLMs（GPT3.5和GPT4）的标注结果进行比较。此外，我们还创建了两个合成数据集，用以评估LLMs在生成数据时同步进行标注的效果。研究发现，GPT4在一致性和性能上与人类专家不相上下，且在合成数据上的表现显著优于真实数据。然而，模型在处理否定和事实性问题时仍偶有失误，这表明合成数据的复杂性提升是其表现提高的主要原因，而非模型本身的内在优势。

> Mental health in children and adolescents has been steadily deteriorating over the past few years [ 1 ]. The recent advent of Large Language Models (LLMs) offers much hope for cost and time efficient scaling of monitoring and intervention, yet despite specifically prevalent issues such as school bullying and eating disorders, previous studies on have not investigated performance in this domain or for open information extraction where the set of answers is not predetermined. We create a new dataset of Reddit posts from adolescents aged 12-19 annotated by expert psychiatrists for the following categories: TRAUMA, PRECARITY, CONDITION, SYMPTOMS, SUICIDALITY and TREATMENT and compare expert labels to annotations from two top performing LLMs (GPT3.5 and GPT4). In addition, we create two synthetic datasets to assess whether LLMs perform better when annotating data as they generate it. We find GPT4 to be on par with human inter-annotator agreement and performance on synthetic data to be substantially higher, however we find the model still occasionally errs on issues of negation and factuality and higher performance on synthetic data is driven by greater complexity of real data rather than inherent advantage.

[Arxiv](https://arxiv.org/abs/2404.16461)