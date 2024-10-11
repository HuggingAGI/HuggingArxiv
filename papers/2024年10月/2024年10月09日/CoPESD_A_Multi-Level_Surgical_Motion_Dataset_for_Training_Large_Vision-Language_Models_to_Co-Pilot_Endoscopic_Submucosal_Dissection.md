# CoPESD：一个多层次手术动作数据集，专为训练大型视觉-语言模型，以协同进行内窥镜黏膜下剥离。

发布时间：2024年10月09日

`LLM应用` `机器人手术`

> CoPESD: A Multi-Level Surgical Motion Dataset for Training Large Vision-Language Models to Co-Pilot Endoscopic Submucosal Dissection

# 摘要

> 黏膜下剥离术（ESD）虽能高效切除大型病变，降低复发率并提升长期生存率，但其技术难度高，并发症风险大，需高超技艺与精准器械。近期，大型视觉语言模型（LVLMs）的突破为机器人系统带来决策支持与预测规划的新希望，有望提升ESD精度，降低手术风险。然而，现有ESD手术动作理解数据集匮乏且标注不足。本文创新性地设计了ESD动作的层次分解，并推出多层次手术动作数据集（CoPESD），旨在训练LVLMs成为ESD手术的机器人“副驾驶”。CoPESD囊括17,679张图像，32,699个边界框及88,395个多层次动作，源自逾35小时的机器人与传统ESD手术视频。该数据集精细剖析ESD动作，聚焦黏膜下剥离的复杂任务。实验证实，CoPESD能有效训练LVLMs预测机器人手术动作。作为首个多模态ESD动作数据集，CoPESD为ESD指令跟随与手术自动化研究开辟新径。数据集现已在https://github.com/gkw0010/CoPESD开放获取。

> submucosal dissection (ESD) enables rapid resection of large lesions, minimizing recurrence rates and improving long-term overall survival. Despite these advantages, ESD is technically challenging and carries high risks of complications, necessitating skilled surgeons and precise instruments. Recent advancements in Large Visual-Language Models (LVLMs) offer promising decision support and predictive planning capabilities for robotic systems, which can augment the accuracy of ESD and reduce procedural risks. However, existing datasets for multi-level fine-grained ESD surgical motion understanding are scarce and lack detailed annotations. In this paper, we design a hierarchical decomposition of ESD motion granularity and introduce a multi-level surgical motion dataset (CoPESD) for training LVLMs as the robotic \textbf{Co}-\textbf{P}ilot of \textbf{E}ndoscopic \textbf{S}ubmucosal \textbf{D}issection. CoPESD includes 17,679 images with 32,699 bounding boxes and 88,395 multi-level motions, from over 35 hours of ESD videos for both robot-assisted and conventional surgeries. CoPESD enables granular analysis of ESD motions, focusing on the complex task of submucosal dissection. Extensive experiments on the LVLMs demonstrate the effectiveness of CoPESD in training LVLMs to predict following surgical robotic motions. As the first multimodal ESD motion dataset, CoPESD supports advanced research in ESD instruction-following and surgical automation. The dataset is available at \href{https://github.com/gkw0010/CoPESD}{https://github.com/gkw0010/CoPESD.}}

[Arxiv](https://arxiv.org/abs/2410.07540)