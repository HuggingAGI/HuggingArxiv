# GLaD：融合分子图与语言描述，提升有机光伏设备功率转换效率预测精度

发布时间：2024年05月23日

`LLM应用

这篇论文介绍了一种名为GLaD的方法，它利用大型语言模型（LLM）的预训练成果来提升有机光伏器件的功率转换效率预测。这种方法通过融合分子图与语言描述符，实现了分子属性的多模态预测。论文中提到的应用场景包括化学领域的数据稀缺环境，以及药物和材料发现等科学探索中的数据依赖决策和化学空间探索。因此，这篇论文属于LLM应用类别，因为它展示了LLM在特定科学问题上的实际应用和效果。` `有机光伏` `药物发现`

> GLaD: Synergizing Molecular Graphs and Language Descriptors for Enhanced Power Conversion Efficiency Prediction in Organic Photovoltaic Devices

# 摘要

> 本文介绍了一种创新方法GLaD，旨在通过融合分子图与语言描述符来提升有机光伏器件的功率转换效率预测。面对高质量实验数据的匮乏，我们构建了一个包含500对OPV分子及其PCE值的数据集，以此训练我们的预测模型。在数据稀缺的情境下，GLaD巧妙地利用了大型语言模型在科学文献上的预训练成果，丰富了分子结构的表示，实现了分子属性的多模态预测。GLaD不仅精准预测了PCE，助力了高效OPV分子的合成，还展现了其广泛适用性，涵盖了BBBP、BACE、ClinTox和SIDER等多个分子属性预测领域。尤其在化学领域的数据稀缺环境中，GLaD通过整合大规模预训练获得的分子属性描述，显著提升了分子表示的丰富性，这对于药物和材料发现等科学探索中的数据依赖决策和化学空间探索具有重大意义。

> This paper presents a novel approach for predicting Power Conversion Efficiency (PCE) of Organic Photovoltaic (OPV) devices, called GLaD: synergizing molecular Graphs and Language Descriptors for enhanced PCE prediction. Due to the lack of high-quality experimental data, we collect a dataset consisting of 500 pairs of OPV donor and acceptor molecules along with their corresponding PCE values, which we utilize as the training data for our predictive model. In this low-data regime, GLaD leverages properties learned from large language models (LLMs) pretrained on extensive scientific literature to enrich molecular structural representations, allowing for a multimodal representation of molecules. GLaD achieves precise predictions of PCE, thereby facilitating the synthesis of new OPV molecules with improved efficiency. Furthermore, GLaD showcases versatility, as it applies to a range of molecular property prediction tasks (BBBP, BACE, ClinTox, and SIDER), not limited to those concerning OPV materials. Especially, GLaD proves valuable for tasks in low-data regimes within the chemical space, as it enriches molecular representations by incorporating molecular property descriptions learned from large-scale pretraining. This capability is significant in real-world scientific endeavors like drug and material discovery, where access to comprehensive data is crucial for informed decision-making and efficient exploration of the chemical space.

[Arxiv](https://arxiv.org/abs/2405.14203)