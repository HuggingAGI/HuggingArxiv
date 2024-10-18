# GeoCoder：借助视觉-语言模型生成模块化代码，轻松解决几何难题

发布时间：2024年10月17日

`LLM应用` `计算机视觉`

> GeoCoder: Solving Geometry Problems by Generating Modular Code through Vision-Language Models

# 摘要

> 几何问题解决需要高级推理能力，而视觉-语言模型（VLM）在多模态任务中虽有显著进展，但在几何问题上仍显不足。为此，我们推出了 GeoCoder，通过模块化代码微调，利用预定义的几何函数库生成并执行代码，确保计算的准确性和确定性。此外，我们还设计了 RAG-GeoCoder，引入非参数记忆模块，减少对参数记忆的依赖。这些创新使 VLM 的几何推理能力大幅提升，在 GeomVerse 数据集上，平均性能提升了超过 16%。

> Geometry problem-solving demands advanced reasoning abilities to process multimodal inputs and employ mathematical knowledge effectively. Vision-language models (VLMs) have made significant progress in various multimodal tasks. Yet, they still struggle with geometry problems and are significantly limited by their inability to perform mathematical operations not seen during pre-training, such as calculating the cosine of an arbitrary angle, and by difficulties in correctly applying relevant geometry formulas. To overcome these challenges, we present GeoCoder, which leverages modular code-finetuning to generate and execute code using a predefined geometry function library. By executing the code, we achieve accurate and deterministic calculations, contrasting the stochastic nature of autoregressive token prediction, while the function library minimizes errors in formula usage. We also propose a multimodal retrieval-augmented variant of GeoCoder, named RAG-GeoCoder, which incorporates a non-parametric memory module for retrieving functions from the geometry library, thereby reducing reliance on parametric memory. Our modular code-finetuning approach enhances the geometric reasoning capabilities of VLMs, yielding an average improvement of over 16% across various question complexities on the GeomVerse dataset compared to other finetuning methods.

[Arxiv](https://arxiv.org/abs/2410.13510)