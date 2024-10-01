# TROPE：无需训练的对象-部分增强技术，旨在无缝提升细粒度零-shot 图像描述的性能。

发布时间：2024年09月30日

`LLM应用` `计算机视觉`

> TROPE: TRaining-Free Object-Part Enhancement for Seamlessly Improving Fine-Grained Zero-Shot Image Captioning

# 摘要

> 零-shot 推理是大模型如 CLIP 的一项令人振奋的能力，无需特定训练数据即可执行任务。尽管在图像字幕生成方面，针对 MSCOCO 和 Flickr8k 等流行数据集的零-shot 能力已有大量研究，但在 CUB、FLO、UCM-Captions 和 Sydney-Captions 等细粒度数据集上，这些方法仍显不足。这些数据集要求字幕能够细致区分视觉和语义相似的类别，关注对象的细节部分及其属性。为此，我们提出了无需训练的对象部分增强技术 (TROPE)。TROPE 通过对象检测器和 NLP 技术，为字幕添加更多对象部分细节，既不改变基础字幕，又能与其他字幕生成方法无缝结合，提供更高的灵活性。评估结果表明，TROPE 在所有测试的零-shot 图像字幕生成方法中均显著提升性能，并在细粒度数据集上达到领先水平。

> Zero-shot inference, where pre-trained models perform tasks without specific training data, is an exciting emergent ability of large models like CLIP. Although there has been considerable exploration into enhancing zero-shot abilities in image captioning (IC) for popular datasets such as MSCOCO and Flickr8k, these approaches fall short with fine-grained datasets like CUB, FLO, UCM-Captions, and Sydney-Captions. These datasets require captions to discern between visually and semantically similar classes, focusing on detailed object parts and their attributes. To overcome this challenge, we introduce TRaining-Free Object-Part Enhancement (TROPE). TROPE enriches a base caption with additional object-part details using object detector proposals and Natural Language Processing techniques. It complements rather than alters the base caption, allowing seamless integration with other captioning methods and offering users enhanced flexibility. Our evaluations show that TROPE consistently boosts performance across all tested zero-shot IC approaches and achieves state-of-the-art results on fine-grained IC datasets.

[Arxiv](https://arxiv.org/abs/2409.19960)