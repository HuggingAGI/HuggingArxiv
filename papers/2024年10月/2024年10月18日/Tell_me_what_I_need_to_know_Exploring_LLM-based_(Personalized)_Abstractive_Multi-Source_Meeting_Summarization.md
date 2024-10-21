# 探索基于 LLM 的个性化多源会议摘要，揭示你需要了解的关键信息。

发布时间：2024年10月18日

`LLM应用` `会议管理`

> Tell me what I need to know: Exploring LLM-based (Personalized) Abstractive Multi-Source Meeting Summarization

# 摘要

> 会议摘要对数字通信至关重要，但现有方法在生成个性化摘要和理解会议内容方面仍有不足。以往尝试通过结合演示文稿等补充资源来改进，但受限于模型上下文大小和多源任务的复杂性。本研究采用三阶段大型语言模型方法，通过识别需补充的转录段落、从补充材料中提取相关信息并整合，最终生成更丰富的摘要。这种方法不仅将摘要相关性提升了约9%，还通过个性化协议提取参与者特征，使摘要信息量增加了约10%。此外，我们还探讨了四大模型家族的性能成本权衡，包括适用于边缘设备的选择。此方法可应用于对话系统和行动规划等复杂生成任务，进一步提升其效果。

> Meeting summarization is crucial in digital communication, but existing solutions struggle with salience identification to generate personalized, workable summaries, and context understanding to fully comprehend the meetings' content. Previous attempts to address these issues by considering related supplementary resources (e.g., presentation slides) alongside transcripts are hindered by models' limited context sizes and handling the additional complexities of the multi-source tasks, such as identifying relevant information in additional files and seamlessly aligning it with the meeting content. This work explores multi-source meeting summarization considering supplementary materials through a three-stage large language model approach: identifying transcript passages needing additional context, inferring relevant details from supplementary materials and inserting them into the transcript, and generating a summary from this enriched transcript. Our multi-source approach enhances model understanding, increasing summary relevance by ~9% and producing more content-rich outputs. We introduce a personalization protocol that extracts participant characteristics and tailors summaries accordingly, improving informativeness by ~10%. This work further provides insights on performance-cost trade-offs across four leading model families, including edge-device capable options. Our approach can be extended to similar complex generative tasks benefitting from additional resources and personalization, such as dialogue systems and action planning.

[Arxiv](https://arxiv.org/abs/2410.14545)