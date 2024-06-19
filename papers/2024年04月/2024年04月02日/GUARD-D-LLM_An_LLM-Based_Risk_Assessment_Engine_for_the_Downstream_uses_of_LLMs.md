# GUARD-D-LLM：大型语言模型下游应用的风险评估引擎

发布时间：2024年04月02日

`Agent

理由：这篇论文主要探讨了大型语言模型（LLMs）在下游应用中的风险，并开发了一个名为GUARD-D-LLM的风险评估引擎。该引擎集成了三十个智能代理，用于识别、评估风险严重性，并提供针对性的缓解建议。因此，这篇论文的核心在于使用智能代理（Agent）来管理和评估风险，属于Agent分类。虽然论文涉及LLM的应用，但其重点在于风险管理和智能代理的应用，而非LLM的理论或应用本身。` `风险管理` `人工智能`

> GUARD-D-LLM: An LLM-Based Risk Assessment Engine for the Downstream uses of LLMs

# 摘要

> 随着AI系统带来的危害日益加剧，风险管理在高风险应用中变得尤为重要，尤其是在欧盟AI法案的要求下。尽管ISO和NIST提供了AI风险管理的指南，但学术文献中的实际应用仍显不足。我们的研究填补了这一空白，探讨了大型语言模型（LLMs）下游应用中的风险，并基于先前研究构建了一个风险分类体系。在此基础上，我们开发了GUARD-D-LLM，一个创新的风险评估引擎，它能够针对特定文本输入用例，精确定位并排序相关威胁。该引擎集成了三十个智能代理，不仅识别并评估风险严重性，还提供针对性的缓解建议，推动风险意识的发展。本文还指出了该方法的局限性，并提出了改进建议，以增强专家的风险评估能力，从而利用GUARD-D-LLM早期识别并缓解风险。本文及其相关代码为开发者提供了宝贵的资源，帮助他们减轻基于LLM的应用程序的风险。

> Amidst escalating concerns about the detriments inflicted by AI systems, risk management assumes paramount importance, notably for high-risk applications as demanded by the European Union AI Act. Guidelines provided by ISO and NIST aim to govern AI risk management; however, practical implementations remain scarce in scholarly works. Addressing this void, our research explores risks emanating from downstream uses of large language models (LLMs), synthesizing a taxonomy grounded in earlier research. Building upon this foundation, we introduce a novel LLM-based risk assessment engine (GUARD-D-LLM: Guided Understanding and Assessment for Risk Detection for Downstream use of LLMs) designed to pinpoint and rank threats relevant to specific use cases derived from text-based user inputs. Integrating thirty intelligent agents, this innovative approach identifies bespoke risks, gauges their severity, offers targeted suggestions for mitigation, and facilitates risk-aware development. The paper also documents the limitations of such an approach along with way forward suggestions to augment experts in such risk assessment thereby leveraging GUARD-D-LLM in identifying risks early on and enabling early mitigations. This paper and its associated code serve as a valuable resource for developers seeking to mitigate risks associated with LLM-based applications.

[Arxiv](https://arxiv.org/abs/2406.11851)