# WisPerMed 参与“Discharge Me!”项目，通过大型语言模型、动态专家选择及预处理技术，在 MIMIC-IV 数据库上推动医疗文本生成的进步。

发布时间：2024年05月18日

`LLM应用

理由：这篇论文主要探讨了如何利用尖端语言模型自动化医疗记录中的特定部分，以减轻临床医生的行政负担并提高医疗运营效率。论文中提到的技术应用，如少量样本学习、指令调整及动态专家选择（DES），都是为了优化模型在特定医疗文档生成任务中的表现。这些应用直接关联到大型语言模型（LLM）的实际应用场景，特别是在医疗领域的自动化文档处理，因此属于LLM应用类别。` `电子健康记录`

> WisPerMed at "Discharge Me!": Advancing Text Generation in Healthcare with Large Language Models, Dynamic Expert Selection, and Priming Techniques on MIMIC-IV

# 摘要

> 本研究利用尖端语言模型，旨在自动化MIMIC-IV数据集中的出院总结“简要住院过程”及“出院指导”部分，以减轻临床医生的行政负担。我们探讨了自动化如何提升文档准确性、缓解临床疲劳并增强医疗运营效率。在参加2024年BioNLP @ ACL的Shared Task Discharge Me!期间，我们采用了少量样本学习、指令调整及动态专家选择（DES）等策略，开发出能生成所需文本的模型。特别地，DES方法通过优化多预测文本输出选择，表现出色，在比赛中以0.332的高分领先，超越了单一模型。这表明，结合DES的高级深度学习方法能有效自动化电子健康记录，从而通过释放临床时间提升患者护理。文本选择策略的整合为未来研究开辟了新途径。

> This study aims to leverage state of the art language models to automate generating the "Brief Hospital Course" and "Discharge Instructions" sections of Discharge Summaries from the MIMIC-IV dataset, reducing clinicians' administrative workload. We investigate how automation can improve documentation accuracy, alleviate clinician burnout, and enhance operational efficacy in healthcare facilities. This research was conducted within our participation in the Shared Task Discharge Me! at BioNLP @ ACL 2024. Various strategies were employed, including few-shot learning, instruction tuning, and Dynamic Expert Selection (DES), to develop models capable of generating the required text sections. Notably, utilizing an additional clinical domain-specific dataset demonstrated substantial potential to enhance clinical language processing. The DES method, which optimizes the selection of text outputs from multiple predictions, proved to be especially effective. It achieved the highest overall score of 0.332 in the competition, surpassing single-model outputs. This finding suggests that advanced deep learning methods in combination with DES can effectively automate parts of electronic health record documentation. These advancements could enhance patient care by freeing clinician time for patient interactions. The integration of text selection strategies represents a promising avenue for further research.

![WisPerMed 参与“Discharge Me!”项目，通过大型语言模型、动态专家选择及预处理技术，在 MIMIC-IV 数据库上推动医疗文本生成的进步。](../../../paper_images/2405.11255/x1.png)

![WisPerMed 参与“Discharge Me!”项目，通过大型语言模型、动态专家选择及预处理技术，在 MIMIC-IV 数据库上推动医疗文本生成的进步。](../../../paper_images/2405.11255/x2.png)

![WisPerMed 参与“Discharge Me!”项目，通过大型语言模型、动态专家选择及预处理技术，在 MIMIC-IV 数据库上推动医疗文本生成的进步。](../../../paper_images/2405.11255/x3.png)

[Arxiv](https://arxiv.org/abs/2405.11255)