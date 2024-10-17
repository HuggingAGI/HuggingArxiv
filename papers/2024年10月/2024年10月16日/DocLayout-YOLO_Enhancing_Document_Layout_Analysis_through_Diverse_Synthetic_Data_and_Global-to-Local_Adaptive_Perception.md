# DocLayout-YOLO：利用多样化合成数据和全局到局部的自适应感知，提升文档布局分析能力

发布时间：2024年10月16日

`其他` `文档处理` `计算机视觉`

> DocLayout-YOLO: Enhancing Document Layout Analysis through Diverse Synthetic Data and Global-to-Local Adaptive Perception

# 摘要

> 文档布局分析在实际应用中至关重要，但速度与准确性往往难以兼顾。多模态方法虽提高准确性，却牺牲了速度；单模态方法则反之。为此，我们推出了DocLayout-YOLO，通过文档特化的预训练与模型设计，实现了速度与准确性的双赢。我们创新的Mesh-candidate BestFit算法，将文档合成视为二维装箱问题，生成了DocSynth-300K数据集，大幅提升了微调效果。模型优化方面，我们设计了全局到局部的可控感受野模块，有效应对多尺度文档元素。为全面评估性能，我们创建了DocStructBench基准测试。实验证明，DocLayout-YOLO在速度与准确性上均表现卓越。相关资源已开放，详见https://github.com/opendatalab/DocLayout-YOLO。

> Document Layout Analysis is crucial for real-world document understanding systems, but it encounters a challenging trade-off between speed and accuracy: multimodal methods leveraging both text and visual features achieve higher accuracy but suffer from significant latency, whereas unimodal methods relying solely on visual features offer faster processing speeds at the expense of accuracy. To address this dilemma, we introduce DocLayout-YOLO, a novel approach that enhances accuracy while maintaining speed advantages through document-specific optimizations in both pre-training and model design. For robust document pre-training, we introduce the Mesh-candidate BestFit algorithm, which frames document synthesis as a two-dimensional bin packing problem, generating the large-scale, diverse DocSynth-300K dataset. Pre-training on the resulting DocSynth-300K dataset significantly improves fine-tuning performance across various document types. In terms of model optimization, we propose a Global-to-Local Controllable Receptive Module that is capable of better handling multi-scale variations of document elements. Furthermore, to validate performance across different document types, we introduce a complex and challenging benchmark named DocStructBench. Extensive experiments on downstream datasets demonstrate that DocLayout-YOLO excels in both speed and accuracy. Code, data, and models are available at https://github.com/opendatalab/DocLayout-YOLO.

[Arxiv](https://arxiv.org/abs/2410.12628)