# 多阶段视觉标记丢弃：致力于打造高效的多模态大型语言模型

发布时间：2024年11月16日

`LLM应用` `多模态` `语言模型`

> Multi-Stage Vision Token Dropping: Towards Efficient Multimodal Large Language Model

# 摘要

> 在多模态大型语言模型中，视觉标记往往存在明显的时空冗余，占据了大量输入标记，从而影响了推理效率。为化解这一难题，近来有一些研究工作在推理时舍弃不重要的标记，而每个标记的重要性仅由视觉编码阶段或预填充阶段的信息来判定。本文中，我们提出了多阶段标记丢弃（MustDrop）方法，用于衡量每个标记在整个生命周期（涵盖视觉编码阶段、预填充阶段和解码阶段）中的重要性。具体而言，在视觉编码阶段，MustDrop 会合并空间上相邻且相似度高的标记，并构建关键标记集，以留存最关键的视觉标记，避免其在后续阶段被丢弃。在预填充阶段，MustDrop 借助文本语义的引导，运用双重注意力过滤策略进一步压缩视觉标记。在解码阶段，提出了一种输出感知的缓存策略，以进一步缩小 KV 缓存的规模。通过在多阶段流程中采用定制策略，MustDrop 能够更精准地辨别重要和冗余的标记，从而在性能与效率之间达成最优平衡。例如，MustDrop 在 LLaVA 上能减少约 88.5％的 FLOPs，压缩比达 92.2％，同时保持了相近的准确率。我们的代码可在 url{https://github.com/liuting20/MustDrop} 获取。

> The vision tokens in multimodal large language models usually exhibit significant spatial and temporal redundancy and take up most of the input tokens, which harms their inference efficiency. To solve this problem, some recent works were introduced to drop the unimportant tokens during inference where the importance of each token is decided only by the information in either the vision encoding stage or the prefilling stage. In this paper, we propose Multi-stage Token Dropping (MustDrop) to measure the importance of each token from the whole lifecycle, including the vision encoding stage, prefilling stage, and decoding stage. Concretely, in the visual encoding stage, MustDrop merges spatially adjacent tokens with high similarity, and establishes a key token set to retain the most vision-critical tokens, preventing them from being discarded in later stages. In the prefilling stage, MustDrop further compresses vision tokens by the guidance of text semantics, with a dual-attention filtering strategy. In the decoding stage, an output-aware cache policy is proposed to further reduce the size of the KV cache. By leveraging tailored strategies in the multi-stage process, MustDrop can more precisely recognize the important and redundant tokens, thus achieving an optimal balance between performance and efficiency. For instance, MustDrop reduces about 88.5\% FLOPs on LLaVA with a compression ratio of 92.2\% while maintaining comparable accuracy. Our codes are available at url{https://github.com/liuting20/MustDrop}.

[Arxiv](https://arxiv.org/abs/2411.10803)