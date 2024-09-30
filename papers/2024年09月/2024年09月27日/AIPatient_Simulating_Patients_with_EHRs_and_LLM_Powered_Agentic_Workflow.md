# AIPatient：借助 EHRs 和 LLM 驱动的智能工作流程，模拟患者体验。

发布时间：2024年09月27日

`RAG`

> AIPatient: Simulating Patients with EHRs and LLM Powered Agentic Workflow

# 摘要

> 模拟患者系统在现代医学教育和研究中至关重要，提供安全的学习环境并支持临床决策模拟。大型语言模型（LLM）通过高保真度和低成本复制医患互动，推动了这一领域的发展。然而，确保这些系统的有效性和可信度仍具挑战，需要庞大且精确的患者知识库。我们开发的AIPatient系统，以AIPatient知识图谱为输入，利用推理检索增强生成（Reasoning RAG）代理工作流，从MIMIC-III数据库中提取数据，生成1,495名患者的高效知识库。Reasoning RAG通过六个LLM驱动的代理，在医学问答中达到94.15%的准确率，超越了现有基准。系统还具备高可读性、鲁棒性和稳定性，显示出在医学教育、模型评估和系统集成中的广泛应用潜力。

> Simulated patient systems play a crucial role in modern medical education and research, providing safe, integrative learning environments and enabling clinical decision-making simulations. Large Language Models (LLM) could advance simulated patient systems by replicating medical conditions and patient-doctor interactions with high fidelity and low cost. However, ensuring the effectiveness and trustworthiness of these systems remains a challenge, as they require a large, diverse, and precise patient knowledgebase, along with a robust and stable knowledge diffusion to users. Here, we developed AIPatient, an advanced simulated patient system with AIPatient Knowledge Graph (AIPatient KG) as the input and the Reasoning Retrieval-Augmented Generation (Reasoning RAG) agentic workflow as the generation backbone. AIPatient KG samples data from Electronic Health Records (EHRs) in the Medical Information Mart for Intensive Care (MIMIC)-III database, producing a clinically diverse and relevant cohort of 1,495 patients with high knowledgebase validity (F1 0.89). Reasoning RAG leverages six LLM powered agents spanning tasks including retrieval, KG query generation, abstraction, checker, rewrite, and summarization. This agentic framework reaches an overall accuracy of 94.15% in EHR-based medical Question Answering (QA), outperforming benchmarks that use either no agent or only partial agent integration. Our system also presents high readability (median Flesch Reading Ease 77.23; median Flesch Kincaid Grade 5.6), robustness (ANOVA F-value 0.6126, p<0.1), and stability (ANOVA F-value 0.782, p<0.1). The promising performance of the AIPatient system highlights its potential to support a wide range of applications, including medical education, model evaluation, and system integration.

[Arxiv](https://arxiv.org/abs/2409.18924)