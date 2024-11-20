# 探索用于文本-分子检索的基于最优传输的多粒度对齐方式

发布时间：2024年11月04日

`其他` `生物信息学` `跨模态检索`

> Exploring Optimal Transport-Based Multi-Grained Alignments for Text-Molecule Retrieval

# 摘要

> 在生物信息学领域，进展显著，这让跨模态文本-分子检索任务愈发关键。此任务旨在依据文本描述精确检索分子结构，通过有效对齐文本描述与分子，助力研究人员找到合适的分子候选。然而，众多现有方法都忽视了分子子结构中的固有细节。在本研究中，我们推出了基于最优传输的多粒度对齐模型（ORMA），这是一种推动文本描述和分子实现多粒度对齐的新方法。我们的模型包含文本编码器和分子编码器。文本编码器处理文本描述，生成标记级和句子级的表征，而分子被构建为分层异构图，涵盖原子、基序和分子节点，以提取这三个层面的表征。ORMA 的关键创新在于运用最优传输（OT）将标记与基序对齐，创建出多标记表征，将多个标记对齐与其相应的基序相整合。另外，我们采用对比学习在三个不同尺度上优化跨模态对齐：标记-原子、多标记-基序和句子-分子，保证正确匹配的文本-分子对之间的相似度最大化，未匹配对的相似度最小化。据我们了解，这是首次探索基序和多标记层面的对齐。在 ChEBI-20 和 PCdes 数据集上的实验结果显示，ORMA 明显优于现有的最先进（SOTA）模型。

> The field of bioinformatics has seen significant progress, making the cross-modal text-molecule retrieval task increasingly vital. This task focuses on accurately retrieving molecule structures based on textual descriptions, by effectively aligning textual descriptions and molecules to assist researchers in identifying suitable molecular candidates. However, many existing approaches overlook the details inherent in molecule sub-structures. In this work, we introduce the Optimal TRansport-based Multi-grained Alignments model (ORMA), a novel approach that facilitates multi-grained alignments between textual descriptions and molecules. Our model features a text encoder and a molecule encoder. The text encoder processes textual descriptions to generate both token-level and sentence-level representations, while molecules are modeled as hierarchical heterogeneous graphs, encompassing atom, motif, and molecule nodes to extract representations at these three levels. A key innovation in ORMA is the application of Optimal Transport (OT) to align tokens with motifs, creating multi-token representations that integrate multiple token alignments with their corresponding motifs. Additionally, we employ contrastive learning to refine cross-modal alignments at three distinct scales: token-atom, multitoken-motif, and sentence-molecule, ensuring that the similarities between correctly matched text-molecule pairs are maximized while those of unmatched pairs are minimized. To our knowledge, this is the first attempt to explore alignments at both the motif and multi-token levels. Experimental results on the ChEBI-20 and PCdes datasets demonstrate that ORMA significantly outperforms existing state-of-the-art (SOTA) models.

[Arxiv](https://arxiv.org/abs/2411.11875)