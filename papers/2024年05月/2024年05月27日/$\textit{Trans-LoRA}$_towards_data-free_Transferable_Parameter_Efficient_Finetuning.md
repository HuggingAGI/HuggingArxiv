# 《Trans-LoRA》：探索无需数据支持的高效参数转移微调方法

发布时间：2024年05月27日

`LLM应用

这篇论文探讨了低秩适配器（LoRA）及其变种在大型语言模型（LLM）中的应用，特别是在模型更新换代时如何有效地转移LoRA模块。论文提出了一种名为Trans-LoRA的新方法，该方法利用LLM生成合成数据来实现LoRA模块在不同模型之间的转移，无需原始训练数据。这种方法的应用场景主要集中在LLM的实际应用中，特别是在模型更新和参数微调方面，因此将其归类为LLM应用。` `云计算` `人工智能`

> $\textit{Trans-LoRA}$: towards data-free Transferable Parameter Efficient Finetuning

# 摘要

> 低秩适配器（LoRA）及其变种，作为一种高效的参数微调技术，仅需少量额外参数即可达到全模型微调的性能。然而，当基础模型更新换代时，所有相关的LoRA模块必须重新训练，这需要原始训练数据的支持，这在商业云服务中尤为棘手，因为服务提供商可能无权访问客户的专有数据。为此，我们提出了Trans-LoRA——一种创新的无损、近数据自由的LoRA跨模型转移方法。我们利用大型语言模型生成合成数据，以此来转移LoRA模块至新模型，并在LLama和Gemma模型家族上验证了其有效性。这种方法不仅实现了LoRA在不同模型间的无损转移，还跨越了不同的基础模型家族和PEFT方法，适用于多种任务。

> Low-rank adapters (LoRA) and their variants are popular parameter-efficient fine-tuning (PEFT) techniques that closely match full model fine-tune performance while requiring only a small number of additional parameters. These additional LoRA parameters are specific to the base model being adapted. When the base model needs to be deprecated and replaced with a new one, all the associated LoRA modules need to be re-trained. Such re-training requires access to the data used to train the LoRA for the original base model. This is especially problematic for commercial cloud applications where the LoRA modules and the base models are hosted by service providers who may not be allowed to host proprietary client task data. To address this challenge, we propose $\textit{Trans-LoRA}$ -- a novel method for lossless, nearly data-free transfer of LoRAs across base models. Our approach relies on synthetic data to transfer LoRA modules. Using large language models, we design a synthetic data generator to approximate the data-generating process of the $\textit{observed}$ task data subset. Training on the resulting synthetic dataset transfers LoRA modules to new models. We show the effectiveness of our approach using both LLama and Gemma model families. Our approach achieves lossless (mostly improved) LoRA transfer between models within and across different base model families, and even between different PEFT methods, on a wide variety of tasks.

![《Trans-LoRA》：探索无需数据支持的高效参数转移微调方法](../../../paper_images/2405.17258/x1.png)

![《Trans-LoRA》：探索无需数据支持的高效参数转移微调方法](../../../paper_images/2405.17258/fig2final3.png)

![《Trans-LoRA》：探索无需数据支持的高效参数转移微调方法](../../../paper_images/2405.17258/bbh_llama.png)

![《Trans-LoRA》：探索无需数据支持的高效参数转移微调方法](../../../paper_images/2405.17258/bbh_gemma.png)

![《Trans-LoRA》：探索无需数据支持的高效参数转移微调方法](../../../paper_images/2405.17258/bbh_mixed.png)

![《Trans-LoRA》：探索无需数据支持的高效参数转移微调方法](../../../paper_images/2405.17258/bbh_mixed2.png)

![《Trans-LoRA》：探索无需数据支持的高效参数转移微调方法](../../../paper_images/2405.17258/mmlu_llama.png)

![《Trans-LoRA》：探索无需数据支持的高效参数转移微调方法](../../../paper_images/2405.17258/mmlu_gemma.png)

![《Trans-LoRA》：探索无需数据支持的高效参数转移微调方法](../../../paper_images/2405.17258/mmlu_mixed.png)

![《Trans-LoRA》：探索无需数据支持的高效参数转移微调方法](../../../paper_images/2405.17258/mmlu_mixed2.png)

![《Trans-LoRA》：探索无需数据支持的高效参数转移微调方法](../../../paper_images/2405.17258/abl_sample.png)

[Arxiv](https://arxiv.org/abs/2405.17258)