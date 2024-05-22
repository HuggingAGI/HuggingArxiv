# DrHouse：结合传感器数据与专家知识，由LLM驱动的智能诊断推理系统

发布时间：2024年05月21日

`LLM应用

这篇论文摘要描述了一个基于大型语言模型（LLMs）的系统DrHouse，该系统利用智能设备传感器数据和实时更新的医学数据库来提高诊断的准确性。这个系统通过算法评估多种疾病可能性，并通过多轮对话优化诊断。这与LLM的应用紧密相关，特别是在医疗领域的应用，因此将其归类为LLM应用。` `智能设备`

> DrHouse: An LLM-empowered Diagnostic Reasoning System through Harnessing Outcomes from Sensor Data and Expert Knowledge

# 摘要

> 大型语言模型（LLMs）正推动数字医疗的革新，尤其是基于LLM的虚拟医生技术。然而，现有方法因依赖患者主观描述而误诊频发。我们开发的DrHouse系统，利用智能设备传感器数据，结合实时更新的医学数据库，如UpToDate和PubMed，确保诊断始终精准前沿。DrHouse还创新性地采用算法，同时评估多种疾病可能性，通过多轮对话，逐步优化诊断，并根据需要调用智能设备数据或实验室测试。测试显示，DrHouse的诊断准确率较现有技术提升了18.8%。用户研究中，75%的医学专家和91.7%的患者表示愿意采用DrHouse。

> Large language models (LLMs) have the potential to transform digital healthcare, as evidenced by recent advances in LLM-based virtual doctors. However, current approaches rely on patient's subjective descriptions of symptoms, causing increased misdiagnosis. Recognizing the value of daily data from smart devices, we introduce a novel LLM-based multi-turn consultation virtual doctor system, DrHouse, which incorporates three significant contributions: 1) It utilizes sensor data from smart devices in the diagnosis process, enhancing accuracy and reliability. 2) DrHouse leverages continuously updating medical databases such as Up-to-Date and PubMed to ensure our model remains at diagnostic standard's forefront. 3) DrHouse introduces a novel diagnostic algorithm that concurrently evaluates potential diseases and their likelihood, facilitating more nuanced and informed medical assessments. Through multi-turn interactions, DrHouse determines the next steps, such as accessing daily data from smart devices or requesting in-lab tests, and progressively refines its diagnoses. Evaluations on three public datasets and our self-collected datasets show that DrHouse can achieve up to an 18.8% increase in diagnosis accuracy over the state-of-the-art baselines. The results of a 32-participant user study show that 75% medical experts and 91.7% patients are willing to use DrHouse.

[Arxiv](https://arxiv.org/abs/2405.12541)