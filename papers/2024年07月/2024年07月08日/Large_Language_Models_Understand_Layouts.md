# 大型语言模型具备理解布局的能力。

发布时间：2024年07月08日

`LLM应用` `人工智能` `视觉问答`

> Large Language Models Understand Layouts

# 摘要

> 大型语言模型 (LLMs) 在众多 NLP 任务中表现卓越。本文揭示，LLMs 不仅能理解文本，还能处理空间标记指示的文本布局，解答涉及空间感知的问题。然而，去除空间标记会导致性能大幅下降。我们通过 GPT-3.5、Baichuan2、Llama2 和 ChatGLM3 在布局敏感数据集上的实验，发现布局理解能力源自预训练数据，并在指令调优中强化。利用创新文本游戏自动生成数据，可进一步增强布局理解。此外，这种能力对构建高效的视觉问答 (VQA) 系统大有裨益。

> Large language models (LLMs) demonstrate extraordinary abilities in a wide range of natural language processing (NLP) tasks. In this paper, we show that, beyond text understanding capability, LLMs are capable of processing text layouts that are denoted by spatial markers. They are able to answer questions that require explicit spatial perceiving and reasoning, while a drastic performance drop is observed when the spatial markers from the original data are excluded. We perform a series of experiments with the GPT-3.5, Baichuan2, Llama2 and ChatGLM3 models on various types of layout-sensitive datasets for further analysis. The experimental results reveal that the layout understanding ability of LLMs is mainly introduced by the coding data for pretraining, which is further enhanced at the instruction-tuning stage. In addition, layout understanding can be enhanced by integrating low-cost, auto-generated data approached by a novel text game. Finally, we show that layout understanding ability is beneficial for building efficient visual question-answering (VQA) systems.

[Arxiv](https://arxiv.org/abs/2407.05750)