# 错字引发的 RAG 崩溃：通过细微扰动在现实文档中模拟，对 RAG 流程发起基因级攻击

发布时间：2024年04月22日

`分类：RAG` `信息检索`

> Typos that Broke the RAG's Back: Genetic Attack on RAG Pipeline by Simulating Documents in the Wild via Low-level Perturbations

# 摘要

> 随着大型语言模型（LLMs）在多个领域和实际应用中的广泛应用，其鲁棒性变得日益关键。检索增强生成（RAG）作为一种应对LLMs局限性的解决方案，展现出巨大潜力。但是，目前对RAG鲁棒性的研究往往忽略了RAG组件间的内在联系以及现实世界数据库中常见的潜在威胁，如微小的文本错误。在本研究中，我们深入探讨了评估RAG鲁棒性的两个未被充分研究的维度：一是对含噪声文档的低层次扰动的敏感性；二是对RAG鲁棒性的全面评估。此外，我们提出了一种创新的攻击方法——遗传攻击RAG（GARAG），专门针对这些维度。GARAG设计用来暴露各个组件的弱点，并检验系统在面对噪声文档时的整体功能。我们通过将GARAG应用于标准问答（QA）数据集，并结合多种检索器和LLMs，来验证RAG的鲁棒性。实验结果显示，GARAG在攻击成功率上持续保持高水平，显著降低了各组件及其协同工作的性能，从而突显了现实世界中微小文本错误对RAG系统稳定性构成的重大威胁。

> The robustness of recent Large Language Models (LLMs) has become increasingly crucial as their applicability expands across various domains and real-world applications. Retrieval-Augmented Generation (RAG) is a promising solution for addressing the limitations of LLMs, yet existing studies on the robustness of RAG often overlook the interconnected relationships between RAG components or the potential threats prevalent in real-world databases, such as minor textual errors. In this work, we investigate two underexplored aspects when assessing the robustness of RAG: 1) vulnerability to noisy documents through low-level perturbations and 2) a holistic evaluation of RAG robustness. Furthermore, we introduce a novel attack method, the Genetic Attack on RAG (\textit{GARAG}), which targets these aspects. Specifically, GARAG is designed to reveal vulnerabilities within each component and test the overall system functionality against noisy documents. We validate RAG robustness by applying our \textit{GARAG} to standard QA datasets, incorporating diverse retrievers and LLMs. The experimental results show that GARAG consistently achieves high attack success rates. Also, it significantly devastates the performance of each component and their synergy, highlighting the substantial risk that minor textual inaccuracies pose in disrupting RAG systems in the real world.

[Arxiv](https://arxiv.org/abs/2404.13948)