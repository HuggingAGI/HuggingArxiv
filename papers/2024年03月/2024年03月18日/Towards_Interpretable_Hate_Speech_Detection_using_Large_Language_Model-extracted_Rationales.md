# 致力于借助大型语言模型提取的理据实现对仇恨言论检测的可解释性研究

发布时间：2024年03月18日

`LLM应用` `社交媒体` `仇恨言论检测`

> Towards Interpretable Hate Speech Detection using Large Language Model-extracted Rationales

> 社交媒体虽为用户互动发声的重要舞台，却也因其表面化与匿名性滋生了仇恨言论和冒犯性内容。面对海量社交媒体信息，急需开发自动化工具来识别并标记仇恨言论。目前虽已有多种检测手段，但大多基于黑盒技术，无法直观解读。为此，本文创新性地运用尖端的大型语言模型（LLMs），从输入文本中抽取出具有说服力的理由作为特征，训练基础的仇恨言论分类器，旨在从根本上赋予其可信赖的可解释性。我们构建的框架巧妙融合了LLMs强大的文本理解和前沿仇恨言论分类器的区分能力，确保分类器既准确又易于理解。经过对一系列社交媒体仇恨言论数据集的综合评估，我们发现：(1) LLM抽取的理由质量上乘；(2) 在确保模型具备可解释性的训练过程中，检测器性能仍能出色保持。

> Although social media platforms are a prominent arena for users to engage in interpersonal discussions and express opinions, the facade and anonymity offered by social media may allow users to spew hate speech and offensive content. Given the massive scale of such platforms, there arises a need to automatically identify and flag instances of hate speech. Although several hate speech detection methods exist, most of these black-box methods are not interpretable or explainable by design. To address the lack of interpretability, in this paper, we propose to use state-of-the-art Large Language Models (LLMs) to extract features in the form of rationales from the input text, to train a base hate speech classifier, thereby enabling faithful interpretability by design. Our framework effectively combines the textual understanding capabilities of LLMs and the discriminative power of state-of-the-art hate speech classifiers to make these classifiers faithfully interpretable. Our comprehensive evaluation on a variety of social media hate speech datasets demonstrate: (1) the goodness of the LLM-extracted rationales, and (2) the surprising retention of detector performance even after training to ensure interpretability.

![致力于借助大型语言模型提取的理据实现对仇恨言论检测的可解释性研究](../../../paper_images/2403.12403/llm-hate-speech.png)

![致力于借助大型语言模型提取的理据实现对仇恨言论检测的可解释性研究](../../../paper_images/2403.12403/example-overlap.png)

[Arxiv](https://arxiv.org/abs/2403.12403)