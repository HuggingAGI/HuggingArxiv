# 有害 YouTube 视频检测：在线危害分类及 MLLMs 充当替代标注员

发布时间：2024年11月06日

`LLM应用` `短视频` `网络安全`

> Harmful YouTube Video Detection: A Taxonomy of Online Harm and MLLMs as Alternative Annotators

# 摘要

> 像 YouTube、Instagram 或 TikTok 这样的短视频平台，在全球拥有数十亿用户。然而，这些平台会让用户接触到有害内容，像诱导点击、身体伤害、错误信息、网络仇恨等。但由于对危害的界定不一致，加上人工标注资源有限且耗费精力，检测有害视频颇具挑战。为此，本研究推出了检测视频内容危害的举措和方法。其一，我们为视频平台上的网络危害构建了一个全面的分类体系，将其划分为六类：信息类、仇恨与骚扰类、成瘾类、诱导点击类、性相关类和身体伤害类。其二，我们把多模态大型语言模型当作有害视频的可靠标注者。我们用 14 个图像帧、1 个缩略图和文本元数据对 19422 个 YouTube 视频进行了分析，并将众包工作者（Mturk）和 GPT-4-Turbo 的准确性与领域专家的标注（作为黄金标准）作对比。结果显示，在二分类（有害和无害）及多标签危害分类任务中，GPT-4-Turbo 都比众包工作者表现出色。在方法层面，本研究把大型语言模型的应用拓展到了文本标注和二分类之外的多标签和多模态场景。实际上，我们的研究有助于减轻网络危害，为视频平台上有害内容的定义和识别提供了指导。

> Short video platforms, such as YouTube, Instagram, or TikTok, are used by billions of users globally. These platforms expose users to harmful content, ranging from clickbait or physical harms to misinformation or online hate. Yet, detecting harmful videos remains challenging due to an inconsistent understanding of what constitutes harm and limited resources and mental tolls involved in human annotation. As such, this study advances measures and methods to detect harm in video content. First, we develop a comprehensive taxonomy for online harm on video platforms, categorizing it into six categories: Information, Hate and harassment, Addictive, Clickbait, Sexual, and Physical harms. Next, we establish multimodal large language models as reliable annotators of harmful videos. We analyze 19,422 YouTube videos using 14 image frames, 1 thumbnail, and text metadata, comparing the accuracy of crowdworkers (Mturk) and GPT-4-Turbo with domain expert annotations serving as the gold standard. Our results demonstrate that GPT-4-Turbo outperforms crowdworkers in both binary classification (harmful vs. harmless) and multi-label harm categorization tasks. Methodologically, this study extends the application of LLMs to multi-label and multi-modal contexts beyond text annotation and binary classification. Practically, our study contributes to online harm mitigation by guiding the definitions and identification of harmful content on video platforms.

[Arxiv](https://arxiv.org/abs/2411.05854)