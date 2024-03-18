# [针对同时执行命名实体提取与拼写修正任务，本研究探讨了大型语言模型的应用潜力。通过利用大型语言模型的力量，我们旨在提升模型在面对实体抽取与拼写错误修正双重挑战时的表现。]

发布时间：2024年03月01日

`LLM应用`

> Large Language Models for Simultaneous Named Entity Extraction and Spelling Correction

> 研究发现，BERT 等语言模型在识别文本中命名实体（NE）方面表现出色，常被当作分类器来划分文本标记或标记序列的类别归属。本文进一步推测，仅包含解码器部分的大型语言模型（LLMs）不仅能够自动生成 NE，还可能矫正输入文本中原有的拼写错误，从而还原 NE 的正确形态。我们在本研究中对两组 BERT LMs 做了微调作为对照，并对另外八种开源 LLMs 进行了针对日本店铺收据图片经 OCR 转换后文本提取 NE 的微调任务，但并未涉及定位 NE 在文本中的具体位置。实验结果显示，在此任务上，最优微调后的 LLM 表现略优于最优微调后的 BERT LM，尽管差距不明显，但正如预期所设想的那样，该最优 LLM 在特定情况下确实能有效纠正 OCR 引入的错误。

> Language Models (LMs) such as BERT, have been shown to perform well on the task of identifying Named Entities (NE) in text. A BERT LM is typically used as a classifier to classify individual tokens in the input text, or to classify spans of tokens, as belonging to one of a set of possible NE categories.
  In this paper, we hypothesise that decoder-only Large Language Models (LLMs) can also be used generatively to extract both the NE, as well as potentially recover the correct surface form of the NE, where any spelling errors that were present in the input text get automatically corrected.
  We fine-tune two BERT LMs as baselines, as well as eight open-source LLMs, on the task of producing NEs from text that was obtained by applying Optical Character Recognition (OCR) to images of Japanese shop receipts; in this work, we do not attempt to find or evaluate the location of NEs in the text.
  We show that the best fine-tuned LLM performs as well as, or slightly better than, the best fine-tuned BERT LM, although the differences are not significant. However, the best LLM is also shown to correct OCR errors in some cases, as initially hypothesised.

[Arxiv](https://arxiv.org/abs/2403.00528)