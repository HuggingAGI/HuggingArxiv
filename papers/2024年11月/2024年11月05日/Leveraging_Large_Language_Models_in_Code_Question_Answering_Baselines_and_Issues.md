# 在代码问答中利用大型语言模型：基线和问题

发布时间：2024年11月05日

`LLM应用` `源代码`

> Leveraging Large Language Models in Code Question Answering: Baselines and Issues

# 摘要

> 对源代码的问答为软件工程师和项目经理提供了有关软件产品已实现功能的有用信息。本文介绍了一项致力于使用大型语言模型对 Python 中的源代码进行问答的工作。实现源代码问答系统的拟议方法涉及在 Python 代码的问题和答案的统一数据集上对大型语言模型进行微调。为了获得最高质量的答案，我们测试了在以不同方式预处理的数据集上训练的各种模型：一个没有语法纠正的数据集、一个有语法纠正的数据集和一个用生成的摘要扩充的数据集。还手动分析了模型答案中的错误。我们报告了 BLEU-4、BERTScore F1、BLEURT 和精确匹配度量值，以及手动错误分析的结论。获得的实验结果突出了研究领域当前的问题，例如公共真实问答数据集的质量差。此外，研究结果包括训练数据的语法纠正对测试度量值的积极影响。所提出的发现和问题对于其他试图提高源代码问答解决方案质量的研究人员可能很重要。训练和评估代码可在 https://github.com/IU-AES-AI4Code/CodeQuestionAnswering 公开获取。

> Question answering over source code provides software engineers and project managers with helpful information about the implemented features of a software product. This paper presents a work devoted to using large language models for question answering over source code in Python. The proposed method for implementing a source code question answering system involves fine-tuning a large language model on a unified dataset of questions and answers for Python code. To achieve the highest quality answers, we tested various models trained on datasets preprocessed in different ways: a dataset without grammar correction, a dataset with grammar correction, and a dataset augmented with the generated summaries. The model answers were also analyzed for errors manually. We report BLEU-4, BERTScore F1, BLEURT, and Exact Match metric values, along with the conclusions from the manual error analysis. The obtained experimental results highlight the current problems of the research area, such as poor quality of the public genuine question-answering datasets. In addition, the findings include the positive effect of the grammar correction of the training data on the testing metric values. The addressed findings and issues could be important for other researchers who attempt to improve the quality of source code question answering solutions. The training and evaluation code is publicly available at https://github.com/IU-AES-AI4Code/CodeQuestionAnswering.

[Arxiv](https://arxiv.org/abs/2411.03012)