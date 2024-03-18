# FakeNewsGPT4 是一项创新研究，利用了知识增强的多模态大型语言模型，旨在提升假新闻检测能力。

发布时间：2024年03月04日

`Agent`

> FakeNewsGPT4: Advancing Multimodal Fake News Detection through Knowledge-Augmented LVLMs

> 如今，大规模涌现的多模态假新闻显示出巨大的分布差异，亟需构建能够广泛适用的检测系统。但传统的检测器由于局限于特定领域的训练，往往难以把握开放世界的事实真相。为此，我们创新提出了 FakeNewsGPT4 框架，它巧妙地向大型视觉语言模型（LVLMs）注入针对伪造内容的特定知识，并同时整合丰富全面的世界知识。在这个框架中，知识增强过程涉及获取两类伪造特有信息——语义关联性和痕迹特征，并将其深度融合到 LVLMs 内部。具体来说，我们精心设计了一种多层次跨模态推理机制，实现对不同模态间语义关联的有效捕捉；同时推出一款双通道细粒度验证模块，精准解析局部细节以编码痕迹特征。这些生成的知识随后转化成与 LVLMs 完美兼容的精炼嵌入表示。此外，我们还运用了候选答案启发策略和软提示技术，进一步提升输入信息的质量。经过在公开基准数据集上的广泛实验证明，FakeNewsGPT4 在跨领域检测性能上超越了以往所有方法，相关代码即将开源发布。

> The massive generation of multimodal fake news exhibits substantial distribution discrepancies, prompting the need for generalized detectors. However, the insulated nature of training within specific domains restricts the capability of classical detectors to obtain open-world facts. In this paper, we propose FakeNewsGPT4, a novel framework that augments Large Vision-Language Models (LVLMs) with forgery-specific knowledge for manipulation reasoning while inheriting extensive world knowledge as complementary. Knowledge augmentation in FakeNewsGPT4 involves acquiring two types of forgery-specific knowledge, i.e., semantic correlation and artifact trace, and merging them into LVLMs. Specifically, we design a multi-level cross-modal reasoning module that establishes interactions across modalities for extracting semantic correlations. Concurrently, a dual-branch fine-grained verification module is presented to comprehend localized details to encode artifact traces. The generated knowledge is translated into refined embeddings compatible with LVLMs. We also incorporate candidate answer heuristics and soft prompts to enhance input informativeness. Extensive experiments on the public benchmark demonstrate that FakeNewsGPT4 achieves superior cross-domain performance compared to previous methods. Code will be available.

[Arxiv](https://arxiv.org/abs/2403.01988)