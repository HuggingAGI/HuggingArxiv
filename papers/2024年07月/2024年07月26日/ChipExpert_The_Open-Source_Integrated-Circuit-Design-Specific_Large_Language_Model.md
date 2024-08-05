# ChipExpert：一款专为集成电路设计而生的开源大型语言模型

发布时间：2024年07月26日

`LLM应用` `集成电路设计`

> ChipExpert: The Open-Source Integrated-Circuit-Design-Specific Large Language Model

# 摘要

> 集成电路设计领域因其高度专业化而面临诸多挑战。尽管大型语言模型在多领域表现出色，但它们往往难以满足IC设计领域用户的特定需求。为此，我们推出了ChipExpert，首个专为IC设计定制的开源教学大型语言模型。基于顶尖的开源基础模型Llama-3 8B，ChipExpert的训练涵盖了数据准备、持续预训练、指令引导微调、偏好对齐及评估等关键阶段。通过精心筛选与数据合成，我们构建了高质量数据集，使ChipExpert在后续阶段能吸收大量IC设计知识并专业回应查询。此外，通过直接偏好优化，ChipExpert实现了伦理行为的高标准。为减少信息失真，我们引入了基于IC设计知识库的检索增强生成系统。同时，我们发布了首个IC设计基准ChipICD-Bench，全面评估LLMs在各子领域的能力。实验表明，ChipExpert在IC设计知识问答中展现了卓越的专业水平。

> The field of integrated circuit (IC) design is highly specialized, presenting significant barriers to entry and research and development challenges. Although large language models (LLMs) have achieved remarkable success in various domains, existing LLMs often fail to meet the specific needs of students, engineers, and researchers. Consequently, the potential of LLMs in the IC design domain remains largely unexplored. To address these issues, we introduce ChipExpert, the first open-source, instructional LLM specifically tailored for the IC design field. ChipExpert is trained on one of the current best open-source base model (Llama-3 8B). The entire training process encompasses several key stages, including data preparation, continue pre-training, instruction-guided supervised fine-tuning, preference alignment, and evaluation. In the data preparation stage, we construct multiple high-quality custom datasets through manual selection and data synthesis techniques. In the subsequent two stages, ChipExpert acquires a vast amount of IC design knowledge and learns how to respond to user queries professionally. ChipExpert also undergoes an alignment phase, using Direct Preference Optimization, to achieve a high standard of ethical performance. Finally, to mitigate the hallucinations of ChipExpert, we have developed a Retrieval-Augmented Generation (RAG) system, based on the IC design knowledge base. We also released the first IC design benchmark ChipICD-Bench, to evaluate the capabilities of LLMs across multiple IC design sub-domains. Through comprehensive experiments conducted on this benchmark, ChipExpert demonstrated a high level of expertise in IC design knowledge Question-and-Answer tasks.

[Arxiv](https://arxiv.org/abs/2408.00804)