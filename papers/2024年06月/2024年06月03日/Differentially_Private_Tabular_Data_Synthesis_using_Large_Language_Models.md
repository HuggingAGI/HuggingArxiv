# 利用大型语言模型实现差分隐私下的表格数据合成

发布时间：2024年06月03日

`LLM应用

这篇论文介绍了DP-LLMTGen框架，该框架利用预训练的大型语言模型（LLMs）来生成合成的表格数据，同时确保差分隐私。这种方法通过两阶段微调及特制的损失函数来精确模拟敏感数据，从而生成高质量的合成数据。论文通过实证研究展示了DP-LLMTGen在多个数据集和隐私条件下的优越性能，并通过消融研究和实验分析加深了对LLMs在此领域应用的理解。因此，这篇论文属于LLM应用类别，因为它展示了如何将LLMs应用于特定的实际问题——生成差分隐私的合成表格数据。` `数据隐私` `数据共享`

> Differentially Private Tabular Data Synthesis using Large Language Models

# 摘要

> 在确保形式隐私的前提下，合成表格数据的生成是数据共享的关键。尽管方法研究历史悠久，但创建能产生真实数据的差分隐私表格数据生成器仍是一大挑战。本文推出的DP-LLMTGen框架，巧妙结合预训练大型语言模型（LLMs），通过两阶段微调及特制损失函数，精准模拟敏感数据，进而生成合成数据。实证显示，DP-LLMTGen在多数据集和隐私条件下均优于现有技术。通过消融研究和实验分析，我们对LLMs在此领域的应用有了更深的认识。特别地，DP-LLMTGen在公平性约束下的生成能力展现了其可控性。

> Synthetic tabular data generation with differential privacy is a crucial problem to enable data sharing with formal privacy. Despite a rich history of methodological research and development, developing differentially private tabular data generators that can provide realistic synthetic datasets remains challenging. This paper introduces DP-LLMTGen -- a novel framework for differentially private tabular data synthesis that leverages pretrained large language models (LLMs). DP-LLMTGen models sensitive datasets using a two-stage fine-tuning procedure with a novel loss function specifically designed for tabular data. Subsequently, it generates synthetic data through sampling the fine-tuned LLMs. Our empirical evaluation demonstrates that DP-LLMTGen outperforms a variety of existing mechanisms across multiple datasets and privacy settings. Additionally, we conduct an ablation study and several experimental analyses to deepen our understanding of LLMs in addressing this important problem. Finally, we highlight the controllable generation ability of DP-LLMTGen through a fairness-constrained generation setting.

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x1.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x2.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x3.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x4.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x5.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x6.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x7.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x8.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x9.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x10.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x11.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x12.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x13.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x14.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x15.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x16.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x17.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x18.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x19.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x20.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x21.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x22.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x23.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x24.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x25.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x26.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x27.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x28.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x29.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x30.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x31.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x32.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x33.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x34.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x35.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x36.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x37.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x38.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x39.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x40.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x41.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x42.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x43.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x44.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x45.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x46.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x47.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x48.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x49.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x50.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x51.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x52.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x53.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x54.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x55.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x56.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x57.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x58.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x59.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x60.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x61.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x62.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x63.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x64.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x65.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x66.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x67.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x68.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x69.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x70.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x71.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x72.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x73.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x74.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x75.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x76.png)

![利用大型语言模型实现差分隐私下的表格数据合成](../../../paper_images/2406.01457/x77.png)

[Arxiv](https://arxiv.org/abs/2406.01457)