# RAMIE：利用大型语言模型针对膳食补充剂的检索增强型多任务信息提取

发布时间：2024年11月23日

`LLM应用` `膳食补充剂`

> RAMIE: Retrieval-Augmented Multi-task Information Extraction with Large Language Models on Dietary Supplements

# 摘要

> 	extbf{目标:} 我们致力于开发一个先进的多任务大型语言模型（LLM）框架，以便从临床记录中提取有关膳食补充剂（DS）的多种类型信息。
  	extbf{方法:} 我们将四个核心的 DS 信息提取任务，即命名实体识别（NER：2949 个临床句子）、关系提取（RE：4892 个句子）、三元组提取（TE：2949 个句子）和使用分类（UC：2460 个句子）设定为多任务。我们引入了新颖的检索增强多任务信息提取（RAMIE）框架，具体包括：1. 运用带有特定任务提示的指令微调技术；2. 训练用于多任务的 LLM，提升存储效率并降低训练成本；3. 通过从训练集中检索类似示例融入检索增强生成（RAG）技术。我们对比了 RAMIE 与仅进行指令微调的 LLM 的性能，并开展了消融研究，以评估多任务学习和 RAG 对提升多任务性能的贡献。
  	extbf{结果:} 在 RAMIE 框架助力下，Llama2-13B 在 NER 任务上取得了 87.39 的 F1 分数（提升 3.51%），在 RE 任务上表现卓越，F1 分数达 93.74（提升 1.15%）。对于 TE 任务，Llama2-7B 得分 79.45（提升 14.26%），MedAlpaca-7B 在 UC 任务上获得最高 F1 分数 93.45（提升 0.94%）。消融研究显示，虽然多任务学习（MTL）在性能上稍有折衷地提高了效率，但 RAG 显著提升了整体准确性。
  	extbf{结论:} 本研究呈现了一个新颖的 RAMIE 框架，在从临床记录中提取与 DS 相关数据的多任务信息提取方面有显著改进。我们的框架有望应用于其他领域。

> \textbf{Objective:} We aimed to develop an advanced multi-task large language model (LLM) framework to extract multiple types of information about dietary supplements (DS) from clinical records.
  \textbf{Methods:} We used four core DS information extraction tasks - namely, named entity recognition (NER: 2,949 clinical sentences), relation extraction (RE: 4,892 sentences), triple extraction (TE: 2,949 sentences), and usage classification (UC: 2,460 sentences) as our multitasks. We introduced a novel Retrieval-Augmented Multi-task Information Extraction (RAMIE) Framework, including: 1) employed instruction fine-tuning techniques with task-specific prompts, 2) trained LLMs for multiple tasks with improved storage efficiency and lower training costs, and 3) incorporated retrieval augmentation generation (RAG) techniques by retrieving similar examples from the training set. We compared RAMIE's performance to LLMs with instruction fine-tuning alone and conducted an ablation study to assess the contributions of multi-task learning and RAG to improved multitasking performance.
  \textbf{Results:} With the aid of the RAMIE framework, Llama2-13B achieved an F1 score of 87.39 (3.51\% improvement) on the NER task and demonstrated outstanding performance on the RE task with an F1 score of 93.74 (1.15\% improvement). For the TE task, Llama2-7B scored 79.45 (14.26\% improvement), and MedAlpaca-7B achieved the highest F1 score of 93.45 (0.94\% improvement) on the UC task. The ablation study revealed that while MTL increased efficiency with a slight trade-off in performance, RAG significantly boosted overall accuracy.
  \textbf{Conclusion:} This study presents a novel RAMIE framework that demonstrates substantial improvements in multi-task information extraction for DS-related data from clinical records. Our framework can potentially be applied to other domains.

[Arxiv](https://arxiv.org/abs/2411.15700)