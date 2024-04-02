# 语言模型真的能辨识出令人信服的论证吗？

发布时间：2024年03月31日

`LLM应用` `信息安全` `人工智能伦理`

> Can Language Models Recognize Convincing Arguments?

# 摘要

> 随着大型语言模型（LLMs）的能力日益增强，人们对其可能被用于制造具有误导性、极具说服力的虚假信息和宣传的担忧也在增加。为了探究LLMs的说服力而不直接涉及人类实验，我们通过研究它们在检测有说服力论点任务上的表现来获得洞察。我们扩充了Durmus & Cardie（2018）的现有数据集，加入了辩论内容、投票数据和用户特征，并设计了三个任务来衡量LLMs：（1）辨别论点的强弱，（2）依据信仰和人口统计学特征预测立场，（3）根据个人特征评估论点的吸引力。研究显示，LLMs在这些任务上的表现与人类持平，通过整合多个LLMs的预测，性能提升显著，甚至在某些方面超越了人类。本文发布的数据和代码旨在支持对LLMs不断演变的能力及其潜在影响的持续评估与监控工作。

> The remarkable and ever-increasing capabilities of Large Language Models (LLMs) have raised concerns about their potential misuse for creating personalized, convincing misinformation and propaganda. To gain insights into LLMs' persuasive capabilities without directly engaging in experimentation with humans, we propose studying their performance on the related task of detecting convincing arguments. We extend a dataset by Durmus & Cardie (2018) with debates, votes, and user traits and propose tasks measuring LLMs' ability to (1) distinguish between strong and weak arguments, (2) predict stances based on beliefs and demographic characteristics, and (3) determine the appeal of an argument to an individual based on their traits. We show that LLMs perform on par with humans in these tasks and that combining predictions from different LLMs yields significant performance gains, even surpassing human performance. The data and code released with this paper contribute to the crucial ongoing effort of continuously evaluating and monitoring the rapidly evolving capabilities and potential impact of LLMs.

![语言模型真的能辨识出令人信服的论证吗？](../../../paper_images/2404.00750/x1.png)

![语言模型真的能辨识出令人信服的论证吗？](../../../paper_images/2404.00750/q1-prompt.png)

![语言模型真的能辨识出令人信服的论证吗？](../../../paper_images/2404.00750/x2.png)

![语言模型真的能辨识出令人信服的论证吗？](../../../paper_images/2404.00750/q2-prompt.png)

![语言模型真的能辨识出令人信服的论证吗？](../../../paper_images/2404.00750/q3-prompt.png)

[Arxiv](https://arxiv.org/abs/2404.00750)