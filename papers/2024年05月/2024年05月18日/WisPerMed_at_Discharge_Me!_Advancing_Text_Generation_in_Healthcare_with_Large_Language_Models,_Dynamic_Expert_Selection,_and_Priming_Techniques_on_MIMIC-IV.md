# WisPerMed 在“出院吧！”项目中，通过大型语言模型、动态专家选择及预处理技术，在 MIMIC-IV 数据集上推动了医疗文本生成的进步。

发布时间：2024年05月18日

`LLM应用

这篇论文的研究重点是利用先进的语言模型（LLM）自动化生成医疗记录中的特定部分，即MIMIC-IV数据集的出院总结中的“简要住院过程”与“出院指导”。研究的目标是减轻临床医生的行政负担，提高文档准确性，缓解临床疲劳，并增强医疗运营效率。该研究采用了少量样本学习、指令调整及动态专家选择（DES）等策略，并在2024年BioNLP @ ACL的“Shared Task Discharge Me!”中进行了验证。研究结果显示，结合DES的高级深度学习方法能够有效自动化电子健康记录的部分内容，从而提升患者护理质量。因此，这篇论文属于LLM应用类别，因为它展示了如何将LLM技术应用于实际的医疗文档自动化任务中。`

> WisPerMed at "Discharge Me!": Advancing Text Generation in Healthcare with Large Language Models, Dynamic Expert Selection, and Priming Techniques on MIMIC-IV

# 摘要

> 本研究利用尖端语言模型，旨在自动化生成MIMIC-IV数据集出院总结中的“简要住院过程”与“出院指导”，从而减轻临床医生的行政负担。我们探讨了自动化如何提升文档准确性、缓解临床疲劳并增强医疗运营效率。此研究在我们参与2024年BioNLP @ ACL的“Shared Task Discharge Me!”中进行，采用了少量样本学习、指令调整及动态专家选择（DES）等策略，开发出能生成所需文本的模型。特别地，利用额外的临床领域数据集极大地增强了临床语言处理能力。DES方法，通过优化多预测文本输出选择，表现尤为出色，在比赛中以0.332的高分领先，超越了单一模型。这表明，结合DES的高级深度学习方法能有效自动化电子健康记录的部分内容，通过释放临床时间，提升患者护理质量。文本选择策略的整合为未来研究开辟了新途径。

> This study aims to leverage state of the art language models to automate generating the "Brief Hospital Course" and "Discharge Instructions" sections of Discharge Summaries from the MIMIC-IV dataset, reducing clinicians' administrative workload. We investigate how automation can improve documentation accuracy, alleviate clinician burnout, and enhance operational efficacy in healthcare facilities. This research was conducted within our participation in the Shared Task Discharge Me! at BioNLP @ ACL 2024. Various strategies were employed, including few-shot learning, instruction tuning, and Dynamic Expert Selection (DES), to develop models capable of generating the required text sections. Notably, utilizing an additional clinical domain-specific dataset demonstrated substantial potential to enhance clinical language processing. The DES method, which optimizes the selection of text outputs from multiple predictions, proved to be especially effective. It achieved the highest overall score of 0.332 in the competition, surpassing single-model outputs. This finding suggests that advanced deep learning methods in combination with DES can effectively automate parts of electronic health record documentation. These advancements could enhance patient care by freeing clinician time for patient interactions. The integration of text selection strategies represents a promising avenue for further research.

![WisPerMed 在“出院吧！”项目中，通过大型语言模型、动态专家选择及预处理技术，在 MIMIC-IV 数据集上推动了医疗文本生成的进步。](../../../paper_images/2405.11255/x1.png)

![WisPerMed 在“出院吧！”项目中，通过大型语言模型、动态专家选择及预处理技术，在 MIMIC-IV 数据集上推动了医疗文本生成的进步。](../../../paper_images/2405.11255/x2.png)

![WisPerMed 在“出院吧！”项目中，通过大型语言模型、动态专家选择及预处理技术，在 MIMIC-IV 数据集上推动了医疗文本生成的进步。](../../../paper_images/2405.11255/x3.png)

[Arxiv](https://arxiv.org/abs/2405.11255)