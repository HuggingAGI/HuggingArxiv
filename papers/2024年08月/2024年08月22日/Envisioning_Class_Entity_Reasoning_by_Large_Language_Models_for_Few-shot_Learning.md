# 设想大型语言模型在少样本学习中进行类实体推理

发布时间：2024年08月22日

`LLM应用` `计算机视觉` `机器学习`

> Envisioning Class Entity Reasoning by Large Language Models for Few-shot Learning

# 摘要

> 少样本学习 (FSL) 旨在通过少量视觉样本识别新概念。现有方法尝试将语义信息融入视觉数据以理解类别，但往往依赖抽象类别名称，未能捕捉到关键的细微特征。为此，我们提出了一种新框架，结合大型语言模型 (LLM) 中的抽象语义和具体实体，以强化类别原型。该框架包含语义引导的视觉模式提取 (SVPE) 和原型校准 (PC) 模块，前者提取多尺度语义感知模式，后者整合这些模式以精炼原型，提升其代表性。实验表明，在多个基准测试中，我们的方法显著超越现有技术，特别是在一次性设置中，使用 ResNet-12 主干，平均提升达 1.95%。

> Few-shot learning (FSL) aims to recognize new concepts using a limited number of visual samples. Existing approaches attempt to incorporate semantic information into the limited visual data for category understanding. However, these methods often enrich class-level feature representations with abstract category names, failing to capture the nuanced features essential for effective generalization. To address this issue, we propose a novel framework for FSL, which incorporates both the abstract class semantics and the concrete class entities extracted from Large Language Models (LLMs), to enhance the representation of the class prototypes. Specifically, our framework composes a Semantic-guided Visual Pattern Extraction (SVPE) module and a Prototype-Calibration (PC) module, where the SVPE meticulously extracts semantic-aware visual patterns across diverse scales, while the PC module seamlessly integrates these patterns to refine the visual prototype, enhancing its representativeness. Extensive experiments on four few-shot classification benchmarks and the BSCD-FSL cross-domain benchmarks showcase remarkable advancements over the current state-of-the-art methods. Notably, for the challenging one-shot setting, our approach, utilizing the ResNet-12 backbone, achieves an impressive average improvement of 1.95% over the second-best competitor.

[Arxiv](https://arxiv.org/abs/2408.12469)