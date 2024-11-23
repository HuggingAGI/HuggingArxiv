# 一种用于在作者归属方面发挥 LLMs 作用的贝叶斯方法

发布时间：2024年10月29日

`LLM应用` `法医语言学` `作者归属`

> A Bayesian Approach to Harnessing the Power of LLMs in Authorship Attribution

# 摘要

> 作者归属旨在明确一份文件的出处或作者。传统方式高度依赖人工特征，难以捕捉长距离的关联，致使其成效受限。近来的发展借助了预训练语言模型的文本嵌入，这需要在有标注的数据上大量微调，从而在数据依赖和有限的可解释性方面形成难题。具备深度推理能力和维持长距离文本关联能力的大型语言模型（LLMs）提供了颇具前景的替代选择。本研究探索了预训练LLMs在一次性作者归属方面的潜力，尤其运用了贝叶斯方法和LLMs的概率输出。我们的方法计算一段文本涵盖作者以往作品的概率，体现了对作者归属更细腻的理解。仅使用诸如Llama-3-70B这样的预训练模型，我们在IMDb和博客数据集上的成果表明，在针对十位作者的一次性作者分类中，准确率高达令人瞩目的85％。我们的发现为运用LLMs进行一次性作者分析确立了新基准，拓展了这些模型在法医语言学中的应用范畴。此项工作还涵盖了大量的消融研究以验证我们的方法。

> Authorship attribution aims to identify the origin or author of a document. Traditional approaches have heavily relied on manual features and fail to capture long-range correlations, limiting their effectiveness. Recent advancements leverage text embeddings from pre-trained language models, which require significant fine-tuning on labeled data, posing challenges in data dependency and limited interpretability. Large Language Models (LLMs), with their deep reasoning capabilities and ability to maintain long-range textual associations, offer a promising alternative. This study explores the potential of pre-trained LLMs in one-shot authorship attribution, specifically utilizing Bayesian approaches and probability outputs of LLMs. Our methodology calculates the probability that a text entails previous writings of an author, reflecting a more nuanced understanding of authorship. By utilizing only pre-trained models such as Llama-3-70B, our results on the IMDb and blog datasets show an impressive 85\% accuracy in one-shot authorship classification across ten authors. Our findings set new baselines for one-shot authorship analysis using LLMs and expand the application scope of these models in forensic linguistics. This work also includes extensive ablation studies to validate our approach.

[Arxiv](https://arxiv.org/abs/2410.21716)