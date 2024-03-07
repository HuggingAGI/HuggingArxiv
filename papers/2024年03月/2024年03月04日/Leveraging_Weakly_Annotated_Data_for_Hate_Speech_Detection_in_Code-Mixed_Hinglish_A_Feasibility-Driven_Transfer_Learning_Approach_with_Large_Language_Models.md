# [针对混合语种 Hinglish 中的仇恨言论检测问题，我们提出了一种以可行性为导向的迁移学习策略，充分利用弱标注数据，并结合大型语言模型的力量。](https://arxiv.org/abs/2403.02121)

发布时间：2024年03月04日

`LLM应用`

> Leveraging Weakly Annotated Data for Hate Speech Detection in Code-Mixed Hinglish: A Feasibility-Driven Transfer Learning Approach with Large Language Models

> 随着LLMs的兴起，各类NLP任务的基准得以显著提升，但训练它们需依赖大量带有标签的数据，而标注和训练过程既耗算力也耗时间。为此，零样本和少量样本学习技术借助大规模预训练模型，成为了高效标注数据的新兴方案。在低资源混合编码语境下的仇恨言论检测这一活跃问题领域，LLMs的应用带来了积极效果。本研究汇编了一组包含100条YouTube评论的数据集，通过弱标注方式对其中的粗细粒度厌女内容进行了分类（鉴于标注工作的繁重性）。随后，我们运用零样本、一次样本及少量样本学习技术以及提示引导策略来为评论自动分配标签，并与人工标注结果对比。实验结果显示，在所有方法中，采用BART大型模型进行零样本分类，以及运用GPT-3进行的少量样本提示引导策略获得了最优性能。

> The advent of Large Language Models (LLMs) has advanced the benchmark in various Natural Language Processing (NLP) tasks. However, large amounts of labelled training data are required to train LLMs. Furthermore, data annotation and training are computationally expensive and time-consuming. Zero and few-shot learning have recently emerged as viable options for labelling data using large pre-trained models. Hate speech detection in mix-code low-resource languages is an active problem area where the use of LLMs has proven beneficial. In this study, we have compiled a dataset of 100 YouTube comments, and weakly labelled them for coarse and fine-grained misogyny classification in mix-code Hinglish. Weak annotation was applied due to the labor-intensive annotation process. Zero-shot learning, one-shot learning, and few-shot learning and prompting approaches have then been applied to assign labels to the comments and compare them to human-assigned labels. Out of all the approaches, zero-shot classification using the Bidirectional Auto-Regressive Transformers (BART) large model and few-shot prompting using Generative Pre-trained Transformer- 3 (ChatGPT-3) achieve the best results