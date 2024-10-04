# SIEVE：一款通用数据过滤系统，以 GPT-4 成本的 1% 实现同等准确性

发布时间：2024年10月03日

`LLM应用` `数据处理` `人工智能`

> SIEVE: General Purpose Data Filtering System Matching GPT-4o Accuracy at 1% the Cost

# 摘要

> 构建专门的大型语言模型需要海量的干净、特定用途的数据。然而，现有的特定领域数据集寥寥无几，大多数应用都需要创建新数据集。这要求我们开发新的、针对特定应用的网络数据过滤方法。虽然使用高性能的通用LLM（如GPT-4o）进行过滤效果显著，但在大规模应用中成本极高。为此，我们提出了SIEVE，一种轻量级方案，其准确性与GPT-4o相当，但成本仅为后者的几分之一。SIEVE能够以一次GPT-4o调用的成本完成多达500次过滤操作。其核心在于巧妙结合GPT-4o与轻量级T5模型，通过主动学习在后台少量调用GPT-4o来微调T5。训练完成后，SIEVE在极低成本下表现与GPT-4o不相上下。我们在OpenWebText数据集上进行了实验，通过五个高度定制的过滤任务，验证了SIEVE在以1%的成本策划高质量、特定领域数据集方面的有效性和高效性。进一步的实验表明，SIEVE与GPT-4o的准确性相当，且人类评估者更青睐SIEVE的过滤结果。

> Creating specialized large language models requires vast amounts of clean, special purpose data for training and fine-tuning. With only a handful of existing large-scale, domain-specific datasets, creation of new datasets is required in most applications. This requires the development of new application-specific filtering of web-scale data. Filtering with a high-performance, general-purpose LLM such as GPT-4o can be highly effective, but this is extremely expensive at web-scale. This paper proposes SIEVE, a lightweight alternative that matches GPT-4o accuracy at a fraction of the cost. SIEVE can perform up to 500 filtering operations for the cost of one GPT-4o filtering call. The key to SIEVE is a seamless integration of GPT-4o and lightweight T5 models, using active learning to fine-tune T5 in the background with a small number of calls to GPT-4o. Once trained, it performs as well as GPT-4o at a tiny fraction of the cost. We experimentally validate SIEVE on the OpenWebText dataset, using five highly customized filter tasks targeting high quality and domain-specific content. Our results demonstrate the effectiveness and efficiency of our method in curating large, high-quality datasets for language model training at a substantially lower cost (1%) than existing techniques. To further validate SIEVE, experiments show that SIEVE and GPT-4o achieve similar accuracy, with human evaluators preferring SIEVE's filtering results to those of GPT-4o.

[Arxiv](https://arxiv.org/abs/2410.02755)