# 开发用于预测材料失效的基础模型

发布时间：2024年11月13日

`LLM应用` `材料科学` `失效预测`

> Developing a Foundation Model for Predicting Material Failure

# 摘要

> 理解材料失效对于通过识别可减轻的弱点来设计更坚固和更轻的结构至关重要。现有的全物理数值模拟技术在速度、准确性和处理诸如变化的边界条件、网格类型、分辨率和物理模型等复杂特征的能力之间存在权衡。我们提出了第一个专门用于预测材料失效的基础模型，利用大规模数据集和高参数数量（高达 30 亿）显著提高了失效预测的准确性。此外，大型语言模型提供了丰富的上下文嵌入，使我们的模型能够在各种条件下进行预测。与传统的机器学习模型不同，传统机器学习模型通常针对特定系统量身定制或限于狭窄的模拟条件，我们的基础模型旨在跨不同材料和模拟器进行泛化。这种灵活性使模型能够处理一系列材料特性和条件，提供准确的预测，而无需针对每个具体情况进行重新训练或调整。我们的模型能够适应各种输入格式，例如图像和不同的模拟条件，并产生从模拟结果到有效属性的一系列输出。它支持笛卡尔和非结构化网格，其设计选择允许随着新数据和要求的出现进行无缝更新和扩展。我们的结果表明，模型规模的增加会带来显著的性能提升（损失规模为$N^{-1.6}$，而语言模型通常为$N^{-0.5}$）。

> Understanding material failure is critical for designing stronger and lighter structures by identifying weaknesses that could be mitigated. Existing full-physics numerical simulation techniques involve trade-offs between speed, accuracy, and the ability to handle complex features like varying boundary conditions, grid types, resolution, and physical models. We present the first foundation model specifically designed for predicting material failure, leveraging large-scale datasets and a high parameter count (up to 3B) to significantly improve the accuracy of failure predictions. In addition, a large language model provides rich context embeddings, enabling our model to make predictions across a diverse range of conditions. Unlike traditional machine learning models, which are often tailored to specific systems or limited to narrow simulation conditions, our foundation model is designed to generalize across different materials and simulators. This flexibility enables the model to handle a range of material properties and conditions, providing accurate predictions without the need for retraining or adjustments for each specific case. Our model is capable of accommodating diverse input formats, such as images and varying simulation conditions, and producing a range of outputs, from simulation results to effective properties. It supports both Cartesian and unstructured grids, with design choices that allow for seamless updates and extensions as new data and requirements emerge. Our results show that increasing the scale of the model leads to significant performance gains (loss scales as $N^{-1.6}$, compared to language models which often scale as $N^{-0.5}$).

[Arxiv](https://arxiv.org/abs/2411.08354)