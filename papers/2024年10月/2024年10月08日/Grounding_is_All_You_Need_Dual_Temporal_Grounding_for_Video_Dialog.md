# “定位”是否足够？探讨视频对话中的双重时间定位技术。

发布时间：2024年10月08日

`LLM应用` `视频对话` `人工智能`

> Grounding is All You Need? Dual Temporal Grounding for Video Dialog

# 摘要

> 在视频对话生成领域，理解视频内容和对话历史的时间细节至关重要。当前研究中，一部分过于依赖大规模预训练模型而忽视时间动态，另一部分则深入研究视频的时空关系，但需复杂预处理且忽略对话时间动态。本文提出双时间基础增强视频对话模型（DTGVD），巧妙融合两种方法的优势。DTGVD通过预测对话轮次特定的时间区域，过滤视频内容，并在视频和对话上下文中定位响应，强调双重时间关系。其独特之处在于高度关注时间顺序的相互作用，通过识别和处理对话轮次间的依赖，捕捉更细腻的对话动态。为增强视频与对话时间动态的一致性，我们采用列表式对比学习策略，将准确的时间片段对设为正样本，不精确的设为负样本，并将其融入端到端响应生成机制。AVSD@DSTC-7和AVSD@DSTC-8数据集的评估结果显示，我们的方法表现卓越。

> In the realm of video dialog response generation, the understanding of video content and the temporal nuances of conversation history are paramount. While a segment of current research leans heavily on large-scale pretrained visual-language models and often overlooks temporal dynamics, another delves deep into spatial-temporal relationships within videos but demands intricate object trajectory pre-extractions and sidelines dialog temporal dynamics. This paper introduces the Dual Temporal Grounding-enhanced Video Dialog model (DTGVD), strategically designed to merge the strengths of both dominant approaches. It emphasizes dual temporal relationships by predicting dialog turn-specific temporal regions, filtering video content accordingly, and grounding responses in both video and dialog contexts. One standout feature of DTGVD is its heightened attention to chronological interplay. By recognizing and acting upon the dependencies between different dialog turns, it captures more nuanced conversational dynamics. To further bolster the alignment between video and dialog temporal dynamics, we've implemented a list-wise contrastive learning strategy. Within this framework, accurately grounded turn-clip pairings are designated as positive samples, while less precise pairings are categorized as negative. This refined classification is then funneled into our holistic end-to-end response generation mechanism. Evaluations using AVSD@DSTC-7 and AVSD@DSTC-8 datasets underscore the superiority of our methodology.

[Arxiv](https://arxiv.org/abs/2410.05767)