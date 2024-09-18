# 通过蒸馏技术提升文档理解：FLAN-T5 案例研究

发布时间：2024年09月17日

`LLM应用` `文档理解`

> Leveraging Distillation Techniques for Document Understanding: A Case Study with FLAN-T5

# 摘要

> 数字文档的激增，尤其是商业报告和环境评估等非标准化文档，凸显了文档理解的重要性。尽管大型语言模型 (LLM) 在 NLP 任务中表现出色，但在文档理解中的应用仍面临挑战。虽然 LLM 在此领域展示了实用性，但其高计算需求限制了实际部署。此外，专有 LLM 通常优于开源模型，阻碍了广泛应用。本文探讨了文档理解领域，通过蒸馏方法，在计算限制下利用 LLM 的强大能力。我们提出了一种新方法，将 ChatGPT 的文档理解知识蒸馏到 FLAN-T5 中，结合标签和课程学习机制，实现高效知识转移。这项工作通过提供可扩展解决方案，弥合了资源密集型 LLM 与实际应用之间的差距，推动了文档理解方法的发展。研究结果表明，蒸馏技术在促进复杂语言模型在现实场景中的部署方面具有巨大潜力，推动了 NLP 和文档理解领域的进步。

> The surge of digital documents in various formats, including less standardized documents such as business reports and environmental assessments, underscores the growing importance of Document Understanding. While Large Language Models (LLMs) have showcased prowess across diverse natural language processing tasks, their direct application to Document Understanding remains a challenge. Previous research has demonstrated the utility of LLMs in this domain, yet their significant computational demands make them challenging to deploy effectively. Additionally, proprietary Blackbox LLMs often outperform their open-source counterparts, posing a barrier to widespread accessibility. In this paper, we delve into the realm of document understanding, leveraging distillation methods to harness the power of large LLMs while accommodating computational limitations. Specifically, we present a novel approach wherein we distill document understanding knowledge from the proprietary LLM ChatGPT into FLAN-T5. Our methodology integrates labeling and curriculum-learning mechanisms to facilitate efficient knowledge transfer. This work contributes to the advancement of document understanding methodologies by offering a scalable solution that bridges the gap between resource-intensive LLMs and practical applications. Our findings underscore the potential of distillation techniques in facilitating the deployment of sophisticated language models in real-world scenarios, thereby fostering advancements in natural language processing and document comprehension domains.

[Arxiv](https://arxiv.org/abs/2409.11282)