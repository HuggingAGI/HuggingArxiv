# 大型语言模型推理：几何视角探析

发布时间：2024年07月02日

`LLM理论` `人工智能` `机器学习`

> Reasoning in Large Language Models: A Geometric Perspective

# 摘要

> 提升大型语言模型（LLM）的推理能力对其在实际应用中的发展至关重要。本研究通过几何视角深入探讨了LLM的推理能力，揭示了LLM表达力与自注意力图密度间的内在联系。分析显示，这些图的密度直接影响了输入到MLP块的内在维度，进而决定了LLM的表达能力。通过理论与实例验证，我们证实了内在维度越高，LLM的表达力越强。此外，我们还提供了实证，将这一几何框架与近期旨在提升LLM推理能力的方法进展相联系。

> The advancement of large language models (LLMs) for real-world applications hinges critically on enhancing their reasoning capabilities. In this work, we explore the reasoning abilities of large language models (LLMs) through their geometrical understanding. We establish a connection between the expressive power of LLMs and the density of their self-attention graphs. Our analysis demonstrates that the density of these graphs defines the intrinsic dimension of the inputs to the MLP blocks. We demonstrate through theoretical analysis and toy examples that a higher intrinsic dimension implies a greater expressive capacity of the LLM. We further provide empirical evidence linking this geometric framework to recent advancements in methods aimed at enhancing the reasoning capabilities of LLMs.

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/partition2d_biais.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/partition2d_biaisless.png.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/sin_50_neurons.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/sin_500_neurons.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/num_regions.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/region_context_10_heads_1.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/region_context_10_heads_10.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/region_context_100_heads_1.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/region_context_100_heads_10.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/region_all_imshow.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/slice_id.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/layer30_8b_instruct_fewshot.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/layer78_70b_instruct_fewshot.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/layer30_8b_instruct_random.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/layer30_8b_instruct_permuted.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/8b_ID.png)

![大型语言模型推理：几何视角探析](../../../paper_images/2407.02678/70b_ID.png)

[Arxiv](https://arxiv.org/abs/2407.02678)