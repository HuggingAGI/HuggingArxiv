# CursorCore：以万物对齐之力，助你编程一臂之力

发布时间：2024年10月09日

`LLM应用` `软件开发` `人工智能`

> CursorCore: Assist Programming through Aligning Anything

# 摘要

> 大型语言模型在编程辅助任务中表现出色，但现有应用仍不够自动化，难以在编程过程中整合多种信息。为此，我们提出了一种新的对话框架，全面整合编码历史、当前代码和用户指令等信息。首先，我们引入了APEval基准，全面评估模型在编程辅助任务中的表现。接着，我们开发了Programming-Instruct数据生成管道，自动合成训练数据。利用此管道，我们生成了219K样本，微调模型并推出CursorCore系列，其性能优于同类模型。该框架不仅统一了内联聊天和自动化编辑等应用，还推动了编码助手的进步。所有资源均可免费获取。

> Large language models have been successfully applied to programming assistance tasks, such as code completion, code insertion, and instructional code editing. However, these applications remain insufficiently automated and struggle to effectively integrate various types of information during the programming process, including coding history, current code, and user instructions. In this work, we propose a new conversational framework that comprehensively integrates these information sources, collect data to train our models and evaluate their performance. Firstly, to thoroughly evaluate how well models align with different types of information and the quality of their outputs, we introduce a new benchmark, APEval (Assist Programming Eval), to comprehensively assess the performance of models in programming assistance tasks. Then, for data collection, we develop a data generation pipeline, Programming-Instruct, which synthesizes training data from diverse sources, such as GitHub and online judge platforms. This pipeline can automatically generate various types of messages throughout the programming process. Finally, using this pipeline, we generate 219K samples, fine-tune multiple models, and develop the CursorCore series. We show that CursorCore outperforms other models of comparable size. This framework unifies applications such as inline chat and automated editing, contributes to the advancement of coding assistants. Code, models and data are freely available at https://github.com/TechxGenus/CursorCore.

[Arxiv](https://arxiv.org/abs/2410.07002)