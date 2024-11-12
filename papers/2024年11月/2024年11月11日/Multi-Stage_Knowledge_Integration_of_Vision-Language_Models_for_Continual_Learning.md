# 多阶段的视觉语言模型知识集成用于持续学习

发布时间：2024年11月11日

`LLM应用` `计算机视觉` `持续学习`

> Multi-Stage Knowledge Integration of Vision-Language Models for Continual Learning

# 摘要

> 视觉语言模型（VLMs）在大规模图像-文本数据集上进行了预训练，能够对未见过的数据进行零样本预测，但在特定的未见过的任务中可能表现不佳。持续学习（CL）可以帮助 VLMs 有效地适应新的数据分布，而无需联合训练，但面临着灾难性遗忘和泛化遗忘的挑战。尽管基于蒸馏的方法取得了显著进展，但它们表现出两个严重的局限性。一是广泛采用的单教师范式无法传授全面的知识，二是现有方法没有充分利用原始训练数据集中的多模态信息，而是依赖于额外的数据进行蒸馏，这增加了计算和存储开销。为了减轻这两个限制，借鉴知识集成理论（KIT），我们提出了一个多阶段知识集成网络（MulKI），以在蒸馏方法中模拟人类的学习过程。MulKI 通过四个阶段来实现这一点，包括引发想法、添加新想法、区分想法和建立联系。在这四个阶段中，我们首先利用原型来跨模态对齐，引发跨模态知识，然后通过与原型构建细粒度的模态内和模态间关系来添加新知识。之后，自适应地区分和重新加权来自两个教师模型的知识。最后，我们在任务内和任务间的模型之间建立联系，整合先前的和新的知识。我们的方法在保持零样本能力的同时，在支持不同下游任务的持续学习方面显示出显著的改进，展示了其在使 VLMs 适应不断变化的数据分布方面的潜力。

> Vision Language Models (VLMs), pre-trained on large-scale image-text datasets, enable zero-shot predictions for unseen data but may underperform on specific unseen tasks. Continual learning (CL) can help VLMs effectively adapt to new data distributions without joint training, but faces challenges of catastrophic forgetting and generalization forgetting. Although significant progress has been achieved by distillation-based methods, they exhibit two severe limitations. One is the popularly adopted single-teacher paradigm fails to impart comprehensive knowledge, The other is the existing methods inadequately leverage the multimodal information in the original training dataset, instead they rely on additional data for distillation, which increases computational and storage overhead. To mitigate both limitations, by drawing on Knowledge Integration Theory (KIT), we propose a Multi-Stage Knowledge Integration network (MulKI) to emulate the human learning process in distillation methods. MulKI achieves this through four stages, including Eliciting Ideas, Adding New Ideas, Distinguishing Ideas, and Making Connections. During the four stages, we first leverage prototypes to align across modalities, eliciting cross-modal knowledge, then adding new knowledge by constructing fine-grained intra- and inter-modality relationships with prototypes. After that, knowledge from two teacher models is adaptively distinguished and re-weighted. Finally, we connect between models from intra- and inter-task, integrating preceding and new knowledge. Our method demonstrates significant improvements in maintaining zero-shot capabilities while supporting continual learning across diverse downstream tasks, showcasing its potential in adapting VLMs to evolving data distributions.

[Arxiv](https://arxiv.org/abs/2411.06764)