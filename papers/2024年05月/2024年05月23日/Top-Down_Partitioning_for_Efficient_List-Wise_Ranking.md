# 采用自顶向下的分区策略，列表级排序得以高效实现。

发布时间：2024年05月23日

`RAG

理由：这篇论文主要讨论了大型语言模型（LLMs）在信息检索中的应用，特别是在文档排序方面的改进。它提出了一种新的算法来优化滑动窗口方法在列表式重新排序中的应用，这与RAG（Retrieval-Augmented Generation）模型在信息检索和文档排序方面的应用密切相关。RAG模型通常结合了检索和生成两种技术，以提高信息检索的效率和准确性。这篇论文的创新点在于改进了文档排序的算法，使其更高效且减少计算冗余，这与RAG模型的目标相符。因此，将其归类为RAG是合适的。` `信息检索`

> Top-Down Partitioning for Efficient List-Wise Ranking

# 摘要

> 大型语言模型（LLMs）极大地改变了自然语言处理和信息检索的面貌。这些生成模型通过扩展的上下文窗口，实现了对多个文档的一次性排序，即列表式排序。尽管如此，单次推理中可排序的文档数量仍有限制，这促使了滑动窗口方法的广泛应用，以筛选出排名列表中的前k个最相关文档。我们认为，滑动窗口方法并不适合列表式重新排序，原因有三：一是其当前形式无法并行处理；二是它在初始排名的基础上，反复对最佳文档集进行重新评分，导致计算步骤冗余；三是它采用自下而上的策略，优先对排名较低的文档进行评分，而非排名较高的文档。鉴于这些不足，以及初步研究显示列表式排名器倾向于在其上下文窗口开始时偏向相关文档，我们提出了一种创新的算法，该算法将排名分割至深度k，并自上而下处理文档。与滑动窗口方法不同，我们的算法因使用枢轴元素而天生具备并行性，该枢轴元素能与任意深度的文档同时进行比较。这一改进使我们在深度100的排名时，将预期的推理调用次数减少了约33%，同时在多个强大的重新排名器中，性能与先前方法相匹配。

> Large Language Models (LLMs) have significantly impacted many facets of natural language processing and information retrieval. Unlike previous encoder-based approaches, the enlarged context window of these generative models allows for ranking multiple documents at once, commonly called list-wise ranking. However, there are still limits to the number of documents that can be ranked in a single inference of the model, leading to the broad adoption of a sliding window approach to identify the k most relevant items in a ranked list. We argue that the sliding window approach is not well-suited for list-wise re-ranking because it (1) cannot be parallelized in its current form, (2) leads to redundant computational steps repeatedly re-scoring the best set of documents as it works its way up the initial ranking, and (3) prioritizes the lowest-ranked documents for scoring rather than the highest-ranked documents by taking a bottom-up approach. Motivated by these shortcomings and an initial study that shows list-wise rankers are biased towards relevant documents at the start of their context window, we propose a novel algorithm that partitions a ranking to depth k and processes documents top-down. Unlike sliding window approaches, our algorithm is inherently parallelizable due to the use of a pivot element, which can be compared to documents down to an arbitrary depth concurrently. In doing so, we reduce the number of expected inference calls by around 33% when ranking at depth 100 while matching the performance of prior approaches across multiple strong re-rankers.

[Arxiv](https://arxiv.org/abs/2405.14589)