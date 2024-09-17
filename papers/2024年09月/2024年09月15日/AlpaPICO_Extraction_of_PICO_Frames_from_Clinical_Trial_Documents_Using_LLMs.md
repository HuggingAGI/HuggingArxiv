# AlpaPICO：借助 LLM 技术，从临床试验文档中精准提取 PICO 框架。

发布时间：2024年09月15日

`LLM应用` `临床试验`

> AlpaPICO: Extraction of PICO Frames from Clinical Trial Documents Using LLMs

# 摘要

> 近年来，临床试验报告的激增使得系统综述变得困难。自动提取PICO信息可以简化这一过程。现有方法依赖于手动注释，而ICL等新方法则需要标记示例。我们利用LLM的预训练知识，在无监督环境中自动提取PICO术语，并使用LORA在低资源环境下进行指令调优，以提升PICO框架提取的性能。实验结果显示，我们的ICL框架在EBM-NLP数据集上表现优异，指令调优版本更是达到了最先进水平。项目代码可在\url{https://github.com/shrimonmuke0202/AlpaPICO.git}找到。

> In recent years, there has been a surge in the publication of clinical trial reports, making it challenging to conduct systematic reviews. Automatically extracting Population, Intervention, Comparator, and Outcome (PICO) from clinical trial studies can alleviate the traditionally time-consuming process of manually scrutinizing systematic reviews. Existing approaches of PICO frame extraction involves supervised approach that relies on the existence of manually annotated data points in the form of BIO label tagging. Recent approaches, such as In-Context Learning (ICL), which has been shown to be effective for a number of downstream NLP tasks, require the use of labeled examples. In this work, we adopt ICL strategy by employing the pretrained knowledge of Large Language Models (LLMs), gathered during the pretraining phase of an LLM, to automatically extract the PICO-related terminologies from clinical trial documents in unsupervised set up to bypass the availability of large number of annotated data instances. Additionally, to showcase the highest effectiveness of LLM in oracle scenario where large number of annotated samples are available, we adopt the instruction tuning strategy by employing Low Rank Adaptation (LORA) to conduct the training of gigantic model in low resource environment for the PICO frame extraction task. Our empirical results show that our proposed ICL-based framework produces comparable results on all the version of EBM-NLP datasets and the proposed instruction tuned version of our framework produces state-of-the-art results on all the different EBM-NLP datasets. Our project is available at \url{https://github.com/shrimonmuke0202/AlpaPICO.git}.

[Arxiv](https://arxiv.org/abs/2409.09704)