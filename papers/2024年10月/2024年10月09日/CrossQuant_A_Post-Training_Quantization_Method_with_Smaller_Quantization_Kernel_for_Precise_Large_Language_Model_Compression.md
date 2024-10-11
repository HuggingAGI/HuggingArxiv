# CrossQuant：一种精准压缩大型语言模型的后训练量化方法，采用更小的量化核，提升压缩效率。

发布时间：2024年10月09日

`LLM理论` `人工智能` `计算机科学`

> CrossQuant: A Post-Training Quantization Method with Smaller Quantization Kernel for Precise Large Language Model Compression

# 摘要

> Post-Training Quantization (PTQ) 是压缩大型语言模型 (LLM) 的有效手段。尽管许多研究致力于量化权重和激活，但如何在激活量化后保持 LLM 的准确性仍是一大难题。为此，我们将线性代数中的核概念引入量化函数，定义了“量化核”这一新概念，即被量化为零的激活元素集合。通过量化核的定量分析，我们发现这些元素对保持量化 LLM 的准确性至关重要。随着量化核的减少，量化 LLM 的精度显著提升。若 OPT 模型的量化核比例低于 19%，LLaMA 模型低于 1%，将激活量化为 INT8 的精度损失几乎可以忽略。基于开发小量化核量化方法的目标，我们提出了 CrossQuant：一种简单高效的激活量化方法。CrossQuant 通过行和列方向的绝对最大向量对元素进行交叉量化，使得 OPT 模型的量化核约为 16%，LLaMA 模型则低于 0.1%。实验结果显示，CrossQuant 在语言建模、零样本和少样本任务中显著提升了或保持了困惑度和准确性。

> Post-Training Quantization (PTQ) is an effective technique for compressing Large Language Models (LLMs). While many studies focus on quantizing both weights and activations, it is still a challenge to maintain the accuracy of LLM after activating quantization. To investigate the primary cause, we extend the concept of kernel from linear algebra to quantization functions to define a new term, "quantization kernel", which refers to the set of elements in activations that are quantized to zero. Through quantitative analysis of the quantization kernel, we find that these elements are crucial for maintaining the accuracy of quantized LLMs. With the decrease of quantization kernel, the precision of quantized LLMs increases. If the quantization kernel proportion is kept below 19% for OPT models and below 1% for LLaMA models, the precision loss from quantizing activations to INT8 becomes negligible. Motivated by the goal of developing a quantization method with small quantization kernel, we propose CrossQuant: a simple yet effective method for quantizing activations. CrossQuant cross-quantizes elements using row and column-wise absolute maximum vectors, achieving a quantization kernel of approximately 16% for OPT models and less than 0.1% for LLaMA models. Experimental results on LLMs (LLaMA, OPT) ranging from 6.7B to 70B parameters demonstrate that CrossQuant improves or maintains perplexity and accuracy in language modeling, zero-shot, and few-shot tasks.

[Arxiv](https://arxiv.org/abs/2410.07505)