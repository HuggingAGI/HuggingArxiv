# 通过实体链接进行信息检索

发布时间：2024年04月07日

`LLM应用` `信息检索` `实体链接`

> Information Retrieval with Entity Linking

# 摘要

> 尽管传统稀疏检索器在资源较少的环境中展现出优势，但它们仍需依赖于查询和文档集合间高维词袋（BoW）表示的精确匹配，这限制了检索性能，因为存在语义差异和词汇缺口。相比之下，基于变换器的密集检索器通过采用语料库的低维上下文化表示，在信息检索任务上取得了显著提升。尽管密集检索器因其高效性而受到推崇，但相较于稀疏检索器，它们在效率和泛化能力上仍有不足。在轻量级检索任务中，高昂的计算资源和时间成本成为了放弃潜在优势的密集模型的主要障碍。本文提出了一种提升稀疏检索器性能的方法，即通过两种格式（显式和哈希）将链接实体扩展到查询和文档中。引入了一个零样本端到端密集实体链接系统，用于实体识别和消歧，以增强语料库。借助先进的实体链接技术，有望缩小稀疏与密集检索器之间的性能差距。实验基于MS MARCO段落数据集，采用了原始qrel集、MonoT5优化后的重排qrels，以及DuoT5进一步优化的集合。鉴于研究重点在于大型信息检索系统中串联排名架构的初期检索阶段，因此采用recall@1000作为评估指标。本研究所提出的方法同样能够有效检索出以往研究中认为难度较大的查询子集的相关文档。

> Despite the advantages of their low-resource settings, traditional sparse retrievers depend on exact matching approaches between high-dimensional bag-of-words (BoW) representations of both the queries and the collection. As a result, retrieval performance is restricted by semantic discrepancies and vocabulary gaps. On the other hand, transformer-based dense retrievers introduce significant improvements in information retrieval tasks by exploiting low-dimensional contextualized representations of the corpus. While dense retrievers are known for their relative effectiveness, they suffer from lower efficiency and lack of generalization issues, when compared to sparse retrievers. For a lightweight retrieval task, high computational resources and time consumption are major barriers encouraging the renunciation of dense models despite potential gains. In this work, I propose boosting the performance of sparse retrievers by expanding both the queries and the documents with linked entities in two formats for the entity names: 1) explicit and 2) hashed. A zero-shot end-to-end dense entity linking system is employed for entity recognition and disambiguation to augment the corpus. By leveraging the advanced entity linking methods, I believe that the effectiveness gap between sparse and dense retrievers can be narrowed. Experiments are conducted on the MS MARCO passage dataset using the original qrel set, the re-ranked qrels favoured by MonoT5 and the latter set further re-ranked by DuoT5. Since I am concerned with the early stage retrieval in cascaded ranking architectures of large information retrieval systems, the results are evaluated using recall@1000. The suggested approach is also capable of retrieving documents for query subsets judged to be particularly difficult in prior work.

![通过实体链接进行信息检索](../../../paper_images/2404.08678/query_expansion.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/star-adore.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/classifier.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/all_original_2.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/all_original_3.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/all_original_4.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/all_original_1.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/veiled_original_2.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/veiled_original_3.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/veiled_original_4.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/veiled_original_1.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/pygmy_original_2.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/pygmy_original_3.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/pygmy_original_4.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/pygmy_original_1.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/lesser_original_2.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/lesser_original_3.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/lesser_original_4.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/lesser_original_1.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/all_monoT5_2.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/all_monoT5_3.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/all_monoT5_4.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/all_monoT5_1.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/veiled_monoT5_2.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/veiled_monoT5_3.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/veiled_monoT5_4.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/veiled_monoT5_1.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/pygmy_monoT5_2.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/pygmy_monoT5_3.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/pygmy_monoT5_4.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/pygmy_monoT5_1.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/lesser_monoT5_2.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/lesser_monoT5_3.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/lesser_monoT5_4.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/lesser_monoT5_1.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/all_duoT5_2.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/all_duoT5_3.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/all_duoT5_4.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/all_duoT5_1.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/veiled_duoT5_2.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/veiled_duoT5_3.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/veiled_duoT5_4.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/veiled_duoT5_1.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/pygmy_duoT5_2.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/pygmy_duoT5_3.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/pygmy_duoT5_4.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/pygmy_duoT5_1.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/lesser_duoT5_2.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/lesser_duoT5_3.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/lesser_duoT5_4.png)

![通过实体链接进行信息检索](../../../paper_images/2404.08678/lesser_duoT5_1.png)

[Arxiv](https://arxiv.org/abs/2404.08678)