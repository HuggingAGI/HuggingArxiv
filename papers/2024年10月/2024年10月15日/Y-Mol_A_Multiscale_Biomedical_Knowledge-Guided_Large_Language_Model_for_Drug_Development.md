# Y-Mol：一款多尺度生物医学知识驱动的大型语言模型，专为药物研发而生

发布时间：2024年10月15日

`LLM应用` `药物开发` `生物医学`

> Y-Mol: A Multiscale Biomedical Knowledge-Guided Large Language Model for Drug Development

# 摘要

> 大型语言模型 (LLM) 在多领域通用任务中表现出色，但在药物开发等特定领域仍面临挑战。为此，我们推出了 \textbf{Y-Mol}，一个专为药物开发流程设计的 LLM 范式。Y-Mol 结合多尺度生物医学知识与 LLaMA2 基础模型，通过学习出版物、知识图谱和专家数据，提升生物医学领域的推理能力。它还通过三种药物导向指令，进一步增强能力：处理出版物的描述提示、知识图谱的语义提示和生物医学工具的模板提示。Y-Mol 不仅能自主执行药物开发全过程的下游任务，如虚拟筛选、药物设计和药理预测，还在发现先导化合物和识别药物相互作用方面显著超越通用 LLM。

> Large Language Models (LLMs) have recently demonstrated remarkable performance in general tasks across various fields. However, their effectiveness within specific domains such as drug development remains challenges. To solve these challenges, we introduce \textbf{Y-Mol}, forming a well-established LLM paradigm for the flow of drug development. Y-Mol is a multiscale biomedical knowledge-guided LLM designed to accomplish tasks across lead compound discovery, pre-clinic, and clinic prediction. By integrating millions of multiscale biomedical knowledge and using LLaMA2 as the base LLM, Y-Mol augments the reasoning capability in the biomedical domain by learning from a corpus of publications, knowledge graphs, and expert-designed synthetic data. The capability is further enriched with three types of drug-oriented instructions: description-based prompts from processed publications, semantic-based prompts for extracting associations from knowledge graphs, and template-based prompts for understanding expert knowledge from biomedical tools. Besides, Y-Mol offers a set of LLM paradigms that can autonomously execute the downstream tasks across the entire process of drug development, including virtual screening, drug design, pharmacological properties prediction, and drug-related interaction prediction. Our extensive evaluations of various biomedical sources demonstrate that Y-Mol significantly outperforms general-purpose LLMs in discovering lead compounds, predicting molecular properties, and identifying drug interaction events.

[Arxiv](https://arxiv.org/abs/2410.11550)