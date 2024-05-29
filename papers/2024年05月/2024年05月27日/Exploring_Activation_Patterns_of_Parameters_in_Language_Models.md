# 揭示语言模型参数的激活奥秘

发布时间：2024年05月27日

`LLM理论

这篇论文主要关注大型语言模型（LLM）内部机制的理解，特别是模型参数的激活程度及其与输入数据的关系。通过提出一种基于梯度的度量方法，研究了模型参数在不同层级和不同输入类型下的激活模式，并进行了实验验证。这些发现有助于深入理解LLM的工作原理，属于理论研究范畴，因此应归类为LLM理论。` `模型优化`

> Exploring Activation Patterns of Parameters in Language Models

# 摘要

> 大多数研究将大型语言模型视为黑箱，对其内部机制知之甚少。为此，我们提出了一种基于梯度的度量，用以评估模型参数的激活程度，并据此得出了三个关键发现。首先，同一领域的输入会使浅层参数密集激活，而深层参数则激活稀疏。其次，跨领域输入时，浅层参数的激活模式比深层更为相似。最后，深层中激活参数的分布相似性与数据相关性正相关。为了验证这些发现，我们进行了三项实验：首先，通过为不同层设置不同剪枝比例，我们发现这能优化模型剪枝效果。其次，基于特定校准集剪枝的模型在处理相关任务时表现更佳。最后，在STS-B和SICK基准测试中，我们观察到语义一致的句子在深层共享相似的参数激活模式。我们的研究不仅揭示了LLMs中参数激活的特性，还期望这些发现能激发更多实际应用的创新。

> Most work treats large language models as black boxes without in-depth understanding of their internal working mechanism. In order to explain the internal representations of LLMs, we propose a gradient-based metric to assess the activation level of model parameters. Based on this metric, we obtain three preliminary findings. (1) When the inputs are in the same domain, parameters in the shallow layers will be activated densely, which means a larger portion of parameters will have great impacts on the outputs. In contrast, parameters in the deep layers are activated sparsely. (2) When the inputs are across different domains, parameters in shallow layers exhibit higher similarity in the activation behavior than deep layers. (3) In deep layers, the similarity of the distributions of activated parameters is positively correlated to the empirical data relevance. Further, we develop three validation experiments to solidify these findings. (1) Firstly, starting from the first finding, we attempt to configure different prune ratios for different layers, and find this method can benefit model pruning. (2) Secondly, we find that a pruned model based on one calibration set can better handle tasks related to the calibration task than those not related, which validate the second finding. (3) Thirdly, Based on the STS-B and SICK benchmark, we find that two sentences with consistent semantics tend to share similar parameter activation patterns in deep layers, which aligns with our third finding. Our work sheds light on the behavior of parameter activation in LLMs, and we hope these findings will have the potential to inspire more practical applications.

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/0.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/1.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/8.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/15.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/23.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/30.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/0.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/1.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/8.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/15.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/23.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/30.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/0.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/1.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/8.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/15.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/23.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/30.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/boolq_boolq.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/mmlu_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/he_he.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/mmlu_boolq.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/he_boolq.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/mmlu_he.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama_7b_mmlu_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/qwen_7b_mmlu_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_13b_mmlu_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama_7b_humaneval_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/qwen_7b_humaneval_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_13b_humaneval_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/corelation.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/0.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/1.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/2.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/3.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/4.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/5.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/6.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/7.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/8.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/9.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/10.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/11.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/12.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/13.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/14.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/15.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/16.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/17.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/18.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/19.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/20.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/21.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/22.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/23.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/24.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/25.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/26.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/27.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/28.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/29.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/30.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/31.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/0.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/1.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/2.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/3.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/4.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/5.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/6.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/7.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/8.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/9.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/10.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/11.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/12.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/13.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/14.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/15.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/16.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/17.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/18.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/19.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/20.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/21.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/22.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/23.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/24.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/25.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/26.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/27.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/28.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/29.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/30.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/31.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/0.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/1.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/2.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/3.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/4.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/5.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/6.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/7.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/8.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/9.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/10.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/11.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/12.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/13.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/14.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/15.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/16.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/17.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/18.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/19.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/20.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/21.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/22.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/23.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/24.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/25.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/26.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/27.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/28.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/29.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/30.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/31.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_humaneval_hellaswag.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_wikitext2_humaneval.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_piqa_piqa.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_c4_hellaswag.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_piqa_hellaswag.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_wikitext2_boolq.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_humaneval_gsm8k.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_siqa_boolq.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_mmlu_boolq.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_hellaswag_boolq.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_siqa_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_piqa_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_gsm8k_gsm8k.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_c4_gsm8k.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_humaneval_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_gsm8k_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_wikitext2_wikitext2.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_c4_c4.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_wikitext2_siqa.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_c4_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_wikitext2_c4.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_piqa_gsm8k.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_hellaswag_hellaswag.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_c4_siqa.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_wikitext2_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_gsm8k_siqa.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_humaneval_siqa.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_wikitext2_gsm8k.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_humaneval_boolq.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_piqa_siqa.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_wikitext2_hellaswag.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_siqa_siqa.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_gsm8k_hellaswag.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_humaneval_humaneval.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_mmlu_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_wikitext2_piqa.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_siqa_hellaswag.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_c4_boolq.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_piqa_humaneval.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_gsm8k_boolq.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_boolq_boolq.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_c4_humaneval.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_hellaswag_mmlu.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_piqa_boolq.png)

![揭示语言模型参数的激活奥秘](../../../paper_images/2405.17799/llama2_7b_piqa_c4.png)

[Arxiv](https://arxiv.org/abs/2405.17799)