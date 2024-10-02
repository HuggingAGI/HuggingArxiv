# 大型语言模型在多指令文档中的对话问答基准测试

发布时间：2024年10月01日

`LLM应用` `软件开发`

> Benchmarking Large Language Models for Conversational Question Answering in Multi-instructional Documents

# 摘要

> 指导性文档虽是任务完成的宝库，但在对话问答（CQA）中的挑战仍未被深入研究。现有基准多聚焦于单一文档的基本问答，难以评估模型在复杂指导文档中的理解与日常指导能力。为此，我们推出InsCoQA，一个专为LLM在指导文档CQA中表现设计的基准。InsCoQA基于丰富的百科式指导内容，测试模型从多文档中提取、解读并精准总结程序指导的能力，反映现实任务的复杂性。同时，为全面评估LLM在InsCoQA上的表现，我们引入InsEval，一个由LLM辅助的评估工具，确保生成答案与指导的完整与准确。

> Instructional documents are rich sources of knowledge for completing various tasks, yet their unique challenges in conversational question answering (CQA) have not been thoroughly explored. Existing benchmarks have primarily focused on basic factual question-answering from single narrative documents, making them inadequate for assessing a model`s ability to comprehend complex real-world instructional documents and provide accurate step-by-step guidance in daily life. To bridge this gap, we present InsCoQA, a novel benchmark tailored for evaluating large language models (LLMs) in the context of CQA with instructional documents. Sourced from extensive, encyclopedia-style instructional content, InsCoQA assesses models on their ability to retrieve, interpret, and accurately summarize procedural guidance from multiple documents, reflecting the intricate and multi-faceted nature of real-world instructional tasks. Additionally, to comprehensively assess state-of-the-art LLMs on the InsCoQA benchmark, we propose InsEval, an LLM-assisted evaluator that measures the integrity and accuracy of generated responses and procedural instructions.

[Arxiv](https://arxiv.org/abs/2410.00526)