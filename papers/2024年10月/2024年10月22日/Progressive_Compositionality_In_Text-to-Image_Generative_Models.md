# 文本到图像生成模型中的渐进组合性

发布时间：2024年10月22日

`LLM应用` `图像合成` `视觉问答`

> Progressive Compositionality In Text-to-Image Generative Models

# 摘要

> 尽管扩散模型具有令人印象深刻的文本到图像（T2I）合成能力，但它们往往难以理解对象和属性之间的组合关系，特别是在复杂的环境中。现有的解决方案通过优化交叉注意力机制或从语义变化最小的标题对中学习来应对这些挑战。然而，我们能否生成扩散模型可以直接根据视觉表示进行区分的高质量复杂对比图像？在这项工作中，我们利用大型语言模型（LLMs）来构建逼真、复杂的场景，并利用视觉问答（VQA）系统和扩散模型自动策划一个对比数据集 ConPair，其中包含 15000 对高质量的对比图像。这些对具有最小的视觉差异，并涵盖了广泛的属性类别，特别是复杂和自然的场景。为了从这些错误案例（即硬负图像）中有效地学习，我们提出了 EvoGen，这是一种用于扩散模型对比学习的新的多阶段课程。通过在广泛的组合场景中进行大量实验，我们展示了我们提出的框架在组合 T2I 基准测试中的有效性。

> Despite the impressive text-to-image (T2I) synthesis capabilities of diffusion models, they often struggle to understand compositional relationships between objects and attributes, especially in complex settings. Existing solutions have tackled these challenges by optimizing the cross-attention mechanism or learning from the caption pairs with minimal semantic changes. However, can we generate high-quality complex contrastive images that diffusion models can directly discriminate based on visual representations? In this work, we leverage large-language models (LLMs) to compose realistic, complex scenarios and harness Visual-Question Answering (VQA) systems alongside diffusion models to automatically curate a contrastive dataset, ConPair, consisting of 15k pairs of high-quality contrastive images. These pairs feature minimal visual discrepancies and cover a wide range of attribute categories, especially complex and natural scenarios. To learn effectively from these error cases, i.e., hard negative images, we propose EvoGen, a new multi-stage curriculum for contrastive learning of diffusion models. Through extensive experiments across a wide range of compositional scenarios, we showcase the effectiveness of our proposed framework on compositional T2I benchmarks.

[Arxiv](https://arxiv.org/abs/2410.16719)