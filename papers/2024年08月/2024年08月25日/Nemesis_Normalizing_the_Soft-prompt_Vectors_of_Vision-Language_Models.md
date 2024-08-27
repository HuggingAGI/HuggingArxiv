# Nemesis：优化视觉-语言模型中的软提示向量规范化

发布时间：2024年08月25日

`LLM应用` `计算机视觉`

> Nemesis: Normalizing the Soft-prompt Vectors of Vision-Language Models

# 摘要

> 随着CLIP等大规模预训练视觉-语言模型的普及，软提示调优已成为适应多种下游任务的热门方法。然而，关于可学习软提示向量的范数如何影响模型性能的研究甚少。这引发了一个新问题：“在VLMs中，我们是否需要归一化软提示？”通过大量实验，我们发现了**低范数效应**，即降低某些提示向量的范数有时能提升性能，反之则降低。基于此，我们提出了**Nemesis**方法，专门用于归一化VLMs中的软提示向量。我们的研究首次系统探讨了这一问题，为软提示调优领域提供了新视角。相关代码已公开在\texttt{\href{https://github.com/ShyFoo/Nemesis}{GitHub}}。

> With the prevalence of large-scale pretrained vision-language models (VLMs), such as CLIP, soft-prompt tuning has become a popular method for adapting these models to various downstream tasks. However, few works delve into the inherent properties of learnable soft-prompt vectors, specifically the impact of their norms to the performance of VLMs. This motivates us to pose an unexplored research question: ``Do we need to normalize the soft prompts in VLMs?'' To fill this research gap, we first uncover a phenomenon, called the \textbf{Low-Norm Effect} by performing extensive corruption experiments, suggesting that reducing the norms of certain learned prompts occasionally enhances the performance of VLMs, while increasing them often degrades it. To harness this effect, we propose a novel method named \textbf{N}ormalizing th\textbf{e} soft-pro\textbf{m}pt v\textbf{e}ctors of vi\textbf{si}on-language model\textbf{s} (\textbf{Nemesis}) to normalize soft-prompt vectors in VLMs. To the best of our knowledge, our work is the first to systematically investigate the role of norms of soft-prompt vector in VLMs, offering valuable insights for future research in soft-prompt tuning. The code is available at \texttt{\href{https://github.com/ShyFoo/Nemesis}{https://github.com/ShyFoo/Nemesis}}.

[Arxiv](https://arxiv.org/abs/2408.13979)