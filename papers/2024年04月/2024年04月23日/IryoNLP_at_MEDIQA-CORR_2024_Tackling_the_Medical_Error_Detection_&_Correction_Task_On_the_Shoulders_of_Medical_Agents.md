# IryoNLP 亮相 2024 年 MEDIQA-CORR，携手医疗代理共同攻克医疗错误检测与纠正的挑战。

发布时间：2024年04月23日

`Agent`

> IryoNLP at MEDIQA-CORR 2024: Tackling the Medical Error Detection & Correction Task On the Shoulders of Medical Agents

# 摘要

> 在临床领域的自然语言处理应用中，借助大型语言模型来检测和修正临床记录中的错误，这一方法显示出巨大的潜力，尤其是在标注数据难以获得的复杂任务中。本研究提出了一个创新的系统——MedReAct'N'MedReFlex，它整合了四个基于大型语言模型的医疗智能体。MedReAct 智能体首先通过观察、分析和执行操作来启动错误检测流程，生成路径以定位临床记录中的潜在错误。接着，MedEval 智能体动用五个评估器对目标错误及其修正建议进行评估。当 MedReAct 的修正措施不足时，MedReFlex 智能体会介入，进行深入分析并提出新的策略。最终，MedFinalParser 智能体负责将修正后的内容格式化输出，既保持了原文的风格，又确保了错误修正过程的准确性。我们的方法还包括一个基于 ClinicalCorp 语料库的 RAG 流程，这是我们的核心组成部分。我们还预处理并开源了 MedWiki 数据集，以支持临床 RAG 应用。实验结果显示，我们的 RAG 方法在 MedReAct'N'MedReFlex 框架下，通过 ClinicalCorp 数据集的加持，发挥了关键作用，在 MEDIQA-CORR 2024 的最终排行榜上荣获第九名。

> In natural language processing applied to the clinical domain, utilizing large language models has emerged as a promising avenue for error detection and correction on clinical notes, a knowledge-intensive task for which annotated data is scarce. This paper presents MedReAct'N'MedReFlex, which leverages a suite of four LLM-based medical agents. The MedReAct agent initiates the process by observing, analyzing, and taking action, generating trajectories to guide the search to target a potential error in the clinical notes. Subsequently, the MedEval agent employs five evaluators to assess the targeted error and the proposed correction. In cases where MedReAct's actions prove insufficient, the MedReFlex agent intervenes, engaging in reflective analysis and proposing alternative strategies. Finally, the MedFinalParser agent formats the final output, preserving the original style while ensuring the integrity of the error correction process. One core component of our method is our RAG pipeline based on our ClinicalCorp corpora. Among other well-known sources containing clinical guidelines and information, we preprocess and release the open-source MedWiki dataset for clinical RAG application. Our results demonstrate the central role of our RAG approach with ClinicalCorp leveraged through the MedReAct'N'MedReFlex framework. It achieved the ninth rank on the MEDIQA-CORR 2024 final leaderboard.

![IryoNLP 亮相 2024 年 MEDIQA-CORR，携手医疗代理共同攻克医疗错误检测与纠正的挑战。](../../../paper_images/2404.15488/x1.png)

![IryoNLP 亮相 2024 年 MEDIQA-CORR，携手医疗代理共同攻克医疗错误检测与纠正的挑战。](../../../paper_images/2404.15488/x2.png)

![IryoNLP 亮相 2024 年 MEDIQA-CORR，携手医疗代理共同攻克医疗错误检测与纠正的挑战。](../../../paper_images/2404.15488/x3.png)

![IryoNLP 亮相 2024 年 MEDIQA-CORR，携手医疗代理共同攻克医疗错误检测与纠正的挑战。](../../../paper_images/2404.15488/x4.png)

![IryoNLP 亮相 2024 年 MEDIQA-CORR，携手医疗代理共同攻克医疗错误检测与纠正的挑战。](../../../paper_images/2404.15488/x5.png)

![IryoNLP 亮相 2024 年 MEDIQA-CORR，携手医疗代理共同攻克医疗错误检测与纠正的挑战。](../../../paper_images/2404.15488/x6.png)

![IryoNLP 亮相 2024 年 MEDIQA-CORR，携手医疗代理共同攻克医疗错误检测与纠正的挑战。](../../../paper_images/2404.15488/x7.png)

![IryoNLP 亮相 2024 年 MEDIQA-CORR，携手医疗代理共同攻克医疗错误检测与纠正的挑战。](../../../paper_images/2404.15488/x8.png)

[Arxiv](https://arxiv.org/abs/2404.15488)