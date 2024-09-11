# MIP-GAF：一个专为最重要人物定位和群体上下文理解设计的 MLLM 注释基准

发布时间：2024年09月10日

`LLM应用` `社交分析` `计算机视觉`

> MIP-GAF: A MLLM-annotated Benchmark for Most Important Person Localization and Group Context Understanding

# 摘要

> 在社交活动中识别“最重要的人 (MIP)”极具挑战，主要因上下文复杂和标签数据稀缺。MIP 的因果关系也相当主观多样。为此，我们注释了大规模“野外”数据集，以捕捉人们对图像中 MIP 的看法。本文详述了基于多模态大型语言模型 (MLLM) 的注释策略及数据质量分析。我们还用最先进的 MIP 定位方法对数据集进行了基准测试，发现性能显著下降，表明现有算法在“野外”场景中需更稳健。我们相信，此数据集将推动下一代社交情境理解方法的发展。代码和数据已公开，详见 https://github.com/surbhimadan92/MIP-GAF。

> Estimating the Most Important Person (MIP) in any social event setup is a challenging problem mainly due to contextual complexity and scarcity of labeled data. Moreover, the causality aspects of MIP estimation are quite subjective and diverse. To this end, we aim to address the problem by annotating a large-scale `in-the-wild' dataset for identifying human perceptions about the `Most Important Person (MIP)' in an image. The paper provides a thorough description of our proposed Multimodal Large Language Model (MLLM) based data annotation strategy, and a thorough data quality analysis. Further, we perform a comprehensive benchmarking of the proposed dataset utilizing state-of-the-art MIP localization methods, indicating a significant drop in performance compared to existing datasets. The performance drop shows that the existing MIP localization algorithms must be more robust with respect to `in-the-wild' situations. We believe the proposed dataset will play a vital role in building the next-generation social situation understanding methods. The code and data is available at https://github.com/surbhimadan92/MIP-GAF.

[Arxiv](https://arxiv.org/abs/2409.06224)