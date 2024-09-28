# BeanCounter 是一个低毒性、大规模且开放的商业文本数据集。

发布时间：2024年09月26日

`LLM应用` `数据集`

> BeanCounter: A low-toxicity, large-scale, and open dataset of business-oriented text

# 摘要

> 近期语言建模的突破多来自将相同模型架构扩展至更大数据集。最新研究指出，增加训练数据规模与质量能显著提升性能，这呼唤着新的大规模数据集。我们推出了 BeanCounter，一个包含 1590 亿标记的企业披露数据集。数据显示，BeanCounter 新颖性十足：不到 0.1% 内容与 Common Crawl 数据集重叠，规模更是同类数据集的十倍。基于数据来源，我们推测 BeanCounter 事实性更强、毒性更低。研究发现，BeanCounter 中各类身份出现频率与其他数据集相当，但毒性环境显著减少。为验证其效用，我们对比了在 BeanCounter 上持续预训练的 LLM 与基础模型，结果显示毒性生成减少 18-33%，金融领域表现提升。综上，BeanCounter 是训练数十亿参数 LLM 的理想之选，提供低毒性、高质量、特定领域数据。

> Many of the recent breakthroughs in language modeling have resulted from scaling effectively the same model architecture to larger datasets. In this vein, recent work has highlighted performance gains from increasing training dataset size and quality, suggesting a need for novel sources of large-scale datasets. In this work, we introduce BeanCounter, a public dataset consisting of more than 159B tokens extracted from businesses' disclosures. We show that this data is indeed novel: less than 0.1% of BeanCounter appears in Common Crawl-based datasets and it is an order of magnitude larger than datasets relying on similar sources. Given the data's provenance, we hypothesize that BeanCounter is comparatively more factual and less toxic than web-based datasets. Exploring this hypothesis, we find that many demographic identities occur with similar prevalence in BeanCounter but with significantly less toxic context relative to other datasets. To demonstrate the utility of BeanCounter, we evaluate and compare two LLMs continually pre-trained on BeanCounter with their base models. We find an 18-33% reduction in toxic generation and improved performance within the finance domain for the continually pretrained models. Collectively, our work suggests that BeanCounter is a novel source of low-toxicity and high-quality domain-specific data with sufficient scale to train multi-billion parameter LLMs.

[Arxiv](https://arxiv.org/abs/2409.17827)