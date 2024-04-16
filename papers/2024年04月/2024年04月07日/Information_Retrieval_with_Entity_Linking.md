# 通过实体链接进行信息检索

发布时间：2024年04月07日

`LLM应用` `信息检索` `实体链接`

> Information Retrieval with Entity Linking

# 摘要

> 虽然传统稀疏检索器在资源受限环境下有其优势，但它们依赖于查询和文档的高维词袋表示之间的精确匹配，这限制了其检索性能，因为存在语义和词汇的差异。相比之下，基于变换器的密集检索器通过使用语料库的低维情境化表示，在信息检索任务中取得了显著进步。然而，密集检索器相较于稀疏检索器，存在效率低下和泛化能力不足的问题。为了提升稀疏检索器的性能，我提出一种方法，通过两种形式（显式和哈希）扩展查询和文档中的链接实体。采用零次端到端的密集实体链接系统来识别和消歧实体，从而增强语料库。我相信，通过运用高级的实体链接技术，可以缩小稀疏和密集检索器之间的性能差距。我们在MS MARCO段落数据集上进行了实验，使用了原始的qrel集、MonoT5优化后的重新排名的qrels，以及DuoT5进一步优化的排名结果。鉴于我关注的是大型信息检索系统级联排名结构中的初期检索阶段，因此我们使用recall@1000来评估结果。这种方法还能够检索那些在之前研究中被认为具有挑战性的查询子集的文档。

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