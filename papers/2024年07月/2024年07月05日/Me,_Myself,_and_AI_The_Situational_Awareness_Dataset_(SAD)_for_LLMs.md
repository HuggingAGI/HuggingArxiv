# 我、自我与AI：为LLM量身打造的情境意识数据集（SAD）

发布时间：2024年07月05日

`LLM理论` `人工智能` `数据分析`

> Me, Myself, and AI: The Situational Awareness Dataset (SAD) for LLMs

# 摘要

> AI助手如ChatGPT在回应用户时自称“我是一个大型语言模型”，这引发了疑问：这些模型是否真正了解自己的身份，并据此行动？它们是否意识到自己被公众使用的情境？我们将这种自我认知和环境感知称为“情境意识”。为了量化大型语言模型（LLM）的情境意识，我们设计了一系列基于问答和指令遵循的测试，形成了包含7大类任务和超过13,000个问题的情境意识数据集（SAD）。SAD测试了LLM的多项能力，如识别自身生成文本、预测行为、区分评估与实际部署环境、遵循基于自我认知的指令等。我们对16个LLM进行了SAD评估，包括预训练和聊天模型。尽管所有模型表现均优于随机水平，但即便是表现最佳的Claude 3 Opus，在某些任务上仍远未达到人类基准。我们还发现，SAD表现与一般知识指标（如MMLU）的相关性有限。经过微调以服务为AI助手的聊天模型，在SAD上表现优于其基础模型，但在一般知识任务上则不然。SAD旨在通过量化分析，深化对LLM情境意识的理解。情境意识至关重要，因为它提升了模型的自主规划与行动能力，虽为自动化带来潜在益处，但也带来了与AI安全和控制相关的新风险。相关代码和最新结果可访问https://situational-awareness-dataset.org。

> AI assistants such as ChatGPT are trained to respond to users by saying, "I am a large language model". This raises questions. Do such models know that they are LLMs and reliably act on this knowledge? Are they aware of their current circumstances, such as being deployed to the public? We refer to a model's knowledge of itself and its circumstances as situational awareness. To quantify situational awareness in LLMs, we introduce a range of behavioral tests, based on question answering and instruction following. These tests form the $\textbf{Situational Awareness Dataset (SAD)}$, a benchmark comprising 7 task categories and over 13,000 questions. The benchmark tests numerous abilities, including the capacity of LLMs to (i) recognize their own generated text, (ii) predict their own behavior, (iii) determine whether a prompt is from internal evaluation or real-world deployment, and (iv) follow instructions that depend on self-knowledge.
  We evaluate 16 LLMs on SAD, including both base (pretrained) and chat models. While all models perform better than chance, even the highest-scoring model (Claude 3 Opus) is far from a human baseline on certain tasks. We also observe that performance on SAD is only partially predicted by metrics of general knowledge (e.g. MMLU). Chat models, which are finetuned to serve as AI assistants, outperform their corresponding base models on SAD but not on general knowledge tasks. The purpose of SAD is to facilitate scientific understanding of situational awareness in LLMs by breaking it down into quantitative abilities. Situational awareness is important because it enhances a model's capacity for autonomous planning and action. While this has potential benefits for automation, it also introduces novel risks related to AI safety and control. Code and latest results available at https://situational-awareness-dataset.org .

[Arxiv](https://arxiv.org/abs/2407.04694)