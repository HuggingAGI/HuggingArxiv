# 通过视觉-语言模型从图像中推断个人隐私属性

发布时间：2024年04月16日

`LLM应用` `隐私保护` `人工智能安全`

> Private Attribute Inference from Images with Vision-Language Models

# 摘要

> 随着大型语言模型（LLMs）日益融入我们的日常生活和数字化互动，其潜在的隐私风险也日益凸显。尽管LLM的隐私问题研究主要关注模型训练数据的泄露问题，但最新发现显示，随着模型性能的提升，LLMs能够从未见过的文本中准确推断出侵犯隐私的信息。在多模态视觉-语言模型（VLMs）兴起的背景下，这些模型能够理解和处理图像与文本，人们开始关注这些成果是否会扩展到之前未曾研究的在线良性图像领域。为了探究新兴VLMs在图像推理方面的风险，我们汇集了一个图像数据集，其中包含了人工标注的图像所有者个人属性信息。我们的研究重点在于了解VLMs在传统人类属性识别之外可能带来的额外隐私风险，因此数据集中的图像所包含的私人属性并非直接来源于人物描绘。我们对7个顶尖的VLMs进行了推理能力的评估，结果显示它们能够以高达77.6%的准确率推断出多种个人属性。更令人担忧的是，我们发现模型的准确性与其综合能力成正比，这意味着随着模型能力的提升，未来模型可能被滥用为更危险的对手，这迫切要求我们开发出有效的防御措施。

> As large language models (LLMs) become ubiquitous in our daily tasks and digital interactions, associated privacy risks are increasingly in focus. While LLM privacy research has primarily focused on the leakage of model training data, it has recently been shown that the increase in models' capabilities has enabled LLMs to make accurate privacy-infringing inferences from previously unseen texts. With the rise of multimodal vision-language models (VLMs), capable of understanding both images and text, a pertinent question is whether such results transfer to the previously unexplored domain of benign images posted online. To investigate the risks associated with the image reasoning capabilities of newly emerging VLMs, we compile an image dataset with human-annotated labels of the image owner's personal attributes. In order to understand the additional privacy risk posed by VLMs beyond traditional human attribute recognition, our dataset consists of images where the inferable private attributes do not stem from direct depictions of humans. On this dataset, we evaluate the inferential capabilities of 7 state-of-the-art VLMs, finding that they can infer various personal attributes at up to 77.6% accuracy. Concerningly, we observe that accuracy scales with the general capabilities of the models, implying that future models can be misused as stronger adversaries, establishing an imperative for the development of adequate defenses.

[Arxiv](https://arxiv.org/abs/2404.10618)