# 儿科肺炎的医学多模态大型语言模型

发布时间：2024年09月04日

`LLM应用` `人工智能`

> A Medical Multimodal Large Language Model for Pediatric Pneumonia

# 摘要

> 小儿肺炎，作为全球五岁以下儿童的头号杀手，给无数家庭带来了沉重负担。在诊断与治疗这一疾病时，我们面临三大难题：相似症状导致鉴别诊断困难、基层医疗资源匮乏、个性化诊疗方案耗时费力。为此，我们研发了P2Med-MLLM，一种专为小儿肺炎设计的多模态医学大型语言模型。该模型能处理包括生成放射报告在内的多种临床任务，并能处理文本与图像数据，其训练基于包含163,999例门诊和8,684例住院病例的大型数据集P2Med-MD。我们通过三阶段训练策略，使模型掌握医学知识，适应多样临床需求。为验证其性能，我们创建了P2Med-MBench基准，包含642个经专家验证的样本，覆盖六类临床决策任务。自动评分显示，P2Med-MLLM表现卓越，对提升基层医疗效率、降低重症死亡率及优化资源配置具有重要意义。

> Pediatric pneumonia is the leading cause of death among children under five years worldwide, imposing a substantial burden on affected families. Currently, there are three significant hurdles in diagnosing and treating pediatric pneumonia. Firstly, pediatric pneumonia shares similar symptoms with other respiratory diseases, making rapid and accurate differential diagnosis challenging. Secondly, primary hospitals often lack sufficient medical resources and experienced doctors. Lastly, providing personalized diagnostic reports and treatment recommendations is labor-intensive and time-consuming. To tackle these challenges, we proposed a Medical Multimodal Large Language Model for Pediatric Pneumonia (P2Med-MLLM). It was capable of handling diverse clinical tasks, such as generating free-text radiology reports and medical records within a unified framework. Specifically, P2Med-MLLM can process both pure text and image-text data, trained on an extensive and large-scale dataset (P2Med-MD), including real clinical information from 163,999 outpatient and 8,684 inpatient cases. This dataset comprised 2D chest X-ray images, 3D chest CT images, corresponding radiology reports, and outpatient and inpatient records. We designed a three-stage training strategy to enable P2Med-MLLM to comprehend medical knowledge and follow instructions for various clinical tasks. To rigorously evaluate P2Med-MLLM's performance, we developed P2Med-MBench, a benchmark consisting of 642 meticulously verified samples by pediatric pulmonology specialists, covering six clinical decision-support tasks and a balanced variety of diseases. The automated scoring results demonstrated the superiority of P2Med-MLLM. This work plays a crucial role in assisting primary care doctors with prompt disease diagnosis and treatment planning, reducing severe symptom mortality rates, and optimizing the allocation of medical resources.

[Arxiv](https://arxiv.org/abs/2409.02608)