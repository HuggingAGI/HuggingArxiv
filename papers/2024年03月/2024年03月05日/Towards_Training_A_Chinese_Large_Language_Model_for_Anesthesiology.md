# [致力于训练适用于麻醉学领域的大型中文语言模型]

发布时间：2024年03月05日

`LLM应用`

> Towards Training A Chinese Large Language Model for Anesthesiology

> 随着医疗LLMs因其强大的实用性崭露头角，近期它们备受瞩目。然而，当前的研究重心多集中于普通医学领域，针对如麻醉学这类特定领域的LLMs深入探究显得尤为必要。为此，我们推出了Hypnos——一个建立在现有LLMs（如Llama）基础之上的中国麻醉模型。Hypnos的核心价值体现在三方面：首先，在数据优化上，鉴于当前LLMs自动生成数据可能存在误差，Hypnos采用交叉过滤技术提升数据质量，即通过一个LLM评判另一个LLM生成数据的优劣并剔除不合格数据。其次，在训练策略上，Hypnos采取由广至深的方式，先运用一般医学数据对LLMs进行微调，然后进一步借助麻醉学专有数据优化微调后的模型，这样既丰富了麻醉学专业知识，也有效提升了模型生成内容的准确性。最后，我们构建了一套标准化麻醉学医疗LLM评估基准，该基准集合了网上公开数据和医院内部真实案例。在与GPT-4及其他医疗LLMs对比时，Hypnos在基准测试集的各项指标以及人工评价中均展现出卓越性能，尤其是在麻醉学领域。

> Medical large language models (LLMs) have gained popularity recently due to their significant practical utility. However, most existing research focuses on general medicine, and there is a need for in-depth study of LLMs in specific fields like anesthesiology. To fill the gap, we introduce Hypnos, a Chinese Anesthesia model built upon existing LLMs, e.g., Llama. Hypnos' contributions have three aspects: 1) The data, such as utilizing Self-Instruct, acquired from current LLMs likely includes inaccuracies. Hypnos implements a cross-filtering strategy to improve the data quality. This strategy involves using one LLM to assess the quality of the generated data from another LLM and filtering out the data with low quality. 2) Hypnos employs a general-to-specific training strategy that starts by fine-tuning LLMs using the general medicine data and subsequently improving the fine-tuned LLMs using data specifically from Anesthesiology. The general medical data supplement the medical expertise in Anesthesiology and enhance the effectiveness of Hypnos' generation. 3) We introduce a standardized benchmark for evaluating medical LLM in Anesthesiology. Our benchmark includes both publicly available instances from the Internet and privately obtained cases from the Hospital. Hypnos outperforms other medical LLMs in anesthesiology in metrics, GPT-4, and human evaluation on the benchmark dataset.

[Arxiv](https://arxiv.org/abs/2403.02742)