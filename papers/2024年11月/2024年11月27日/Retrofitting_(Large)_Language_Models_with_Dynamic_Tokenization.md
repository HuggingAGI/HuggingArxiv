# 利用动态标记化改造（大型）语言模型

发布时间：2024年11月27日

`LLM应用` `语言模型`

> Retrofitting (Large) Language Models with Dynamic Tokenization

# 摘要

> 当前的语言模型（LMs）采用固定、静态的子词分词器。这种常被默认的选择，通常致使在非英语语言里效率与能力降低，也让 LMs 在新领域或新语言中的应用面临挑战。为应对这些问题，我们提议用动态分词来改进 LMs：这是一种依据输入文本动态确定分词边界的方式。对于编码器式模型，我们引入了受字节对编码（BPE）启发的子词合并算法，不过是在批次层面。我们在一个批次中合并频繁的子词序列，接着运用预先训练的嵌入预测超网络实时计算分词嵌入。在应用于词级边界时，这在 XNLI 上的 14 种语言中平均将分词序列长度减少了超过 20％，而 XLM-R 的任务性能下降不足 2％。对于解码器式模型，我们通过两种方式应用动态分词：1）在预填充方面，几乎完全维持 Mistral-7B 的性能，序列相对词级减少高达 40％；2）借助近似最近邻索引，使用百万个分词的词汇实现快速生成，展现出对更大、动态词汇表的可扩展性。总体而言，我们的发现表明，动态分词显著提升了推理速度，增进了跨语言的公平性，在克服静态分词的局限方面实现了重大跨越，让 LMs 更公平且更具适应性。

> Current language models (LMs) use a fixed, static subword tokenizer. This choice, often taken for granted, typically results in degraded efficiency and capabilities in languages other than English, and makes it challenging to apply LMs to new domains or languages. To address these issues, we propose retrofitting LMs with dynamic tokenization: a way to dynamically decide on token boundaries based on the input text. For encoder-style models, we introduce a subword-merging algorithm inspired by byte-pair encoding (BPE), but at a batch level. We merge frequent subword sequences in a batch, then apply a pretrained embedding-prediction hypernetwork to compute the token embeddings on-the-fly. When applied with word-level boundaries, this on average reduces token sequence lengths by >20% across 14 languages on XNLI with XLM-R while degrading its task performance by less than 2%. For decoder-style models, we apply dynamic tokenization in two ways: 1) for prefilling, maintaining performance of Mistral-7B almost completely with up to 40% sequence reduction - relative to the word-level; and 2) via an approximate nearest neighbor index, achieving fast generation with a one million token vocabulary, demonstrating scalability to even larger, dynamic vocabularies. Overall, our findings show that dynamic tokenization substantially improves inference speed and promotes fairness across languages, making a leap towards overcoming the limitations of static tokenization and enabling more equitable and adaptable LMs.

[Arxiv](https://arxiv.org/abs/2411.18553)