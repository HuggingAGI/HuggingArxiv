# LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。

发布时间：2024年05月15日

`LLM理论

这篇论文探讨了LoRA（低秩适应技术）在大型语言模型微调中的应用，特别是在节省内存方面的优势，以及它与全微调在不同数据制度下的性能对比。论文还分析了LoRA如何保持模型在非目标任务上的基础性能，以及它与传统正则化技术的差异。这些内容涉及大型语言模型的理论和微调技术，因此属于LLM理论分类。` `数学教育`

> LoRA Learns Less and Forgets Less

# 摘要

> LoRA，一种低秩适应技术，在大型语言模型微调中以节省内存著称。我们对比了LoRA与全微调在编程和数学领域的性能，并探讨了不同数据制度下的表现。尽管LoRA在多数情况下不及全微调，但它能更好地保持模型在非目标任务上的基础性能，显示出其正则化的优势。与传统正则化技术相比，LoRA更能保持生成内容的多样性。全微调产生的扰动秩远高于LoRA，这可能是性能差异的原因之一。最后，我们提出了LoRA微调的最佳实践建议。

> Low-Rank Adaptation (LoRA) is a widely-used parameter-efficient finetuning method for large language models. LoRA saves memory by training only low rank perturbations to selected weight matrices. In this work, we compare the performance of LoRA and full finetuning on two target domains, programming and mathematics. We consider both the instruction finetuning ($\approx$100K prompt-response pairs) and continued pretraining ($\approx$10B unstructured tokens) data regimes. Our results show that, in most settings, LoRA substantially underperforms full finetuning. Nevertheless, LoRA exhibits a desirable form of regularization: it better maintains the base model's performance on tasks outside the target domain. We show that LoRA provides stronger regularization compared to common techniques such as weight decay and dropout; it also helps maintain more diverse generations. We show that full finetuning learns perturbations with a rank that is 10-100X greater than typical LoRA configurations, possibly explaining some of the reported gaps. We conclude by proposing best practices for finetuning with LoRA.

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/intro.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/learning_curves_all_datasets.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/forgetting_all_datasets.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/pareto_all_datasets.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/regularization_magicoder.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/lora_diversity.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/svd_summary_starcoder_all.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/lr_sweep_main.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/magicoder_human_eval_rank_module.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/metamath_rank_module.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/adam_vs_lion.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/learning_curves_all_loras.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/learn_forget_13b_starcoder_many_metrics.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/sup_forgetting_7b_starcoder.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/sup_forgetting_7b_magicoder.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/sup_forgetting_7b_owm.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/sup_forgetting_7b_metamath.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/learn_forget_Llama-2-7b_starcoder_many_metrics.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/learn_forget_Llama-2-7b_magicoder_many_metrics.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/learn_forget_Llama-2-7b.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/learn_corrs_7b_meta_math.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/single_layer_spectrum_starcoder_cropped.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/x1.png)

![LoRA 模型以其高效的学习和记忆保持能力著称，它学得精简，忘得缓慢。](../../../paper_images/2405.09673/x2.png)

[Arxiv](https://arxiv.org/abs/2405.09673)