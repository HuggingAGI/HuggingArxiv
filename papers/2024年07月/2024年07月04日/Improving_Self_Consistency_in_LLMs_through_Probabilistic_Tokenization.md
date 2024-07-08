# 借助概率标记化技术，提升大型语言模型中的自我一致性

发布时间：2024年07月04日

`LLM理论` `人工智能`

> Improving Self Consistency in LLMs through Probabilistic Tokenization

# 摘要

> 先前研究表明，通过在训练阶段对同一输入采用多种分词方式的概率性方法，可以显著提升语言模型的性能。然而，现代大型语言模型 (LLM) 尚未充分利用这一技术。本研究提出一种新方法，旨在通过利用 LLM 分词器的多分词能力，增强其在推理任务中的自我一致性。实验显示，概率性分词不仅增加了语言多样性，还促进了逻辑上多样化的推理路径。我们通过在多个 LLM 系列和推理基准上的实验，深入探讨了这一方法，并揭示了其对自我一致性改进的机制。

> Prior research has demonstrated noticeable performance gains through the use of probabilistic tokenizations, an approach that involves employing multiple tokenizations of the same input string during the training phase of a language model. Despite these promising findings, modern large language models (LLMs) have yet to be trained using probabilistic tokenizations. Interestingly, while the tokenizers of these contemporary LLMs have the capability to generate multiple tokenizations, this property remains underutilized.
  In this work, we propose a novel method to leverage the multiple tokenization capabilities of modern LLM tokenizers, aiming to enhance the self-consistency of LLMs in reasoning tasks. Our experiments indicate that when utilizing probabilistic tokenizations, LLMs generate logically diverse reasoning paths, moving beyond mere surface-level linguistic diversity.We carefully study probabilistic tokenization and offer insights to explain the self consistency improvements it brings through extensive experimentation on 5 LLM families and 4 reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2407.03678)