# FAMMA：金融领域多语言多模态问答的标杆

发布时间：2024年10月06日

`LLM应用` `问答系统`

> FAMMA: A Benchmark for Financial Domain Multilingual Multimodal Question Answering

# 摘要

> 本文介绍了 FAMMA，一个专为金融领域多语言多模态问答设计的开源基准。FAMMA 旨在测试多模态大型语言模型在处理复杂金融问题时的表现，涵盖公司金融、资产管理等八大子领域，包含 1,758 个精心挑选的问答对，部分为中文或法语，多数为英文，且问题形式多样，包括图表、表格等。测试结果显示，即使是顶尖模型如 GPT-4o 和 Claude-35-Sonnet，准确率也仅达 42%，而开源模型 Qwen2-VL 表现更为逊色。通过引入 GPT o1-style 推理链，模型错误纠正能力显著提升。FAMMA 的推出，将推动金融问答领域专家系统的研发。排行榜详见 https://famma-bench.github.io/famma/。

> In this paper, we introduce FAMMA, an open-source benchmark for financial multilingual multimodal question answering (QA). Our benchmark aims to evaluate the abilities of multimodal large language models (MLLMs) in answering questions that require advanced financial knowledge and sophisticated reasoning. It includes 1,758 meticulously collected question-answer pairs from university textbooks and exams, spanning 8 major subfields in finance including corporate finance, asset management, and financial engineering. Some of the QA pairs are written in Chinese or French, while a majority of them are in English. These questions are presented in a mixed format combining text and heterogeneous image types, such as charts, tables, and diagrams. We evaluate a range of state-of-the-art MLLMs on our benchmark, and our analysis shows that FAMMA poses a significant challenge for these models. Even advanced systems like GPT-4o and Claude-35-Sonnet achieve only 42\% accuracy. Additionally, the open-source Qwen2-VL lags notably behind its proprietary counterparts. Lastly, we explore GPT o1-style reasoning chains to enhance the models' reasoning capabilities, which significantly improve error correction. Our FAMMA benchmark will facilitate future research to develop expert systems in financial QA. The leaderboard is available at https://famma-bench.github.io/famma/ .

[Arxiv](https://arxiv.org/abs/2410.04526)