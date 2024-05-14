# 检索增强生成评估综述：本调查旨在深入探讨检索增强生成技术的评估方法，分析其在不同应用场景下的表现，并探讨如何优化这一技术以提升生成内容的质量和相关性。

发布时间：2024年05月12日

`RAG

这篇论文主要关注的是检索增强生成（RAG）技术在自然语言处理中的评估问题，并提出了一套分析框架（RAGR）来系统地评估RAG系统。它探讨了RAG系统的评估挑战，包括相关性、准确性和忠实性等关键指标，并指出了现有评估方法的局限性以及未来研究的方向。因此，这篇论文的内容与RAG技术紧密相关，属于RAG分类。` `评估基准`

> Evaluation of Retrieval-Augmented Generation: A Survey

# 摘要

> 检索增强生成（RAG）技术在自然语言处理领域崭露头角，通过引入外部信息检索，显著提升了生成模型的能力。然而，RAG系统的评估因其混合性质和对动态知识源的依赖而变得复杂。为此，我们深入研究并提出了一套名为RAGR的分析框架，专门用于系统地评估RAG系统的基准。该框架聚焦于可量化的输出和已知事实，详细审查了检索和生成组件的多个关键指标，如相关性、准确性和忠实性，并探讨了现有评估方法的内部链接。此外，我们还探讨了不同研究中的额外要求，指出了当前基准的局限，并提出了未来研究的方向，以期克服这些限制，推动RAG评估领域的进步。本文全面分析了RAG评估的挑战，并基于RGAR框架，对现有的RAG基准设计方法进行了深入的探讨。

> Retrieval-Augmented Generation (RAG) has emerged as a pivotal innovation in natural language processing, enhancing generative models by incorporating external information retrieval. Evaluating RAG systems, however, poses distinct challenges due to their hybrid structure and reliance on dynamic knowledge sources. We consequently enhanced an extensive survey and proposed an analysis framework for benchmarks of RAG systems, RAGR (Retrieval, Generation, Additional Requirement), designed to systematically analyze RAG benchmarks by focusing on measurable outputs and established truths. Specifically, we scrutinize and contrast multiple quantifiable metrics of the Retrieval and Generation component, such as relevance, accuracy, and faithfulness, of the internal links within the current RAG evaluation methods, covering the possible output and ground truth pairs. We also analyze the integration of additional requirements of different works, discuss the limitations of current benchmarks, and propose potential directions for further research to address these shortcomings and advance the field of RAG evaluation. In conclusion, this paper collates the challenges associated with RAG evaluation. It presents a thorough analysis and examination of existing methodologies for RAG benchmark design based on the proposed RGAR framework.

[Arxiv](https://arxiv.org/abs/2405.07437)