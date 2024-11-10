# NeurIPS 2023 竞赛：保护隐私的联邦学习文档 VQA

发布时间：2024年11月06日

`LLM应用` `联邦学习` `发票处理`

> NeurIPS 2023 Competition: Privacy Preserving Federated Learning Document VQA

# 摘要

> 隐私保护联邦学习文档视觉问答（PFL-DocVQA）竞赛向社区发起挑战，要求在联邦环境中为现实生活中的用例——发票处理，开发可证明为隐私且通信高效的解决方案。该竞赛引入了真实发票文档的数据集，以及相关的问题和答案，需要对文档图像进行信息提取和推理。因此，它汇集了来自文档分析、隐私和联邦学习社区的研究人员和专业知识。参与者为这个新领域对组织者提供的预先训练的、最先进的文档视觉问答模型进行微调，模仿典型的联邦发票处理设置。基础模型是一个多模态生成语言模型，敏感信息可能通过视觉或文本输入模式暴露。参与者在第 1 赛道提出了优雅的解决方案，以降低通信成本，同时保持最低效用阈值；在第 2 赛道使用差分隐私保护每个文档提供者的所有信息。该竞赛成为开发和测试私有联邦学习方法的新试验台，同时提高了文档图像分析和识别社区内对隐私的认识。最终，竞赛分析为未来成功开展以隐私为重点的联邦学习挑战提供了最佳实践和建议。

> The Privacy Preserving Federated Learning Document VQA (PFL-DocVQA) competition challenged the community to develop provably private and communication-efficient solutions in a federated setting for a real-life use case: invoice processing. The competition introduced a dataset of real invoice documents, along with associated questions and answers requiring information extraction and reasoning over the document images. Thereby, it brings together researchers and expertise from the document analysis, privacy, and federated learning communities. Participants fine-tuned a pre-trained, state-of-the-art Document Visual Question Answering model provided by the organizers for this new domain, mimicking a typical federated invoice processing setup. The base model is a multi-modal generative language model, and sensitive information could be exposed through either the visual or textual input modality. Participants proposed elegant solutions to reduce communication costs while maintaining a minimum utility threshold in track 1 and to protect all information from each document provider using differential privacy in track 2. The competition served as a new testbed for developing and testing private federated learning methods, simultaneously raising awareness about privacy within the document image analysis and recognition community. Ultimately, the competition analysis provides best practices and recommendations for successfully running privacy-focused federated learning challenges in the future.

[Arxiv](https://arxiv.org/abs/2411.03730)