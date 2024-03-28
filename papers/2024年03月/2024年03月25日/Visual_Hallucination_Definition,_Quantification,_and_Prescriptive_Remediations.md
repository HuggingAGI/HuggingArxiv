# 视觉幻觉是指在没有相应外部刺激的情况下，人脑产生的虚假视觉体验。对这种现象的量化研究有助于我们更好地理解其产生机制，并为制定有效的干预措施提供依据。

发布时间：2024年03月25日

`RAG` `视觉-语言模型` `幻觉检测
</example>`

> Visual Hallucination: Definition, Quantification, and Prescriptive Remediations

# 摘要

> 幻觉现象的增加或许成为了推动负责任AI发展的最大障碍。近期，众多研究致力于发现和缓解大型语言模型（LLMs）中的幻觉问题。然而，值得注意的是，在视觉-语言模型（VLMs）中，幻觉问题同样普遍存在。本文细致探讨了基于两项任务的VLM幻觉特征分析：一是图像描述，二是视觉问答（VQA）。我们明确了视觉幻觉的八种细致类型：一是情境推测，二是身份不匹配，三是地域性错误，四是视觉幻象，五是性别偏差，六是VLM作为分类器，七是误读，八是数值差异。我们编制了视觉幻觉诱导数据集（VHILT），这是一个公共数据集，包含2000个样本，这些样本由八种VLM在图像描述和视觉问答任务中生成，并附有人类对前述类别的标注。

> The troubling rise of hallucination presents perhaps the most significant impediment to the advancement of responsible AI. In recent times, considerable research has focused on detecting and mitigating hallucination in Large Language Models (LLMs). However, it's worth noting that hallucination is also quite prevalent in Vision-Language models (VLMs). In this paper, we offer a fine-grained discourse on profiling VLM hallucination based on two tasks: i) image captioning, and ii) Visual Question Answering (VQA). We delineate eight fine-grained orientations of visual hallucination: i) Contextual Guessing, ii) Identity Incongruity, iii) Geographical Erratum, iv) Visual Illusion, v) Gender Anomaly, vi) VLM as Classifier, vii) Wrong Reading, and viii) Numeric Discrepancy. We curate Visual HallucInation eLiciTation (VHILT), a publicly available dataset comprising 2,000 samples generated using eight VLMs across two tasks of captioning and VQA along with human annotations for the categories as mentioned earlier.

[Arxiv](https://arxiv.org/abs/2403.17306)