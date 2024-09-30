# 基于语料库的澄清问题增强生成

发布时间：2024年09月27日

`RAG` `信息检索`

> Corpus-informed Retrieval Augmented Generation of Clarifying Questions

# 摘要

> 本研究旨在开发能够生成与检索语料库信息一致的澄清问题的模型。我们展示了检索增强语言模型（RAG）在此过程中的有效性，强调其能够联合建模用户查询和语料库，以端到端方式定位不确定性并请求澄清，同时建模更多证据文档以增加问题广度。然而，当前数据集中搜索意图大多未被语料库支持，导致模型“幻觉”，提出语料库中不存在的意图，影响性能。为此，我们提出数据集增强方法，使基本事实澄清与语料库对齐，并探索增强推理时证据池相关性的技术。但识别语料库中的基本事实意图仍具挑战，部分原因是当前数据集对澄清分类法的偏见，呼吁支持生成语料库信息澄清的数据。

> This study aims to develop models that generate corpus informed clarifying questions for web search, in a way that ensures the questions align with the available information in the retrieval corpus. We demonstrate the effectiveness of Retrieval Augmented Language Models (RAG) in this process, emphasising their ability to (i) jointly model the user query and retrieval corpus to pinpoint the uncertainty and ask for clarifications end-to-end and (ii) model more evidence documents, which can be used towards increasing the breadth of the questions asked. However, we observe that in current datasets search intents are largely unsupported by the corpus, which is problematic both for training and evaluation. This causes question generation models to ``hallucinate'', ie. suggest intents that are not in the corpus, which can have detrimental effects in performance. To address this, we propose dataset augmentation methods that align the ground truth clarifications with the retrieval corpus. Additionally, we explore techniques to enhance the relevance of the evidence pool during inference, but find that identifying ground truth intents within the corpus remains challenging. Our analysis suggests that this challenge is partly due to the bias of current datasets towards clarification taxonomies and calls for data that can support generating corpus-informed clarifications.

[Arxiv](https://arxiv.org/abs/2409.18575)