# 通过精准的置信度评分，提升对大型语言模型产出的代码摘要的信任度。

发布时间：2024年04月30日

`LLM应用` `程序理解` `软件工程`

> Enhancing Trust in LLM-Generated Code Summaries with Calibrated Confidence Scores

# 摘要

> 在程序理解的过程中，一份精炼、流畅且切题的摘要极为有用。然而，制作这样的摘要需要投入大量的人力。在软件项目中，优质的摘要往往难以获得，这增加了维护的难度。目前，已有大量研究致力于开发自动化的AI方法，利用大型语言模型（LLMs）来生成代码摘要。同时，也有许多研究致力于评估这些摘要方法的性能，特别是它们生成的摘要与人类生成摘要的相似度。诸如BERTScore和BLEU等评价指标已被提出，并在以人为对象的研究中进行了评估。但是，LLMs有时会出错，生成的摘要与人类的表达方式大相径庭。面对LLM生成的代码摘要，我们如何判断其是否足够接近人类生成的摘要？本文中，我们探讨了这一问题，将其视为一个校准问题：给定LLM生成的摘要，我们能否计算出一个置信度量，以判断该摘要是否足够接近人类可能生成的摘要？我们通过多种语言和不同设置下的多种LLMs来检验这一问题。我们提出了一种方法，能够提供对摘要与人类生成摘要相似性可能性的准确预测。

> A good summary can often be very useful during program comprehension. While a brief, fluent, and relevant summary can be helpful, it does require significant human effort to produce. Often, good summaries are unavailable in software projects, thus making maintenance more difficult. There has been a considerable body of research into automated AI-based methods, using Large Language models (LLMs), to generate summaries of code; there also has been quite a bit work on ways to measure the performance of such summarization methods, with special attention paid to how closely these AI-generated summaries resemble a summary a human might have produced. Measures such as BERTScore and BLEU have been suggested and evaluated with human-subject studies.
  However, LLMs often err and generate something quite unlike what a human might say. Given an LLM-produced code summary, is there a way to gauge whether it's likely to be sufficiently similar to a human produced summary, or not? In this paper, we study this question, as a calibration problem: given a summary from an LLM, can we compute a confidence measure, which is a good indication of whether the summary is sufficiently similar to what a human would have produced in this situation? We examine this question using several LLMs, for several languages, and in several different settings. We suggest an approach which provides well-calibrated predictions of likelihood of similarity to human summaries.

[Arxiv](https://arxiv.org/abs/2404.19318)