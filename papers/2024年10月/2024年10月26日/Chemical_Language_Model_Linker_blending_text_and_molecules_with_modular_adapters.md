# 化学语言模型连接器：借助模块化适配器实现文本与分子的融合

发布时间：2024年10月26日

`LLM应用`

> Chemical Language Model Linker: blending text and molecules with modular adapters

# 摘要

> 大型语言模型和多模态模型的发展，让从文本描述生成新分子这一极具吸引力的构想得以实现。生成式建模会将模式从依赖大规模化学筛选来寻觅具有所需特性的分子，转变为直接生成此类分子。然而，将文本和分子相结合的多模态模型往往是从零开始训练的，未利用现有的优质预训练模型。这种方式耗费更多计算资源，还限制了模型的扩展。相较而言，我们提出了一种名为化学语言模型连接器（ChemLML）的基于轻量级适配器的策略。ChemLML 融合了两个单一领域的模型，能从文本描述中获取条件分子生成，且仍在分子领域的专门嵌入空间中运作。ChemLML 能够通过训练相对较少的适配器参数，为分子生成定制各类预训练的文本模型。我们发现，在 ChemLML 中选用的分子表示方式，即 SMILES 和 SELFIES，对条件分子生成性能影响显著。尽管 SMILES 无法保证分子的有效性，但通常更受青睐。我们指出了在使用大型 PubChem 分子数据集及其相关描述来评估分子生成时存在的问题，并提供了该数据集的过滤版本作为生成测试集。为展示 ChemLML 在实际中的运用，我们生成了候选蛋白质抑制剂，并通过对接来评估其质量。

> The development of large language models and multi-modal models has enabled the appealing idea of generating novel molecules from text descriptions. Generative modeling would shift the paradigm from relying on large-scale chemical screening to find molecules with desired properties to directly generating those molecules. However, multi-modal models combining text and molecules are often trained from scratch, without leveraging existing high-quality pretrained models. That approach consumes more computational resources and prohibits model scaling. In contrast, we propose a lightweight adapter-based strategy named Chemical Language Model Linker (ChemLML). ChemLML blends the two single domain models and obtains conditional molecular generation from text descriptions while still operating in the specialized embedding spaces of the molecular domain. ChemLML can tailor diverse pretrained text models for molecule generation by training relatively few adapter parameters. We find that the choice of molecular representation used within ChemLML, SMILES versus SELFIES, has a strong influence on conditional molecular generation performance. SMILES is often preferable despite not guaranteeing valid molecules. We raise issues in using the large PubChem dataset of molecules and their associated descriptions for evaluating molecule generation and provide a filtered version of the dataset as a generation test set. To demonstrate how ChemLML could be used in practice, we generate candidate protein inhibitors and use docking to assess their quality.

[Arxiv](https://arxiv.org/abs/2410.20182)