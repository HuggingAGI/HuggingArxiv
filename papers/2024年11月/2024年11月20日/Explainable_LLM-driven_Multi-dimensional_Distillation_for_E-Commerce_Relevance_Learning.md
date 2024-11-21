# 用于电子商务相关性学习的可解释的 LLM 驱动多维蒸馏

发布时间：2024年11月20日

`LLM应用` `电子商务` `搜索系统`

> Explainable LLM-driven Multi-dimensional Distillation for E-Commerce Relevance Learning

# 摘要

> 有效的查询-项目相关性建模对于增强电子商务搜索系统中的用户体验、保障用户满意度起着关键作用。近来，凭借丰富的内在知识，大型语言模型（LLM）方法相较于此前基于神经的专门相关性学习方法，展现出了强劲的性能和长尾泛化能力。虽说前景光明，但当下基于LLM的方法在实际运用中存在如下缺陷：其一，庞大的参数和计算需求致使其难以在线部署。其二，把LLM模型提炼为在线模型虽为可行方向，然而LLM相关性建模犹如黑箱，其丰富的内在知识难以提取并在线应用。为提升LLM的可解释性，并借LLM之力推动在线相关性模型的性能，我们提出了一个用于电子商务相关性学习的可解释LLM驱动的多维蒸馏框架，它涵盖两个核心部分：（1）用于相关性建模的可解释LLM（ELLM-rele），它把相关性学习拆解为中间步骤，并将相关性学习构建为思维链（CoT）推理，由此提升LLM的可解释性与性能。（2）一个多维知识蒸馏（MKD）架构，从相关性得分分布和CoT推理层面把ELLM-rele的知识传递给当前可部署的基于交互和基于表示的学生模型。通过蒸馏概率和CoT推理知识，MKD增强了学生模型的语义交互和长尾泛化能力。在淘宝搜索广告场景展开的大量离线评估和在线实验表明，我们所提出的框架显著提升了电子商务相关性学习的性能和用户体验。

> Effective query-item relevance modeling is pivotal for enhancing user experience and safeguarding user satisfaction in e-commerce search systems. Recently, benefiting from the vast inherent knowledge, Large Language Model (LLM) approach demonstrates strong performance and long-tail generalization ability compared with previous neural-based specialized relevance learning methods. Though promising, current LLM-based methods encounter the following inadequacies in practice: First, the massive parameters and computational demands make it difficult to be deployed online. Second, distilling LLM models to online models is a feasible direction, but the LLM relevance modeling is a black box, and its rich intrinsic knowledge is difficult to extract and apply online. To improve the interpretability of LLM and boost the performance of online relevance models via LLM, we propose an Explainable LLM-driven Multi-dimensional Distillation framework for e-commerce relevance learning, which comprises two core components: (1) An Explainable LLM for relevance modeling (ELLM-rele), which decomposes the relevance learning into intermediate steps and models relevance learning as a Chain-of-Thought (CoT) reasoning, thereby enhancing both interpretability and performance of LLM. (2) A Multi-dimensional Knowledge Distillation (MKD) architecture that transfers the knowledge of ELLM-rele to current deployable interaction-based and representation-based student models from both the relevance score distribution and CoT reasoning aspects. Through distilling the probabilistic and CoT reasoning knowledge, MKD improves both the semantic interaction and long-tail generalization abilities of student models. Extensive offline evaluations and online experiments on Taobao search ad scene demonstrate that our proposed framework significantly enhances e-commerce relevance learning performance and user experience.

[Arxiv](https://arxiv.org/abs/2411.13045)