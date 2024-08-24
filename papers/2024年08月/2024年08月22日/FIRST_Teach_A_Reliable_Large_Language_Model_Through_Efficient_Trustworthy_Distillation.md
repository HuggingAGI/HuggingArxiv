# 利用高效可信的蒸馏技术，培养一个可靠的大型语言模型

发布时间：2024年08月22日

`LLM理论` `人工智能`

> FIRST: Teach A Reliable Large Language Model Through Efficient Trustworthy Distillation

# 摘要

> 随着大型语言模型（LLM）在日常生活中的普及，人们对其准确性和校准度的期望也随之提高。尽管微调已成为提升模型实用性的主流手段，但其导致的“调谐误校准”问题仍使其信任度不尽如人意。本文深入分析了微调模型中的误校准现象及其成因，并探讨了蒸馏技术对此问题的缓解作用。我们创新性地提出了高效可信蒸馏（FIRST）方法，该方法通过巧妙利用教师模型的一小部分知识，以经济高效的方式构建出可靠的语言模型。实验表明，该方法在提升模型准确性的同时，显著降低了误校准率，从而大幅增强了模型的信任度。

> Large language models (LLMs) have become increasingly prevalent in our daily lives, leading to an expectation for LLMs to be trustworthy -- - both accurate and well-calibrated (the prediction confidence should align with its ground truth correctness likelihood). Nowadays, fine-tuning has become the most popular method for adapting a model to practical usage by significantly increasing accuracy on downstream tasks. Despite the great accuracy it achieves, we found fine-tuning is still far away from satisfactory trustworthiness due to "tuning-induced mis-calibration". In this paper, we delve deeply into why and how mis-calibration exists in fine-tuned models, and how distillation can alleviate the issue. Then we further propose a brand new method named Efficient Trustworthy Distillation (FIRST), which utilizes a small portion of teacher's knowledge to obtain a reliable language model in a cost-efficient way. Specifically, we identify the "concentrated knowledge" phenomenon during distillation, which can significantly reduce the computational burden. Then we apply a "trustworthy maximization" process to optimize the utilization of this small portion of concentrated knowledge before transferring it to the student. Experimental results demonstrate the effectiveness of our method, where better accuracy (+2.3%) and less mis-calibration (-10%) are achieved on average across both in-domain and out-of-domain scenarios, indicating better trustworthiness.

[Arxiv](https://arxiv.org/abs/2408.12168)