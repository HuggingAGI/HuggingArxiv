# 借助大型语言模型，我们能够生成真实的多代理知识工作数据集。

发布时间：2024年09月06日

`Agent` `知识工作` `数据集生成`

> Using Large Language Models to Generate Authentic Multi-agent Knowledge Work Datasets

# 摘要

> 当前公开的知识工作数据集存在多样性不足、注释不全面以及缺乏用户和文档的上下文信息等问题，这限制了知识工作辅助系统的客观评估和优化。由于现实环境中收集此类数据成本高昂且需进行数据审查，构建这样的数据集几乎不可能。为此，我们设计了一个可配置的多代理知识工作数据集生成器，模拟代理间的协作，生成大型语言模型文档及数据跟踪，并将所有背景信息存储于知识图中，确保数据集的使用和共享无隐私顾虑。本文展示了我们方法的设计理念，并强调了使用大型语言模型生成真实知识文档的能力。研究中，人类评估者认为53%的生成文档和74%的真实文档具有现实感，凸显了该方法的潜力。同时，我们深入分析了评估者提及的真实性标准，并针对常见问题提出了改进建议。

> Current publicly available knowledge work data collections lack diversity, extensive annotations, and contextual information about the users and their documents. These issues hinder objective and comparable data-driven evaluations and optimizations of knowledge work assistance systems. Due to the considerable resources needed to collect such data in real-life settings and the necessity of data censorship, collecting such a dataset appears nearly impossible. For this reason, we propose a configurable, multi-agent knowledge work dataset generator. This system simulates collaborative knowledge work among agents producing Large Language Model-generated documents and accompanying data traces. Additionally, the generator captures all background information, given in its configuration or created during the simulation process, in a knowledge graph. Finally, the resulting dataset can be utilized and shared without privacy or confidentiality concerns.
  This paper introduces our approach's design and vision and focuses on generating authentic knowledge work documents using Large Language Models. Our study involving human raters who assessed 53% of the generated and 74% of the real documents as realistic demonstrates the potential of our approach. Furthermore, we analyze the authenticity criteria mentioned in the participants' comments and elaborate on potential improvements for identified common issues.

[Arxiv](https://arxiv.org/abs/2409.04286)