# 利用 LLM 的提示工程技术进行隐私政策分析

发布时间：2024年09月23日

`LLM应用` `隐私保护`

> Privacy Policy Analysis through Prompt Engineering for LLMs

# 摘要

> 隐私政策因其复杂性常导致透明度不足和知情同意难以实现。传统机器学习方法在自动分析这些政策时，需大量资源和专业训练，适应性差，且依赖需频繁维护的大数据集。本文提出并评估了PAPEL框架，利用LLM通过提示工程自动化隐私政策分析。PAPEL旨在简化信息提取、注释和总结，提升政策可访问性和理解性，无需额外训练。通过整合多种学习方法和思维链提示，PAPEL指导LLM高效剖析、解释和综合政策关键点为易懂摘要。我们通过注释和矛盾分析展示了PAPEL的有效性。实验表明，PAPEL使用的LLaMA和Chat GPT模型在政策注释中表现优异，F1分数达0.8以上，凸显了简单提示在高级语言模型中的高效性。

> Privacy policies are often obfuscated by their complexity, which impedes transparency and informed consent. Conventional machine learning approaches for automatically analyzing these policies demand significant resources and substantial domain-specific training, causing adaptability issues. Moreover, they depend on extensive datasets that may require regular maintenance due to changing privacy concerns.
  In this paper, we propose, apply, and assess PAPEL (Privacy Policy Analysis through Prompt Engineering for LLMs), a framework harnessing the power of Large Language Models (LLMs) through prompt engineering to automate the analysis of privacy policies. PAPEL aims to streamline the extraction, annotation, and summarization of information from these policies, enhancing their accessibility and comprehensibility without requiring additional model training. By integrating zero-shot, one-shot, and few-shot learning approaches and the chain-of-thought prompting in creating predefined prompts and prompt templates, PAPEL guides LLMs to efficiently dissect, interpret, and synthesize the critical aspects of privacy policies into user-friendly summaries. We demonstrate the effectiveness of PAPEL with two applications: (i) annotation and (ii) contradiction analysis. We assess the ability of several LLaMa and GPT models to identify and articulate data handling practices, offering insights comparable to existing automated analysis approaches while reducing training efforts and increasing the adaptability to new analytical needs. The experiments demonstrate that the LLMs PAPEL utilizes (LLaMA and Chat GPT models) achieve robust performance in privacy policy annotation, with F1 scores reaching 0.8 and above (using the OPP-115 gold standard), underscoring the effectiveness of simpler prompts across various advanced language models.

[Arxiv](https://arxiv.org/abs/2409.14879)