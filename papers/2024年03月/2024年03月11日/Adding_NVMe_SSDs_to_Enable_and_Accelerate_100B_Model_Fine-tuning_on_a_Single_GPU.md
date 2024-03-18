# [为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。]

发布时间：2024年03月11日

`Agent`

> Adding NVMe SSDs to Enable and Accelerate 100B Model Fine-tuning on a Single GPU

> 随着大型语言模型的飞速发展，它们凭借巨量参数展现出强大的功能，但即便是拥有高达80GB显存的顶级GPU，在采用随机梯度下降优化时也无法满足如此庞大的参数存储需求，尤其是在面对学术界预算有限的研究者时，购置多台高端GPU服务器的成本显得尤为高昂。本论文关注如何在一台配置普通的服务器，甚至是低端GPU环境下，让广大AI研究者也能实现大规模模型的微调。现有尖端技术ZeRO-Infinity在这样的环境中遇到两大难题：GPU利用率因交换效率低下而降低，以及受制于CPU内存容量限制了可训练模型的规模。究其原因，ZeRO-Infinity主要针对高端GPU服务器做了优化。因此，我们创新性地提出了一种名为Fuyou的低成本训练框架，它能够在配备低端GPU且CPU内存资源有限的普通服务器上高效地对千亿参数级别的大型模型进行微调，秘诀就在于巧妙地将SSD-CPU通信融入系统化的优化方案中，以提高GPU利用率为目标，精细协调计算与数据交换过程。实验证明，Fuyou能够在消费级GPU RTX 4090上有效率地对1750亿参数的GPT-3模型进行微调，而相比之下ZeRO-Infinity却无法顺利完成此任务；此外，在训练规模相对较小的130亿参数GPT-3模型时，Fuyou可在RTX 4090 GPU上实现156 TFLOPS的高性能，远超ZeRO-Infinity的45 TFLOPS表现。

> Recent advances in large language models have brought immense value to the world, with their superior capabilities stemming from the massive number of parameters they utilize. However, even the GPUs with the highest memory capacities, currently peaking at 80GB, are far from sufficient to accommodate these vast parameters and their associated optimizer states when conducting stochastic gradient descent-based optimization. One approach to hosting such huge models is to aggregate device memory from many GPUs. However, this approach introduces prohibitive costs for most academic researchers, who always have a limited budget for many high-end GPU servers. In this paper, we focus on huge model fine-tuning on a single, even low-end, GPU in a commodity server, which is accessible to most AI researchers. In such a scenario, the state-of-the-art work ZeRO-Infinity suffers from two severe issues when running in a commodity server: 1) low GPU utilization due to inefficient swapping, and 2) limited trainable model size due to CPU memory capacity. The underlying reason is that ZeRO-Infinity is optimized for running on high-end GPU servers. To this end, we present Fuyou, a low-cost training framework that enables efficient 100B huge model fine-tuning on a low-end server with a low-end GPU and limited CPU memory capacity. The key idea is to add the SSD-CPU communication as an optimization dimension and thus carefully co-optimize computation and data swapping from a systematic approach to maximize GPU utilization. The experimental results show that 1) Fuyou is able to fine-tune 175B GPT-3 on a consumer GPU RTX 4090 with high GPU utilization, while ZeRO-Infinity fails to fine-tune; and 2) when training a small GPT-3 13B model, Fuyou achieves 156 TFLOPS on an RTX 4090 GPU while ZeRO-Infinity only achieves 45 TFLOPS.

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/max_model_size_zero.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/overall_gpu_util.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/opt_prop.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/origin_pipe.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/ratel_pipe.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/ratel_pipe_parallel.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/system_overview.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/max_model_size.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/overall_tp_175b.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/overall_tp_a100_13b.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/overall_tp_4090_13b.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/overall_bigger_model.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/rearr.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/rearr_175b.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/pipeline_a100.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/pipeline_4090.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/swap_coefficient.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/throughput_dollars.png)

![为了在单个GPU上有效且高效地进行百亿模型的微调，我们引入了NVMe SSD技术。这一举措旨在助力并大幅提升大型模型在单一GPU环境下的微调速度。](../../../paper_images/2403.06504/throughput_dollars_full.png)

[Arxiv](https://arxiv.org/abs/2403.06504)