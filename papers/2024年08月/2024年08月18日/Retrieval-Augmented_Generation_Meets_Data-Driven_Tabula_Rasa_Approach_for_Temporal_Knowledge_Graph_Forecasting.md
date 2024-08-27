# 检索增强生成技术与数据驱动的“白板”方法相结合，共同助力时间知识图谱的预测任务。

发布时间：2024年08月18日

`RAG` `人工智能` `数据分析`

> Retrieval-Augmented Generation Meets Data-Driven Tabula Rasa Approach for Temporal Knowledge Graph Forecasting

# 摘要

> 面对预训练大型语言模型（如OpenAI ChatGPT和Google Gemini）在事实回忆、幻觉、偏见及时间知识图谱预测中的数据泄露挑战，我们推出了sLA-tKGF，一种小规模语言助手，通过RAG辅助和定制训练，从零开始有效预测tKG。该框架整合历史数据、网络搜索及PLLMs文本，构建知识融合提示，深入理解历史实体关系，为小规模模型提供精准的未来事件预测，同时减少幻觉和分布偏移问题。实证研究显示，该框架在基准数据集上表现卓越，提供可信且可解释的tKG预测，同时降低计算需求。

> Pre-trained large language models (PLLMs) like OpenAI ChatGPT and Google Gemini face challenges such as inaccurate factual recall, hallucinations, biases, and future data leakage for temporal Knowledge Graph (tKG) forecasting. To address these issues, we introduce sLA-tKGF (small-scale language assistant for tKG forecasting), which utilizes Retrieval-Augmented Generation (RAG) aided, custom-trained small-scale language models through a tabula rasa approach from scratch for effective tKG forecasting. Our framework constructs knowledge-infused prompts with relevant historical data from tKGs, web search results, and PLLMs-generated textual descriptions to understand historical entity relationships prior to the target time. It leverages these external knowledge-infused prompts for deeper understanding and reasoning of context-specific semantic and temporal information to zero-shot prompt small-scale language models for more accurate predictions of future events within tKGs. It reduces hallucinations and mitigates distributional shift challenges through comprehending changing trends over time. As a result, it enables more accurate and contextually grounded forecasts of future events while minimizing computational demands. Rigorous empirical studies demonstrate our framework robustness, scalability, and state-of-the-art (SOTA) performance on benchmark datasets with interpretable and trustworthy tKG forecasting.

[Arxiv](https://arxiv.org/abs/2408.13273)