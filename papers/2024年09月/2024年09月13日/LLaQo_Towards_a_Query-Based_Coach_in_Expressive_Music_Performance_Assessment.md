# LLaQo：迈向基于查询的教练，助力表现性音乐表演评估

发布时间：2024年09月13日

`LLM应用` `音乐教育` `人工智能`

> LLaQo: Towards a Query-Based Coach in Expressive Music Performance Assessment

# 摘要

> 音乐理解研究已深入探索了作曲级属性，如键、流派和乐器，推动了大型语言模型的跨模态应用。然而，音乐表演的风格表达和技术仍待深入研究，同时，利用大型语言模型提供定制反馈以提升教育成果的潜力也未被充分挖掘。为此，我们推出了LLaQo，一个基于大型语言查询的音乐教练，通过音频语言建模提供细致入微的表演评估。我们还设计了指令调优的查询-响应数据集，涵盖音高准确性到发音等多个表演维度，以及表演的上下文理解。结合AudioMAE编码器和Vicuna-7b LLM后端，我们的模型在预测教师评分、识别作品难度和演奏技术方面表现卓越。用户研究显示，LLaQo的文本响应在音频-文本匹配测试中显著优于其他模型。因此，LLaQo能从音频数据中提供与音乐表演相关的详尽答案。

> Research in music understanding has extensively explored composition-level attributes such as key, genre, and instrumentation through advanced representations, leading to cross-modal applications using large language models. However, aspects of musical performance such as stylistic expression and technique remain underexplored, along with the potential of using large language models to enhance educational outcomes with customized feedback. To bridge this gap, we introduce LLaQo, a Large Language Query-based music coach that leverages audio language modeling to provide detailed and formative assessments of music performances. We also introduce instruction-tuned query-response datasets that cover a variety of performance dimensions from pitch accuracy to articulation, as well as contextual performance understanding (such as difficulty and performance techniques). Utilizing AudioMAE encoder and Vicuna-7b LLM backend, our model achieved state-of-the-art (SOTA) results in predicting teachers' performance ratings, as well as in identifying piece difficulty and playing techniques. Textual responses from LLaQo was moreover rated significantly higher compared to other baseline models in a user study using audio-text matching. Our proposed model can thus provide informative answers to open-ended questions related to musical performance from audio data.

[Arxiv](https://arxiv.org/abs/2409.08795)