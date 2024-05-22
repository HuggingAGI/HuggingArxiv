# 探索阿拉伯语中的说服艺术：一项基于大型语言模型的实证研究

发布时间：2024年05月21日

`Agent

这篇论文主要研究了在阿拉伯社交媒体内容中识别说服技巧的方法，使用了预训练语言模型（PLMs）和特定的数据集进行二元分类和多标签分类任务。研究中采用了不同的学习策略，并评估了它们的性能。虽然论文中使用了语言模型，但其核心关注点是通过这些模型来分析和理解社交媒体内容中的说服技巧，这更偏向于应用语言模型作为分析工具，而不是深入探讨语言模型本身的理论或架构。因此，将其归类为Agent，即使用语言模型作为工具来执行特定任务的代理。` `社交媒体`

> Investigating Persuasion Techniques in Arabic: An Empirical Study Leveraging Large Language Models

# 摘要

> 在数字通信和社交媒体盛行的今天，掌握书面文本中的说服技巧变得尤为关键，这有助于我们辨别真伪、做出明智选择。为此，本文深入研究了阿拉伯社交媒体内容中的说服技巧，运用预训练语言模型（PLMs）和ArAlEval数据集，通过二元分类和多标签分类任务，精准识别说服技巧。研究中，我们采用了三种学习策略：特征提取、微调及提示工程，实验结果显示，微调策略在数据集上表现最佳，f1-微观分数达0.865，f1-加权分数为0.861。更有趣的是，尽管GPT模型性能稍逊，但通过少量学习技术，其性能可提升20%，为未来的研究开辟了新视野。

> In the current era of digital communication and widespread use of social media, it is crucial to develop an understanding of persuasive techniques employed in written text. This knowledge is essential for effectively discerning accurate information and making informed decisions. To address this need, this paper presents a comprehensive empirical study focused on identifying persuasive techniques in Arabic social media content. To achieve this objective, we utilize Pre-trained Language Models (PLMs) and leverage the ArAlEval dataset, which encompasses two tasks: binary classification to determine the presence or absence of persuasion techniques, and multi-label classification to identify the specific types of techniques employed in the text. Our study explores three different learning approaches by harnessing the power of PLMs: feature extraction, fine-tuning, and prompt engineering techniques. Through extensive experimentation, we find that the fine-tuning approach yields the highest results on the aforementioned dataset, achieving an f1-micro score of 0.865 and an f1-weighted score of 0.861. Furthermore, our analysis sheds light on an interesting finding. While the performance of the GPT model is relatively lower compared to the other approaches, we have observed that by employing few-shot learning techniques, we can enhance its results by up to 20\%. This offers promising directions for future research and exploration in this topic\footnote{Upon Acceptance, the source code will be released on GitHub.}.

[Arxiv](https://arxiv.org/abs/2405.12884)