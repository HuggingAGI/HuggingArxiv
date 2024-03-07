# [DIVERSE 是一个创新的基准数据集，它专注于通过分析视频评论中的立场来解读网络舆论中关于美国军事的不同观点，为 stance 分类任务提供了有力支持。](https://arxiv.org/abs/2403.03334)

发布时间：2024年03月05日

`Agent`

> DIVERSE: Deciphering Internet Views on the U.S. Military Through Video Comment Stance Analysis, A Novel Benchmark Dataset for Stance Classification

> 在疫苗接种等热议话题中识别不同观点群体的社会媒体文本态度检测是一项关键任务，其中态度揭示了对某一主题的观点倾向。本文介绍了一个名为DIVERSE的数据集，它包含了超173,000条 YouTube 视频评论，并标注了这些评论对美国军方相关视频的态度。与众不同的是，这项研究采用人机协作标注法，借助于文本内部的弱信号（如仇恨言论、讽刺表达、特定关键词以及大语言模型推断出的情感倾向）来辅助标注，而非单纯依靠人工逐一标注。这些弱信号经过数据编程模型综合处理后，为每条评论确定最终的态度标签。通常情况下，每个视频平均拥有约200条评论，且无论是关于美国陆军还是该频道发布的视频，评论整体上呈现出略微倾向于“反对”的态度特征。

> Stance detection of social media text is a key component of downstream tasks involving the identification of groups of users with opposing opinions on contested topics such as vaccination and within arguments. In particular, stance provides an indication of an opinion towards an entity. This paper introduces DIVERSE, a dataset of over 173,000 YouTube video comments annotated for their stance towards videos of the U.S. military. The stance is annotated through a human-guided, machine-assisted labeling methodology that makes use of weak signals of tone within the sentence as supporting indicators, as opposed to using manual annotations by humans. These weak signals consist of the presence of hate speech and sarcasm, the presence of specific keywords, the sentiment of the text, and the stance inference from two Large Language Models. The weak signals are then consolidated using a data programming model before each comment is annotated with a final stance label. On average, the videos have 200 comments each, and the stance of the comments skews slightly towards the "against" characterization for both the U.S. Army and the videos posted on the channel.