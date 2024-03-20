# 本研究致力于训练大型语言模型，使其能够精准识别并主动忽略无关条件，以提升模型处理复杂任务时的聚焦性和准确性。

发布时间：2024年03月19日

`LLM应用`

> Instructing Large Language Models to Identify and Ignore Irrelevant Conditions

> 面对常包含无关条件的数学文字问题(MWP)，解决方案需基于问题描述构建推理路径。现有的一些利用大型语言模型(LLMs)的链式思考(CoT)方法虽能实现多步推理，但在处理无关条件时却容易困惑，进而影响准确性。本文创新性地引入I$^3$C方法，引导LLMs识别并剔除无关条件。该方法先找出一组与问题语义关联度低的无关条件候选，接着让LLMs验证这些条件，并最后在清晰区分相关与无关条件的前提下，优化LLMs的推理路径，消除困惑。同时，我们还提出了一种搭配少量示例推理的策略——I$^3$C-Select，通过选取最具迷惑性的（问题，推理路径）对来提升I$^3$C的效果。我们在多个MWP数据集上进行了大量实验，发现无论结合何种CoT提示方法，I$^3$C都能有效提高解决MWPs的性能。尤其在配合GPT-3.5-Turbo和精心挑选的I$^3$C-Select后，在GSM-IC2-1K和GSM-ICM-1K数据集上，准确率分别跃升至96.0%和94.1%，比现有的最佳few-shot提示方法Complex-CoT高出+11.7和+11.1个百分点。我们的研究成果已开源，访问地址为https://wzy6642.github.io/I3C.github.io/。

> Math word problem (MWP) solving requires generating a reasoning path based on a given problem description that often contains irrelevant conditions. Existing chain-of-thought (CoT) prompting methods elicited multi-step reasoning abilities of large language models (LLMs) to solve MWPs. However, they were seriously confused by the irrelevant conditions, resulting in low accuracy. In this paper, we propose a novel approach named I$^3$C that instructs LLMs to identify and ignore irrelevant conditions. It identifies a set of irrelevant condition candidates that have a weak semantic relevance with the question. Then it prompts LLMs to verify the irrelevant conditions. Lastly it instructs the LLMs with the verification on relevant and irrelevant conditions to avoid confusion and improve reasoning paths. Moreover, we propose to select (problem, reasoning paths) pairs as demonstrations to enhance I$^3$C with few-shot reasoning. We develop I$^3$C-Select that selects the most confusing problems based on the semantic relevance measurement. We conduct extensive experiments on eight MWP datasets. I$^3$C can be combined with any CoT prompting methods to improve the performance of solving MWPs. Notably, with GPT-3.5-Turbo and I$^3$C-Select, we achieve an accuracy of 96.0 and 94.1 on GSM-IC2-1K and GSM-ICM-1K, respectively, significantly outperforming the state-of-the-art few-shot prompting method Complex-CoT by +11.7 and +11.1. Our implementation is made publicly available at https://wzy6642.github.io/I3C.github.io/.

[Arxiv](https://arxiv.org/abs/2403.12744)