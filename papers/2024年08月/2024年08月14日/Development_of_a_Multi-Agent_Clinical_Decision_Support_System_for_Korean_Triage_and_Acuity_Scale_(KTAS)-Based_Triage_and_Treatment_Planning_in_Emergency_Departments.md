# 开发基于KTAS的多代理系统，助力急诊分诊与治疗决策

发布时间：2024年08月14日

`Agent` `急诊医学`

> Development of a Multi-Agent Clinical Decision Support System for Korean Triage and Acuity Scale (KTAS)-Based Triage and Treatment Planning in Emergency Departments

# 摘要

> 急诊科的拥挤和重症监护中的快速决策复杂性是全球医疗系统面临的重大挑战。尽管临床决策支持系统（CDSS）已显示出潜力，但大型语言模型（LLM）的整合为提升分诊准确性和临床决策带来了新机遇。本研究介绍了一种由LLM驱动的CDSS，旨在辅助急诊科医护人员进行患者分诊、治疗规划和急诊护理管理。我们开发了一个多代理CDSS，以Llama-3-70b为基础LLM，由CrewAI和Langchain协调。系统包含四个模拟急诊科关键角色的AI代理：分诊护士、急诊医生、药剂师和急诊协调员。它采用韩国分诊和危重程度量表（KTAS）进行分诊评估，并与RxNorm API集成以管理药物。该模型通过Asclepius数据集评估，由临床急诊医学专家评估性能。与单一代理系统相比，CDSS在分诊决策上表现出高准确性。此外，系统在主要诊断、关键发现识别、处置决策、治疗计划和资源分配等关键领域表现出色。我们的多代理CDSS展现了支持全面急诊护理管理的巨大潜力。借助尖端AI技术，该系统提供了一个可扩展且适应性强的工具，有望提升急诊医疗服务，缓解急诊科拥挤，并改善患者结果。这项工作为急诊医学中日益增长的AI应用领域贡献了力量，并为未来研究和临床应用指明了方向。

> Emergency department (ED) overcrowding and the complexity of rapid decision-making in critical care settings pose significant challenges to healthcare systems worldwide. While clinical decision support systems (CDSS) have shown promise, the integration of large language models (LLMs) offers new possibilities for enhancing triage accuracy and clinical decision-making. This study presents an LLM-driven CDSS designed to assist ED physicians and nurses in patient triage, treatment planning, and overall emergency care management.
  We developed a multi-agent CDSS utilizing Llama-3-70b as the base LLM, orchestrated by CrewAI and Langchain. The system comprises four AI agents emulating key ED roles: Triage Nurse, Emergency Physician, Pharmacist, and ED Coordinator. It incorporates the Korean Triage and Acuity Scale (KTAS) for triage assessment and integrates with the RxNorm API for medication management.
  The model was evaluated using the Asclepius dataset, with performance assessed by a clinical emergency medicine specialist. The CDSS demonstrated high accuracy in triage decision-making compared to the baseline of a single-agent system. Furthermore, the system exhibited strong performance in critical areas, including primary diagnosis, critical findings identification, disposition decision-making, treatment planning, and resource allocation.
  Our multi-agent CDSS demonstrates significant potential for supporting comprehensive emergency care management. By leveraging state-of-the-art AI technologies, this system offers a scalable and adaptable tool that could enhance emergency medical care delivery, potentially alleviating ED overcrowding and improving patient outcomes. This work contributes to the growing field of AI applications in emergency medicine and offers a promising direction for future research and clinical implementation.

[Arxiv](https://arxiv.org/abs/2408.07531)