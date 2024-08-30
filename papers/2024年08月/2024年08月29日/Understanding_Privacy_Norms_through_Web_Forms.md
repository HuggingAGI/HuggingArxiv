# 探究网页表单中的隐私规范

发布时间：2024年08月29日

`LLM应用` `网络安全` `隐私保护`

> Understanding Privacy Norms through Web Forms

# 摘要

> 网页表单作为在线收集个人信息的主要途径，其研究尚显不足。与隐秘的网页追踪不同，表单数据收集直接且情境明确。用户需输入特定信息，并清楚其使用场景与目的。为赢得用户信任，表单设计需遵循特定情境下的合理数据收集标准，即隐私规范。本文通过测量研究，深入挖掘表单中的隐私规范。首先，我们开发专用爬虫，遍历11,500个热门网站，构建包含293K表单的数据集。接着，借助大型语言模型（LLM）训练的文本分类器，高效标注表单类型与个人信息类型。分析标注数据后，我们揭示了数据收集的常见模式，这些模式由功能需求与法律义务驱动，体现了隐私规范，而偏离规范则常意味着不必要的数据收集。此外，我们还审视了伴随表单的隐私政策，发现尽管广泛应用，政策披露与实际隐私规范间仍存在鸿沟。

> Web forms are one of the primary ways to collect personal information online, yet they are relatively under-studied. Unlike web tracking, data collection through web forms is explicit and contextualized. Users (i) are asked to input specific personal information types, and (ii) know the specific context (i.e., on which website and for what purpose). For web forms to be trusted by users, they must meet the common sense standards of appropriate data collection practices within a particular context (i.e., privacy norms). In this paper, we extract the privacy norms embedded within web forms through a measurement study. First, we build a specialized crawler to discover web forms on websites. We run it on 11,500 popular websites, and we create a dataset of 293K web forms. Second, to process data of this scale, we develop a cost-efficient way to annotate web forms with form types and personal information types, using text classifiers trained with assistance of large language models (LLMs). Third, by analyzing the annotated dataset, we reveal common patterns of data collection practices. We find that (i) these patterns are explained by functional necessities and legal obligations, thus reflecting privacy norms, and that (ii) deviations from the observed norms often signal unnecessary data collection. In addition, we analyze the privacy policies that accompany web forms. We show that, despite their wide adoption and use, there is a disconnect between privacy policy disclosures and the observed privacy norms.

[Arxiv](https://arxiv.org/abs/2408.16304)