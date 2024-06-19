# GUARD-D-LLM：大型语言模型下游应用的风险评估引擎

发布时间：2024年04月02日

`Agent

这篇论文主要关注的是大型语言模型（LLMs）在下游应用中的风险管理，并开发了一个名为GUARD-D-LLM的风险评估引擎。该引擎通过集成多个智能代理来识别和量化风险，并提供缓解措施。这与Agent分类相关，因为论文的核心在于使用智能代理来管理和评估风险。虽然涉及到LLM的应用，但其重点在于风险管理和智能代理的使用，而非LLM的理论研究或特定的应用案例。因此，Agent是最合适的分类。` `风险管理` `人工智能`

> GUARD-D-LLM: An LLM-Based Risk Assessment Engine for the Downstream uses of LLMs

# 摘要

> 随着AI系统带来的危害日益受到关注，风险管理在高风险应用中显得尤为重要，尤其是在欧盟AI法案的要求下。尽管ISO和NIST提供了AI风险管理的指导原则，但学术界的实际应用案例仍然不多。为此，我们的研究聚焦于大型语言模型（LLMs）下游应用中的风险，并基于先前的研究构建了一个风险分类体系。在此基础上，我们开发了GUARD-D-LLM（引导理解和评估LLMs下游使用的风险检测），这一创新的风险评估引擎能够针对文本用户输入的特定场景，精准定位并评估风险。通过集成三十个智能代理，GUARD-D-LLM不仅识别并量化风险，还提供针对性的缓解措施，推动风险意识的发展。本文还指出了该方法的局限性，并提出了改进建议，旨在帮助专家更有效地进行风险评估，从而及早发现并缓解风险。本文及其附带的代码为希望降低基于LLM应用风险的开发者提供了宝贵的参考资料。

> Amidst escalating concerns about the detriments inflicted by AI systems, risk management assumes paramount importance, notably for high-risk applications as demanded by the European Union AI Act. Guidelines provided by ISO and NIST aim to govern AI risk management; however, practical implementations remain scarce in scholarly works. Addressing this void, our research explores risks emanating from downstream uses of large language models (LLMs), synthesizing a taxonomy grounded in earlier research. Building upon this foundation, we introduce a novel LLM-based risk assessment engine (GUARD-D-LLM: Guided Understanding and Assessment for Risk Detection for Downstream use of LLMs) designed to pinpoint and rank threats relevant to specific use cases derived from text-based user inputs. Integrating thirty intelligent agents, this innovative approach identifies bespoke risks, gauges their severity, offers targeted suggestions for mitigation, and facilitates risk-aware development. The paper also documents the limitations of such an approach along with way forward suggestions to augment experts in such risk assessment thereby leveraging GUARD-D-LLM in identifying risks early on and enabling early mitigations. This paper and its associated code serve as a valuable resource for developers seeking to mitigate risks associated with LLM-based applications.

[Arxiv](https://arxiv.org/abs/2406.11851)