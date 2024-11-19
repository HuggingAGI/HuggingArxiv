# 从临床笔记中进行信息提取：我们是否已准备好切换至大型语言模型？

发布时间：2024年11月15日

`LLM应用`

> Information Extraction from Clinical Notes: Are We Ready to Switch to Large Language Models?

# 摘要

> 背景：信息提取（IE）在临床自然语言处理（NLP）中极为关键。尽管大型语言模型（LLMs）在生成任务中表现卓越，但在抽取任务上的表现却饱受争议。方法：我们借助来自四个来源（UT 医师、MTSamples、MIMIC-III 以及 i2b2）的 1588 份临床记录，对命名实体识别（NER）和关系提取（RE）展开了研究。我们构建了一个涵盖 4 个临床实体和 16 个修饰符的标注语料库，并从性能、泛化能力、计算资源和吞吐量等方面，将经过指令调整的 LLaMA-2 和 LLaMA-3 与 BiomedBERT 进行了对比。结果：LLaMA 模型在各个数据集上的表现均优于 BiomedBERT。拥有充足训练数据时，LLaMA 有一定程度的提升（NER 提升 1%，RE 提升 1.5 - 3.7%）；训练数据有限时，提升幅度更大。在未曾见过的 i2b2 数据上，LLaMA-3-70B 在 NER 上的表现比 BiomedBERT 高出 7%（F1），在 RE 上高出 4%。然而，LLaMA 模型需要更多计算资源，运行速度慢达 28 倍。我们实现了“Kiwi”，这是一款包含上述两个模型的临床 IE 软件包，可在 https://kiwi.clinicalnlp.org/ 获取。结论：本研究属于首批运用开源 LLMs 开发并评估综合性临床 IE 系统的研究。结果显示，LLaMA 模型在临床 NER 和 RE 方面优于 BiomedBERT，但计算成本更高，吞吐量更低。这些发现表明，在临床 IE 应用中选择 LLMs 还是传统深度学习方法，应视具体任务而定，同时要兼顾性能指标以及诸如可用计算资源和预期用例场景等实际因素。

> Backgrounds: Information extraction (IE) is critical in clinical natural language processing (NLP). While large language models (LLMs) excel on generative tasks, their performance on extractive tasks remains debated. Methods: We investigated Named Entity Recognition (NER) and Relation Extraction (RE) using 1,588 clinical notes from four sources (UT Physicians, MTSamples, MIMIC-III, and i2b2). We developed an annotated corpus covering 4 clinical entities and 16 modifiers, and compared instruction-tuned LLaMA-2 and LLaMA-3 against BiomedBERT in terms of performance, generalizability, computational resources, and throughput to BiomedBERT. Results: LLaMA models outperformed BiomedBERT across datasets. With sufficient training data, LLaMA showed modest improvements (1% on NER, 1.5-3.7% on RE); improvements were larger with limited training data. On unseen i2b2 data, LLaMA-3-70B outperformed BiomedBERT by 7% (F1) on NER and 4% on RE. However, LLaMA models required more computing resources and ran up to 28 times slower. We implemented "Kiwi," a clinical IE package featuring both models, available at https://kiwi.clinicalnlp.org/. Conclusion: This study is among the first to develop and evaluate a comprehensive clinical IE system using open-source LLMs. Results indicate that LLaMA models outperform BiomedBERT for clinical NER and RE but with higher computational costs and lower throughputs. These findings highlight that choosing between LLMs and traditional deep learning methods for clinical IE applications should remain task-specific, taking into account both performance metrics and practical considerations such as available computing resources and the intended use case scenarios.

[Arxiv](https://arxiv.org/abs/2411.10020)