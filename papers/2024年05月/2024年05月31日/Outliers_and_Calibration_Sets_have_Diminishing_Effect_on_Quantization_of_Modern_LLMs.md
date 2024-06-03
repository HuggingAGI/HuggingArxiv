# 现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。

发布时间：2024年05月31日

`LLM理论

这篇论文主要探讨了Post-Training Quantization (PTQ) 在大型语言模型 (LLMs) 中的应用，特别是校准集对隐藏激活的影响。研究关注的是量化技术如何影响不同模型的性能，以及如何通过调整量化策略来优化推理速度。这属于对LLM理论的深入研究，因为它涉及模型内部的量化过程和性能优化，而不是直接的应用或Agent行为。因此，将其归类为LLM理论。` `机器学习`

> Outliers and Calibration Sets have Diminishing Effect on Quantization of Modern LLMs

# 摘要

> Post-Training Quantization (PTQ) 通过减少内存使用，提升了大型语言模型 (LLMs) 的效率，使其运行更快，兼容更多硬件，但性能略有下降。我们研究了校准集在 PTQ 中的关键作用，特别是它们如何影响不同开源 LLMs 的隐藏激活。校准集对于评估激活幅度和识别可能扭曲量化范围并损害性能的异常值至关重要。分析显示，不同模型的量化效果差异显著。较旧的 OPT 模型在面对不同校准集时，性能显著下降，对异常值极为敏感。而新模型如 Llama-2 7B, Llama-3 8B, Command-R 35B, 和 Mistral 7B 则表现出强大的鲁棒性，Mistral 7B 几乎不受异常值影响，激活稳定。这些发现提示我们可能需要调整 PTQ 策略。随着预训练技术的进步，异常值的重要性降低，我们需重新审视当前量化文献的基础。重点应转向优化推理速度，而非仅关注异常值的保留，以适应最先进 LLMs 的演变特性。

> Post-Training Quantization (PTQ) enhances the efficiency of Large Language Models (LLMs) by enabling faster operation and compatibility with more accessible hardware through reduced memory usage, at the cost of small performance drops. We explore the role of calibration sets in PTQ, specifically their effect on hidden activations in various notable open-source LLMs. Calibration sets are crucial for evaluating activation magnitudes and identifying outliers, which can distort the quantization range and negatively impact performance. Our analysis reveals a marked contrast in quantization effectiveness across models. The older OPT model, which much of the quantization literature is based on, shows significant performance deterioration and high susceptibility to outliers with varying calibration sets. In contrast, newer models like Llama-2 7B, Llama-3 8B, Command-R 35B, and Mistral 7B demonstrate strong robustness, with Mistral 7B showing near-immunity to outliers and stable activations. These findings suggest a shift in PTQ strategies might be needed. As advancements in pre-training methods reduce the relevance of outliers, there is an emerging need to reassess the fundamentals of current quantization literature. The emphasis should pivot towards optimizing inference speed, rather than primarily focusing on outlier preservation, to align with the evolving characteristics of state-of-the-art LLMs.

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/GPTQ_nonsensical_perplexity.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/GPTQ_nonsensical_accuracy.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/GPTQ_arc.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/GPTQ_piqa.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/GPTQ_accuracy.png)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/AWQ_accuracy.png)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/SmoothQuant_accuracy.png)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/perplexity_naive.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/average_results_naive.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/eng_Latn_attn_hist.png)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/eng_Latn_mlp_hist.png)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/cmn_Hans_attn_hist.png)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/cmn_Hans_mlp_hist.png)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/models.png)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/eng_Latn_OPT_6.7B.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/eng_Latn_Llama-1_7B.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/pltbar.png)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/eng_Latn_Llama-2_7B.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/eng_Latn_LLaMa-3_8B.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/eng_Latn_Mistral_7B.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/eng_Latn_Command_R_35B.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/GPTQ_nonsensical_perplexity.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/GPTQ_nonsensical_accuracy.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/AWQ_nonsensical_perplexity.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/AWQ_nonsensical_accuracy.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/Smoothq_nonsensical_perplexity.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/Smoothq_nonsensical_accuracy.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/GPTQ_arc.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/GPTQ_piqa.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/AWQ_arc.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/AWQ_piqa.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/Smoothq_ARC.jpg)

![现代大型语言模型的量化过程中，离群值与校准集的影响正逐渐减弱。](../../../paper_images/2405.20835/Smoothq_piqa.jpg)

[Arxiv](https://arxiv.org/abs/2405.20835)