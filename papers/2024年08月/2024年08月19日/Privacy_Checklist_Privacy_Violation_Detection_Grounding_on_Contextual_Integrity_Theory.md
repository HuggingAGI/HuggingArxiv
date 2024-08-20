# 隐私检测清单：依托上下文完整性理论，精准识别隐私侵犯行为

发布时间：2024年08月19日

`LLM应用` `隐私保护`

> Privacy Checklist: Privacy Violation Detection Grounding on Contextual Integrity Theory

# 摘要

> 隐私研究因个人对数据泄露的担忧而备受瞩目。计算机科学家通过隐私攻防研究这一问题，但现有研究多局限于特定领域，未能全面解决人们的隐私顾虑。本文将隐私视为推理问题，基于情境完整性理论，开发了涵盖社会身份、私人属性和法规的全面清单。我们以HIPAA为例，利用大型语言模型全面解读法规，并整合多领域专家注释，以识别私人信息。这一清单不仅为未来以情境为中心的隐私研究指明方向，还旨在扩展至更多法规和社会规范。

> Privacy research has attracted wide attention as individuals worry that their private data can be easily leaked during interactions with smart devices, social platforms, and AI applications. Computer science researchers, on the other hand, commonly study privacy issues through privacy attacks and defenses on segmented fields. Privacy research is conducted on various sub-fields, including Computer Vision (CV), Natural Language Processing (NLP), and Computer Networks. Within each field, privacy has its own formulation. Though pioneering works on attacks and defenses reveal sensitive privacy issues, they are narrowly trapped and cannot fully cover people's actual privacy concerns. Consequently, the research on general and human-centric privacy research remains rather unexplored. In this paper, we formulate the privacy issue as a reasoning problem rather than simple pattern matching. We ground on the Contextual Integrity (CI) theory which posits that people's perceptions of privacy are highly correlated with the corresponding social context. Based on such an assumption, we develop the first comprehensive checklist that covers social identities, private attributes, and existing privacy regulations. Unlike prior works on CI that either cover limited expert annotated norms or model incomplete social context, our proposed privacy checklist uses the whole Health Insurance Portability and Accountability Act of 1996 (HIPAA) as an example, to show that we can resort to large language models (LLMs) to completely cover the HIPAA's regulations. Additionally, our checklist also gathers expert annotations across multiple ontologies to determine private information including but not limited to personally identifiable information (PII). We use our preliminary results on the HIPAA to shed light on future context-centric privacy research to cover more privacy regulations, social norms and standards.

[Arxiv](https://arxiv.org/abs/2408.10053)