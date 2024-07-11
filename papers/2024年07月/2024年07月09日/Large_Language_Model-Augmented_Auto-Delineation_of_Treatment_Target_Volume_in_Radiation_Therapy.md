# 大型语言模型助力放射治疗中治疗目标体积的自动勾画

发布时间：2024年07月09日

`LLM应用` `人工智能`

> Large Language Model-Augmented Auto-Delineation of Treatment Target Volume in Radiation Therapy

# 摘要

> 放射治疗（RT）作为癌症治疗的有效手段，其成功关键在于目标的精准描绘。然而，这一过程目前仍依赖于专家的手动操作，不仅耗时费力，还存在观察者间的差异。尽管AI技术在正常组织自动描绘方面取得了显著进展，但RT目标体积的准确描绘仍面临挑战。为此，我们研发了Radformer，一种基于视觉语言模型的自动描绘网络。Radformer采用层次化视觉变换器架构，并融入大型语言模型，从临床数据中提取丰富文本特征。通过视觉语言注意力模块（VLAM），Radformer能有效整合视觉与语言信息，实现语言感知的视觉编码。在包含2985名头颈癌患者的RT数据集上，Radformer的性能通过DSC、IOU和HD95等指标进行了定量评估，结果显示其分割性能优于现有顶尖模型，展现了在RT实践中的广阔应用前景。

> Radiation therapy (RT) is one of the most effective treatments for cancer, and its success relies on the accurate delineation of targets. However, target delineation is a comprehensive medical decision that currently relies purely on manual processes by human experts. Manual delineation is time-consuming, laborious, and subject to interobserver variations. Although the advancements in artificial intelligence (AI) techniques have significantly enhanced the auto-contouring of normal tissues, accurate delineation of RT target volumes remains a challenge. In this study, we propose a visual language model-based RT target volume auto-delineation network termed Radformer. The Radformer utilizes a hierarichal vision transformer as the backbone and incorporates large language models to extract text-rich features from clinical data. We introduce a visual language attention module (VLAM) for integrating visual and linguistic features for language-aware visual encoding (LAVE). The Radformer has been evaluated on a dataset comprising 2985 patients with head-and-neck cancer who underwent RT. Metrics, including the Dice similarity coefficient (DSC), intersection over union (IOU), and 95th percentile Hausdorff distance (HD95), were used to evaluate the performance of the model quantitatively. Our results demonstrate that the Radformer has superior segmentation performance compared to other state-of-the-art models, validating its potential for adoption in RT practice.

[Arxiv](https://arxiv.org/abs/2407.07296)