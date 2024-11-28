# 借助自然语言处理技术和基于大型语言模型的检索增强生成来实现自动化文献综述

发布时间：2024年11月27日

`RAG` `文献综述`

> Automated Literature Review Using NLP Techniques and LLM-Based Retrieval-Augmented Generation

# 摘要

> 本研究展示并对比了运用多种自然语言处理（NLP）技术及结合大型语言模型（LLM）的检索增强生成（RAG）来实现文献综述自动生成的多种途径。研究文章数量的持续增多给人工文献综述带来极大挑战，致使对自动化的需求攀升。开发仅以PDF文件为输入就能自动生成文献综述的系统，乃是本研究工作的首要目标。为达成这一目标，对诸如基于频率的方法（spaCy）、转换器模型（Simple T5）以及结合大型语言模型（GPT-3.5-turbo）的检索增强生成（RAG）等多种自然语言处理（NLP）策略的有效性进行了评估。本研究实验选用了SciTLDR数据集，并采用三种不同技术实现了三个不同的文献综述自动生成系统。通过ROUGE分数对这三个系统予以评估。评估结果表明，大型语言模型GPT-3.5-turbo的ROUGE-1分数最高，达0.364。转换器模型位列第二，spaCy排在末位。最后，为基于大型语言模型的最优系统创建了图形用户界面。

> This research presents and compares multiple approaches to automate the generation of literature reviews using several Natural Language Processing (NLP) techniques and retrieval-augmented generation (RAG) with a Large Language Model (LLM). The ever-increasing number of research articles provides a huge challenge for manual literature review. It has resulted in an increased demand for automation. Developing a system capable of automatically generating the literature reviews from only the PDF files as input is the primary objective of this research work. The effectiveness of several Natural Language Processing (NLP) strategies, such as the frequency-based method (spaCy), the transformer model (Simple T5), and retrieval-augmented generation (RAG) with Large Language Model (GPT-3.5-turbo), is evaluated to meet the primary objective. The SciTLDR dataset is chosen for this research experiment and three distinct techniques are utilized to implement three different systems for auto-generating the literature reviews. The ROUGE scores are used for the evaluation of all three systems. Based on the evaluation, the Large Language Model GPT-3.5-turbo achieved the highest ROUGE-1 score, 0.364. The transformer model comes in second place and spaCy is at the last position. Finally, a graphical user interface is created for the best system based on the large language model.

[Arxiv](https://arxiv.org/abs/2411.18583)