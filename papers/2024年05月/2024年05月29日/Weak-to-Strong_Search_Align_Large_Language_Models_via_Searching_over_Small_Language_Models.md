# 从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐

发布时间：2024年05月29日

`LLM应用

这篇论文主要探讨了大型语言模型（LLM）在微调过程中如何更好地匹配人类偏好，提出了一种名为“弱到强搜索”的新方法。该方法通过在测试阶段进行贪婪搜索，比较微调与未微调的小型模型，以最大化对数似然差异，并利用冻结的大型模型来提高计算效率和模型的泛化能力。这种方法在情感控制生成和摘要任务中展示了显著的效果，并在AlpacaEval 2.0指令遵循任务中提升了大型模型的表现。因此，这篇论文属于LLM应用类别，因为它专注于LLM的具体应用和改进方法，而不是理论研究或Agent、RAG相关的研究。` `模型优化`

> Weak-to-Strong Search: Align Large Language Models via Searching over Small Language Models

# 摘要

> 大型语言模型常通过微调来匹配人类偏好，但这一过程充满挑战。我们提出的“弱到强搜索”方法，将模型对齐视为测试阶段的贪婪搜索，通过比较微调与未微调的小型模型，最大化对数似然差异，同时利用冻结的大型模型。这种方法不仅避免了直接微调大型模型，提高了计算效率，还通过弱测试时的指导增强了模型的泛化能力。实证显示，此方法在多种任务中均表现出色。在情感控制生成和摘要任务中，我们利用微调与未微调的GPT2模型，无需额外训练即显著提升了大型模型的对齐效果。在AlpacaEval 2.0这一指令遵循的难题中，重用小型模型对显著提升了大型模型的胜率，尽管小型模型的胜率本身不高。

> Large language models are usually fine-tuned to align with human preferences. However, fine-tuning a large language model can be challenging. In this work, we introduce $\textit{weak-to-strong search}$, framing the alignment of a large language model as a test-time greedy search to maximize the log-likelihood difference between small tuned and untuned models while sampling from the frozen large model. This method serves both as (i) a compute-efficient model up-scaling strategy that avoids directly tuning the large model and as (ii) an instance of weak-to-strong generalization that enhances a strong model with weak test-time guidance. Empirically, we demonstrate the flexibility of weak-to-strong search across different tasks. In controlled-sentiment generation and summarization, we use tuned and untuned $\texttt{gpt2}$s to effectively improve the alignment of large models without additional training. Crucially, in a more difficult instruction-following benchmark, AlpacaEval 2.0, we show that reusing off-the-shelf small model pairs (e.g., $\texttt{zephyr-7b-beta}$ and its untuned version) can significantly improve the length-controlled win rates of both white-box and black-box large models against $\texttt{gpt-4-turbo}$ (e.g., $34.4 \rightarrow 37.9$ for $\texttt{Llama-3-70B-Instruct}$ and $16.0 \rightarrow 20.1$ for $\texttt{gpt-3.5-turbo-instruct}$), despite the small models' low win rates $\approx 10.0$.

![从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐](../../../paper_images/2405.19262/x1.png)

![从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐](../../../paper_images/2405.19262/x2.png)

![从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐](../../../paper_images/2405.19262/x3.png)

![从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐](../../../paper_images/2405.19262/x4.png)

![从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐](../../../paper_images/2405.19262/x5.png)

![从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐](../../../paper_images/2405.19262/x6.png)

![从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐](../../../paper_images/2405.19262/x7.png)

![从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐](../../../paper_images/2405.19262/x8.png)

![从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐](../../../paper_images/2405.19262/x9.png)

![从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐](../../../paper_images/2405.19262/x10.png)

![从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐](../../../paper_images/2405.19262/x11.png)

![从弱至强搜索：借助小语言模型探索，实现大型语言模型的精准对齐](../../../paper_images/2405.19262/x12.png)

[Arxiv](https://arxiv.org/abs/2405.19262)