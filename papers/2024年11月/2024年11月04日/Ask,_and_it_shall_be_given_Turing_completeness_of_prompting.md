# 问，就会得到：提示的图灵完备性

发布时间：2024年11月04日

`LLM理论` `机器学习` `理论研究`

> Ask, and it shall be given: Turing completeness of prompting

# 摘要

> 自从 GPT 取得成功以来，大型语言模型（LLM）一直在彻底改变机器学习，并开启了所谓的 LLM 提示范式。在 LLM 时代，人们训练一个单一的通用 LLM，并为 LLM 提供不同的提示来执行不同的任务。然而，这种经验上的成功在很大程度上缺乏理论上的理解。在这里，据我们所知，我们对 LLM 提示范式进行了首次理论研究。在这项工作中，我们表明提示实际上是图灵完备的：存在一个有限大小的 Transformer，对于任何可计算的函数，都存在一个相应的提示，遵循该提示，Transformer 可以计算该函数。此外，我们表明，即使我们只使用一个单一的有限大小的 Transformer，它仍然可以实现几乎与所有无界大小的 Transformer 类相同的复杂度界限。总的来说，我们的结果表明，提示可以使单个有限大小的 Transformer 高效通用，这为实践中的提示工程建立了理论基础。

> Since the success of GPT, large language models (LLMs) have been revolutionizing machine learning and have initiated the so-called LLM prompting paradigm. In the era of LLMs, people train a single general-purpose LLM and provide the LLM with different prompts to perform different tasks. However, such empirical success largely lacks theoretical understanding. Here, we present the first theoretical study on the LLM prompting paradigm to the best of our knowledge. In this work, we show that prompting is in fact Turing-complete: there exists a finite-size Transformer such that for any computable function, there exists a corresponding prompt following which the Transformer computes the function. Furthermore, we show that even though we use only a single finite-size Transformer, it can still achieve nearly the same complexity bounds as that of the class of all unbounded-size Transformers. Overall, our result reveals that prompting can enable a single finite-size Transformer to be efficiently universal, which establishes a theoretical underpinning for prompt engineering in practice.

[Arxiv](https://arxiv.org/abs/2411.01992)