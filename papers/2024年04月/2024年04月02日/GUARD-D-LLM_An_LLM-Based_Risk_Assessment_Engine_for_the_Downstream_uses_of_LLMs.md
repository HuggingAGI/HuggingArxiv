# GUARD-D-LLM：大型语言模型下游应用的风险评估引擎

发布时间：2024年04月02日

`Agent

理由：这篇论文主要介绍了一个名为 GUARD-D-LLM 的风险评估引擎，该引擎集成了三十个智能代理（Agent），用于识别和评估大型语言模型（LLMs）在下游应用中可能引发的风险。这些代理不仅能够识别特定风险，评估其严重性，还能提供针对性的缓解措施。因此，这篇论文的核心在于智能代理的应用，而不是LLM的理论研究或特定的LLM应用案例，也不是关于检索增强生成（RAG）的研究。因此，将其归类为Agent是最合适的。` `风险管理` `人工智能`

> GUARD-D-LLM: An LLM-Based Risk Assessment Engine for the Downstream uses of LLMs

# 摘要

> 随着对AI系统造成的危害的担忧不断升级，风险管理变得尤为重要，特别是在欧盟AI法案所要求的高风险应用领域。尽管ISO和NIST提供了AI风险管理的指导原则，但学术文献中的实际应用案例仍然不多。为此，我们的研究深入探讨了大型语言模型（LLMs）在下游应用中可能引发的风险，并基于先前的研究构建了一个风险分类体系。在此基础上，我们开发了一个名为GUARD-D-LLM的新型风险评估引擎，它能够针对特定用例，从文本用户输入中精准识别并排序潜在威胁。该引擎集成了三十个智能代理，不仅能识别特定风险，评估其严重性，还能提供针对性的缓解措施，并推动风险意识的发展。本文不仅指出了这种方法的局限性，还提出了改进建议，以增强专家在风险评估中的能力，从而利用GUARD-D-LLM早期识别风险并实施早期缓解措施。本文及其相关代码为希望减轻基于LLM的应用程序风险的开发者提供了宝贵的资源。

> Amidst escalating concerns about the detriments inflicted by AI systems, risk management assumes paramount importance, notably for high-risk applications as demanded by the European Union AI Act. Guidelines provided by ISO and NIST aim to govern AI risk management; however, practical implementations remain scarce in scholarly works. Addressing this void, our research explores risks emanating from downstream uses of large language models (LLMs), synthesizing a taxonomy grounded in earlier research. Building upon this foundation, we introduce a novel LLM-based risk assessment engine (GUARD-D-LLM: Guided Understanding and Assessment for Risk Detection for Downstream use of LLMs) designed to pinpoint and rank threats relevant to specific use cases derived from text-based user inputs. Integrating thirty intelligent agents, this innovative approach identifies bespoke risks, gauges their severity, offers targeted suggestions for mitigation, and facilitates risk-aware development. The paper also documents the limitations of such an approach along with way forward suggestions to augment experts in such risk assessment thereby leveraging GUARD-D-LLM in identifying risks early on and enabling early mitigations. This paper and its associated code serve as a valuable resource for developers seeking to mitigate risks associated with LLM-based applications.

[Arxiv](https://arxiv.org/abs/2406.11851)