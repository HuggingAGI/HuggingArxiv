# 多模态大型语言模型中视觉表示的法则

发布时间：2024年08月29日

`LLM理论` `人工智能` `计算机视觉`

> Law of Vision Representation in MLLMs

# 摘要

> 在多模态大型语言模型中，我们揭示了“视觉表示定律”，阐明了跨模态对齐与视觉表示对应关系对模型性能的显著影响。通过 AC 分数量化这些因素，并在多样化的实验中验证，我们发现 AC 分数与性能呈线性关系。这一发现使我们能够优化视觉表示，无需频繁微调语言模型，大幅降低计算成本达 99.7%。

> We present the "Law of Vision Representation" in multimodal large language models (MLLMs). It reveals a strong correlation between the combination of cross-modal alignment, correspondence in vision representation, and MLLM performance. We quantify the two factors using the cross-modal Alignment and Correspondence score (AC score). Through extensive experiments involving thirteen different vision representation settings and evaluations across eight benchmarks, we find that the AC score is linearly correlated to model performance. By leveraging this relationship, we are able to identify and train the optimal vision representation only, which does not require finetuning the language model every time, resulting in a 99.7% reduction in computational cost.

[Arxiv](https://arxiv.org/abs/2408.16357)