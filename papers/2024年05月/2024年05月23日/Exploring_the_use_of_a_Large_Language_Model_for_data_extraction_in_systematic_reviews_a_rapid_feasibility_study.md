# 本研究旨在快速评估大型语言模型在系统评价数据提取中的应用潜力。

发布时间：2024年05月23日

`LLM应用

这篇论文探讨了GPT-4这一大型语言模型在系统评价数据提取半自动化中的应用潜力，具体涉及了自动提取研究特征和预测PICO要素的实验。论文关注的是LLM在实际应用中的表现和评估，而不是Agent的行为、RAG（Retrieval-Augmented Generation）的机制或者LLM的理论研究。因此，最合适的分类是LLM应用。` `系统评价`

> Exploring the use of a Large Language Model for data extraction in systematic reviews: a rapid feasibility study

# 摘要

> 本文探讨了GPT-4这一大型语言模型在系统评价数据提取半自动化中的应用潜力。尽管LLMs备受瞩目，但如何构建和评估这些工具仍是一个谜。在2023年的证据综合黑客松中，我们进行了两项探索：一是自动提取临床、动物和社科研究的研究特征，使用每类两项研究进行提示设计，十项用于评估；二是预测EBM-NLP数据集中100篇摘要的PICO要素。总体准确率达80%，但各领域有所不同。因果推断和研究设计方面的错误较多。PICO研究中，参与者和干预/对照的准确率较高，而结果预测更具挑战。评估采用人工方式，传统评分方法如BLEU和ROUGE效果有限。我们注意到LLM预测的不稳定性和响应质量的波动。本文为未来评估LLMs在系统评价自动化数据提取中的应用提供了一个框架。虽然LLMs可能成为审稿的有力助手，但在整合如GPT-4这样的模型时，我们应保持谨慎，并需进一步研究其在实际操作中的稳定性和可靠性。

> This paper describes a rapid feasibility study of using GPT-4, a large language model (LLM), to (semi)automate data extraction in systematic reviews. Despite the recent surge of interest in LLMs there is still a lack of understanding of how to design LLM-based automation tools and how to robustly evaluate their performance. During the 2023 Evidence Synthesis Hackathon we conducted two feasibility studies. Firstly, to automatically extract study characteristics from human clinical, animal, and social science domain studies. We used two studies from each category for prompt-development; and ten for evaluation. Secondly, we used the LLM to predict Participants, Interventions, Controls and Outcomes (PICOs) labelled within 100 abstracts in the EBM-NLP dataset. Overall, results indicated an accuracy of around 80%, with some variability between domains (82% for human clinical, 80% for animal, and 72% for studies of human social sciences). Causal inference methods and study design were the data extraction items with the most errors. In the PICO study, participants and intervention/control showed high accuracy (>80%), outcomes were more challenging. Evaluation was done manually; scoring methods such as BLEU and ROUGE showed limited value. We observed variability in the LLMs predictions and changes in response quality. This paper presents a template for future evaluations of LLMs in the context of data extraction for systematic review automation. Our results show that there might be value in using LLMs, for example as second or third reviewers. However, caution is advised when integrating models such as GPT-4 into tools. Further research on stability and reliability in practical settings is warranted for each type of data that is processed by the LLM.

[Arxiv](https://arxiv.org/abs/2405.14445)