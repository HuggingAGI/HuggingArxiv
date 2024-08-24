# T2VIndexer：一款专为高效文本至视频检索设计的生成式视频索引工具

发布时间：2024年08月21日

`LLM应用` `多媒体` `计算机视觉`

> T2VIndexer: A Generative Video Indexer for Efficient Text-Video Retrieval

# 摘要

> 当前的文本-视频检索方法通过跨模态匹配计算相似度分数，然后排序得出结果，但这种方法随着候选视频增多，时间成本显著增加。生成模型虽在自然语言处理和计算机视觉中应用广泛，但在多模态检索领域尚未探索。为此，我们提出T2VIndexer，一种直接生成视频标识符的序列到序列模型，旨在提升检索效率并保持高准确性。通过视频标识符编码和查询-标识符增强技术，我们的方法在四个标准数据集上显著提升了检索效率，使基线模型在减少50%检索时间的情况下，性能仍有提升。代码已开源，详见GitHub链接。

> Current text-video retrieval methods mainly rely on cross-modal matching between queries and videos to calculate their similarity scores, which are then sorted to obtain retrieval results. This method considers the matching between each candidate video and the query, but it incurs a significant time cost and will increase notably with the increase of candidates. Generative models are common in natural language processing and computer vision, and have been successfully applied in document retrieval, but their application in multimodal retrieval remains unexplored. To enhance retrieval efficiency, in this paper, we introduce a model-based video indexer named T2VIndexer, which is a sequence-to-sequence generative model directly generating video identifiers and retrieving candidate videos with constant time complexity. T2VIndexer aims to reduce retrieval time while maintaining high accuracy. To achieve this goal, we propose video identifier encoding and query-identifier augmentation approaches to represent videos as short sequences while preserving their semantic information. Our method consistently enhances the retrieval efficiency of current state-of-the-art models on four standard datasets. It enables baselines with only 30\%-50\% of the original retrieval time to achieve better retrieval performance on MSR-VTT (+1.0%), MSVD (+1.8%), ActivityNet (+1.5%), and DiDeMo (+0.2%). The code is available at https://github.com/Lilidamowang/T2VIndexer-generativeSearch.

[Arxiv](https://arxiv.org/abs/2408.11432)