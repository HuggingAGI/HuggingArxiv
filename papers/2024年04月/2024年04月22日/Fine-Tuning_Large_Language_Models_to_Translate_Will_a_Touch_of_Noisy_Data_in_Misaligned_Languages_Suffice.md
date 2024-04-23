# 微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？

发布时间：2024年04月22日

`分类：LLM应用` `机器翻译`

> Fine-Tuning Large Language Models to Translate: Will a Touch of Noisy Data in Misaligned Languages Suffice?

# 摘要

> 在多语言机器翻译领域，成功的关键在于训练数据的三个要素：海量数据、多向翻译和优质内容。在对大型语言模型（LLMs）进行微调以优化翻译性能的实践中，这些因素的重要性再次得到验证。研究表明，即便是基于32个训练样本进行微调，LLMs也能显著提升翻译能力，并且单向翻译的微调足以让LLMs掌握多向翻译技能。然而，翻译方向的选择极为关键，以英语作为目标语言进行微调可能导致任务理解偏差，影响非英语语言的翻译效果。此外，当目标语言在LLM的预训练中占据重要地位时，平行语料中的噪声会对翻译质量产生显著影响。相反，对于在预训练中占比较少的语言，噪声的影响则不那么严重。这些发现提示我们，要实现精准的翻译对齐，需要训练模型保持适度的关注，避免学习到翻译之外的错误偏差。

> Traditionally, success in multilingual machine translation can be attributed to three key factors in training data: large volume, diverse translation directions, and high quality. In the current practice of fine-tuning large language models (LLMs) for translation, we revisit the importance of all these factors. We find that LLMs display strong translation capability after being fine-tuned on as few as 32 training instances, and that fine-tuning on a single translation direction effectively enables LLMs to translate in multiple directions. However, the choice of direction is critical: fine-tuning LLMs with English on the target side can lead to task misinterpretation, which hinders translations into non-English languages. A similar problem arises when noise is introduced into the target side of parallel data, especially when the target language is well-represented in the LLM's pre-training. In contrast, noise in an under-represented language has a less pronounced effect. Our findings suggest that attaining successful alignment hinges on teaching the model to maintain a "superficial" focus, thereby avoiding the learning of erroneous biases beyond translation.

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x1.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x2.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x3.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x4.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x5.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x6.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x7.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x8.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x9.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x10.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x11.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x12.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x13.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x14.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x15.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x16.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x17.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x18.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x19.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x20.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x21.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x22.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x23.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x24.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x25.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x26.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x27.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x28.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x29.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x30.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x31.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x32.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x33.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x34.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x35.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x36.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x37.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x38.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x39.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x40.png)

![微调大型语言模型以实现翻译：仅需在不匹配的语言中掺入少量噪声数据，是否就已足够？](../../../paper_images/2404.14122/x41.png)

[Arxiv](https://arxiv.org/abs/2404.14122)