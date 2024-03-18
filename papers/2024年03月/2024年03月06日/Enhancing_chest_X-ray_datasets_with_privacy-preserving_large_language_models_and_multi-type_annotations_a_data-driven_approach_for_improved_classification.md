# [我们提出了一种数据驱动的方案，利用隐私保护的大规模语言模型及多元注解技术来提升胸部X射线数据集的质量，从而实现更精确的分类效果。]

发布时间：2024年03月06日

`LLM应用`

> Enhancing chest X-ray datasets with privacy-preserving large language models and multi-type annotations: a data-driven approach for improved classification

> 在CXR图像分析领域，以往依赖规则系统的标签提取常受到准确度质疑，且此类数据集仅提供基础的存在与否标签及少量不确定性信息，实用性受限。本研究引入创新方案MAPLEZ，运用本地高效执行的大规模语言模型(LLM)，从CXR报告中精准抽取并优化发现类别的标签，不仅涵盖发现的有无，还包括发现的具体位置、严重程度及放射科医师对此的判断不确定度。我们在五个测试集中的八种异常病状上验证了MAPLEZ的有效性，其在类别存在注释的F1评分上提升了5个百分点，而在位置注释的F1评分上更超越竞品高达30多个百分点。进一步地，将这些升级版注释应用于分类模型训练，我们成功推动模型品质跃升，AUROC值较之前沿方法训练出的模型增长了1.7个百分点。我们已公开相关代码和注释资源。

> In chest X-ray (CXR) image analysis, rule-based systems are usually employed to extract labels from reports, but concerns exist about label quality. These datasets typically offer only presence labels, sometimes with binary uncertainty indicators, which limits their usefulness. In this work, we present MAPLEZ (Medical report Annotations with Privacy-preserving Large language model using Expeditious Zero shot answers), a novel approach leveraging a locally executable Large Language Model (LLM) to extract and enhance findings labels on CXR reports. MAPLEZ extracts not only binary labels indicating the presence or absence of a finding but also the location, severity, and radiologists' uncertainty about the finding. Over eight abnormalities from five test sets, we show that our method can extract these annotations with an increase of 5 percentage points (pp) in F1 score for categorical presence annotations and more than 30 pp increase in F1 score for the location annotations over competing labelers. Additionally, using these improved annotations in classification supervision, we demonstrate substantial advancements in model quality, with an increase of 1.7 pp in AUROC over models trained with annotations from the state-of-the-art approach. We share code and annotations.

[Arxiv](https://arxiv.org/abs/2403.04024)