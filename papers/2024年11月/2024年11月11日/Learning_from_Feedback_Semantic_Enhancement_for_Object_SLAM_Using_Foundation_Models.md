# 从反馈中学习：使用基础模型对对象 SLAM 进行语义增强

发布时间：2024年11月11日

`LLM应用` `室内环境` `语义建图`

> Learning from Feedback: Semantic Enhancement for Object SLAM Using Foundation Models

# 摘要

> 语义同时定位与建图（SLAM）系统难以对近距离的语义相似对象进行建图，特别是在杂乱的室内环境中。我们引入了对象 SLAM 的语义增强（SEO-SLAM），这是一种新颖的 SLAM 系统，利用视觉语言模型（VLMs）和多模态大型语言模型（MLLMs）来增强此类环境中的对象级语义建图。SEO-SLAM 通过（1）使用 MLLMs 生成更具体和描述性的开放词汇对象标签，（2）同时纠正导致错误地标的因素，以及（3）动态更新多类混淆矩阵以减轻对象检测器偏差来解决现有挑战。我们的方法能够更精确地区分相似对象，并通过 MLLM 反馈反映场景变化来保持地图的一致性。我们在具有挑战性的数据集上评估 SEO-SLAM，展示了在具有多个相似对象的环境中提高的准确性和鲁棒性。我们的系统在地标匹配准确性和语义一致性方面优于现有方法。结果表明，来自 MLLM 的反馈改进了以对象为中心的语义建图。我们的数据集可在 jungseokhong.com/SEO-SLAM 公开获取。

> Semantic Simultaneous Localization and Mapping (SLAM) systems struggle to map semantically similar objects in close proximity, especially in cluttered indoor environments. We introduce Semantic Enhancement for Object SLAM (SEO-SLAM), a novel SLAM system that leverages Vision-Language Models (VLMs) and Multimodal Large Language Models (MLLMs) to enhance object-level semantic mapping in such environments. SEO-SLAM tackles existing challenges by (1) generating more specific and descriptive open-vocabulary object labels using MLLMs, (2) simultaneously correcting factors causing erroneous landmarks, and (3) dynamically updating a multiclass confusion matrix to mitigate object detector biases. Our approach enables more precise distinctions between similar objects and maintains map coherence by reflecting scene changes through MLLM feedback. We evaluate SEO-SLAM on our challenging dataset, demonstrating enhanced accuracy and robustness in environments with multiple similar objects. Our system outperforms existing approaches in terms of landmark matching accuracy and semantic consistency. Results show the feedback from MLLM improves object-centric semantic mapping. Our dataset is publicly available at: jungseokhong.com/SEO-SLAM.

[Arxiv](https://arxiv.org/abs/2411.06752)