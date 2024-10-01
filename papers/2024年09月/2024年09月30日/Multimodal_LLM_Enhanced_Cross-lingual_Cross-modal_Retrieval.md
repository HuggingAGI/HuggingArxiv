# 多模态 LLM 助力跨语言跨模态检索

发布时间：2024年09月30日

`LLM应用` `跨语言检索` `视觉内容分析`

> Multimodal LLM Enhanced Cross-lingual Cross-modal Retrieval

# 摘要

> 跨语言跨模态检索 (CCR) 旨在通过非英语查询检索视觉相关内容，无需依赖人工标注的跨模态数据对。常见方法是通过机器翻译 (MT) 创建伪平行数据对，建立视觉与非英语文本的对应关系。然而，由于视觉与文本的语义差距以及非英语表示的质量问题，对齐这些表示颇具挑战。为此，我们提出了 LECCR，一种结合多模态大语言模型 (MLLM) 的新方法，以改进视觉与非英语表示的对齐。具体来说，我们首先使用 MLLM 生成详细的视觉内容描述，并将其聚合为多视图语义槽。然后，利用这些语义槽与视觉特征交互，增强视觉特征的语义信息，缩小模态间的语义差距，并为后续的多层次匹配生成局部视觉语义。此外，我们还引入了在英语指导下的软化匹配，以进一步增强视觉与非英语特征的对齐。在四个 CCR 基准测试上的实验结果表明，我们的方法效果显著。代码链接：\url{https://github.com/LiJiaBei-7/leccr}。

> Cross-lingual cross-modal retrieval (CCR) aims to retrieve visually relevant content based on non-English queries, without relying on human-labeled cross-modal data pairs during training. One popular approach involves utilizing machine translation (MT) to create pseudo-parallel data pairs, establishing correspondence between visual and non-English textual data. However, aligning their representations poses challenges due to the significant semantic gap between vision and text, as well as the lower quality of non-English representations caused by pre-trained encoders and data noise. To overcome these challenges, we propose LECCR, a novel solution that incorporates the multi-modal large language model (MLLM) to improve the alignment between visual and non-English representations. Specifically, we first employ MLLM to generate detailed visual content descriptions and aggregate them into multi-view semantic slots that encapsulate different semantics. Then, we take these semantic slots as internal features and leverage them to interact with the visual features. By doing so, we enhance the semantic information within the visual features, narrowing the semantic gap between modalities and generating local visual semantics for subsequent multi-level matching. Additionally, to further enhance the alignment between visual and non-English features, we introduce softened matching under English guidance. This approach provides more comprehensive and reliable inter-modal correspondences between visual and non-English features. Extensive experiments on four CCR benchmarks, \ie Multi30K, MSCOCO, VATEX, and MSR-VTT-CN, demonstrate the effectiveness of our proposed method. Code: \url{https://github.com/LiJiaBei-7/leccr}.

[Arxiv](https://arxiv.org/abs/2409.19961)