# [该数据集包含日语-英语句子翻译练习题目，专为实现自动化评分而设计。]

发布时间：2024年03月05日

`LLM应用`

> Japanese-English Sentence Translation Exercises Dataset for Automatic Grading

> 本文提出了一项针对早期L2语言学习中广泛使用的句子翻译练习（STEs）自动评估任务的研究。研究将教师预设评分标准下对学生答案的评价进行了规范化处理，并构建了一个包含21道题目的日英STE数据集，附带总计3,498份学生回答（平均每题约167份）。这些回答集合了学生与众包工作者的答案。通过这一数据集，我们验证了包括使用少量示例上下文学习微调的BERT和GPT模型在内的多种基准方法的性能表现。实验证明，微调后的BERT基准模型对正确答案的识别能达到约90%的F1得分，但在识别错误答案时准确率仅略高于80%。另外，少量示例学习下的GPT模型相较于微调BERT模型显示出较弱的结果，这表明我们新提出的任务即使面对当前最先进大型语言模型也极具挑战性。

> This paper proposes the task of automatic assessment of Sentence Translation Exercises (STEs), that have been used in the early stage of L2 language learning. We formalize the task as grading student responses for each rubric criterion pre-specified by the educators. We then create a dataset for STE between Japanese and English including 21 questions, along with a total of 3, 498 student responses (167 on average). The answer responses were collected from students and crowd workers. Using this dataset, we demonstrate the performance of baselines including finetuned BERT and GPT models with few-shot in-context learning. Experimental results show that the baseline model with finetuned BERT was able to classify correct responses with approximately 90% in F1, but only less than 80% for incorrect responses. Furthermore, the GPT models with few-shot learning show poorer results than finetuned BERT, indicating that our newly proposed task presents a challenging issue, even for the stateof-the-art large language models.

[Arxiv](https://arxiv.org/abs/2403.03396)