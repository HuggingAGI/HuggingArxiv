# LoRA 精简学习，记忆更牢

发布时间：2024年05月15日

`LLM理论

这篇论文探讨了LoRA（低秩适应）作为一种参数高效的微调技术在大型语言模型中的应用，并比较了它与完全微调的性能差异。论文不仅关注了LoRA在特定领域的性能，还分析了其在非目标领域任务上的表现，以及其正则化效果。此外，论文还提出了关于使用LoRA进行微调的最佳实践建议。这些内容更多地涉及了大型语言模型的理论层面，包括模型微调的方法、性能分析和优化策略，因此归类为LLM理论。` `机器学习`

> LoRA Learns Less and Forgets Less

# 摘要

> LoRA，作为一种参数高效的微调技术，通过训练权重矩阵的低秩扰动，为大型语言模型节省了大量内存。我们对比了LoRA与完全微调在编程和数学领域的性能，并探讨了两种数据制度：指令微调与持续预训练。尽管LoRA在多数情况下性能不及完全微调，但它展现了一种独特的优势：在非目标领域任务上，LoRA能更好地保持基础模型的性能。此外，LoRA的正则化效果优于传统的权重衰减和丢弃技术，促进了生成内容的多样性。我们发现，完全微调产生的扰动秩远高于LoRA，这可能是性能差异的原因之一。最后，我们提出了使用LoRA进行微调的最佳实践建议。

> Low-Rank Adaptation (LoRA) is a widely-used parameter-efficient finetuning method for large language models. LoRA saves memory by training only low rank perturbations to selected weight matrices. In this work, we compare the performance of LoRA and full finetuning on two target domains, programming and mathematics. We consider both the instruction finetuning ($\approx$100K prompt-response pairs) and continued pretraining ($\approx$10B unstructured tokens) data regimes. Our results show that, in most settings, LoRA substantially underperforms full finetuning. Nevertheless, LoRA exhibits a desirable form of regularization: it better maintains the base model's performance on tasks outside the target domain. We show that LoRA provides stronger regularization compared to common techniques such as weight decay and dropout; it also helps maintain more diverse generations. We show that full finetuning learns perturbations with a rank that is 10-100X greater than typical LoRA configurations, possibly explaining some of the reported gaps. We conclude by proposing best practices for finetuning with LoRA.

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/intro.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/learning_curves_all_datasets.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/forgetting_all_datasets.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/pareto_all_datasets.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/regularization_magicoder.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/lora_diversity.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/svd_summary_starcoder_all.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/lr_sweep_main.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/magicoder_human_eval_rank_module.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/metamath_rank_module.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/adam_vs_lion.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/learning_curves_all_loras.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/learn_forget_13b_starcoder_many_metrics.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/sup_forgetting_7b_starcoder.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/sup_forgetting_7b_magicoder.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/sup_forgetting_7b_owm.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/sup_forgetting_7b_metamath.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/learn_forget_Llama-2-7b_starcoder_many_metrics.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/learn_forget_Llama-2-7b_magicoder_many_metrics.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/learn_forget_Llama-2-7b.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/learn_corrs_7b_meta_math.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/single_layer_spectrum_starcoder_cropped.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/x1.png)

![LoRA 精简学习，记忆更牢](../../../paper_images/2405.09673/x2.png)

[Arxiv](https://arxiv.org/abs/2405.09673)