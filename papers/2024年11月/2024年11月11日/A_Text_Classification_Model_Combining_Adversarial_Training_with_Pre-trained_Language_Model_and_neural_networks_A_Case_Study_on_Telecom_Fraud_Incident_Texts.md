# 一个将对抗训练与预训练语言模型和神经网络相结合的文本分类模型：关于电信诈骗事件文本的案例研究

发布时间：2024年11月11日

`LLM应用` `电信诈骗` `公共安全`

> A Text Classification Model Combining Adversarial Training with Pre-trained Language Model and neural networks: A Case Study on Telecom Fraud Incident Texts

# 摘要

> 一线警察经常将所有报警的电信诈骗案件归类为 14 个子类别，以促进有针对性的预防措施，例如精准的公共教育。然而，相关数据具有量大、信息内容多样和表达变化的特点。目前，缺乏高效准确的智能模型来取代人工分类，人工分类虽然精确，但效率相对较低。为了应对这些挑战，本文提出了一种将对抗训练与预训练语言模型和神经网络相结合的文本分类模型。具有语言动机的预训练语言模型提取三种语言特征，然后利用快速梯度法算法扰动生成的嵌入层。随后，双向长短期记忆和卷积神经网络分别提取上下文句法信息和局部语义信息。当在运营部门提供的一部分电信诈骗案件数据上进行训练时，该模型实现了 83.9％的分类准确率。本文建立的模型已在运营部门部署，节省了大量人力，并提高了该部门打击电信诈骗犯罪的效率。此外，考虑到本文建立的模型的通用性，其他应用场景有待进一步探索。

> Front-line police officers often categorize all police call reported cases of Telecom Fraud into 14 subcategories to facilitate targeted prevention measures, such as precise public education. However, the associated data is characterized by its large volume, diverse information content, and variations in expression. Currently, there is a lack of efficient and accurate intelligent models to replace manual classification, which, while precise, is relatively inefficient. To address these challenges, this paper proposes a text classification model that combines adversarial training with Pre-trained Language Model and neural networks. The Linguistically-motivated Pre-trained Language Model model extracts three types of language features and then utilizes the Fast Gradient Method algorithm to perturb the generated embedding layer. Subsequently, the Bi-directional Long Short-Term Memory and Convolutional Neural Networks networks extract contextual syntactic information and local semantic information, respectively. The model achieved an 83.9% classification accuracy when trained on a portion of telecom fraud case data provided by the operational department. The model established in this paper has been deployed in the operational department, freeing up a significant amount of manpower and improving the department's efficiency in combating Telecom Fraud crimes. Furthermore, considering the universality of the model established in this paper, other application scenarios await further exploration.

[Arxiv](https://arxiv.org/abs/2411.06772)