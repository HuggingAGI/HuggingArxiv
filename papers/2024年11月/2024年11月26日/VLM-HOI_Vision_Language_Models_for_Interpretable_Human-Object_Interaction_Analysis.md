# VLM-HOI：用于可解释的人-物交互分析的视觉语言模型

发布时间：2024年11月26日

`LLM应用` `计算机视觉` `人机交互`

> VLM-HOI: Vision Language Models for Interpretable Human-Object Interaction Analysis

# 摘要

> 大型视觉语言模型（VLM）近来在融合两种基础模态方面进展显著。经足够大规模数据集训练的 VLM，对视觉和语言有着全面的理解，能够执行各类任务。为精准提炼此知识，本文引入了一种创新方法，明确将 VLM 作为人类-对象交互（HOI）检测任务（	extbf{VLM-HOI}）的目标函数形式。具体而言，我们提出了运用图像-文本匹配技术来量化预测的 HOI 三元组相似度的方法。我们以语言形式呈现 HOI 三元组，充分利用 VLM 的语言理解能力，因其具有本地化和以对象为中心的特性，比 CLIP 模型更适用。此匹配分数用作对比优化的目标。据我们所知，这是首次将 VLM 的语言能力用于 HOI 检测。实验表明我们的方法行之有效，在基准测试中达成了最先进的 HOI 检测准确率。我们认为将 VLM 融入 HOI 检测，是朝着更高级且可解释的人类-对象交互分析迈进的重要一步。

> The Large Vision Language Model (VLM) has recently addressed remarkable progress in bridging two fundamental modalities. VLM, trained by a sufficiently large dataset, exhibits a comprehensive understanding of both visual and linguistic to perform diverse tasks. To distill this knowledge accurately, in this paper, we introduce a novel approach that explicitly utilizes VLM as an objective function form for the Human-Object Interaction (HOI) detection task (\textbf{VLM-HOI}). Specifically, we propose a method that quantifies the similarity of the predicted HOI triplet using the Image-Text matching technique. We represent HOI triplets linguistically to fully utilize the language comprehension of VLMs, which are more suitable than CLIP models due to their localization and object-centric nature. This matching score is used as an objective for contrastive optimization. To our knowledge, this is the first utilization of VLM language abilities for HOI detection. Experiments demonstrate the effectiveness of our method, achieving state-of-the-art HOI detection accuracy on benchmarks. We believe integrating VLMs into HOI detection represents important progress towards more advanced and interpretable analysis of human-object interactions.

[Arxiv](https://arxiv.org/abs/2411.18038)