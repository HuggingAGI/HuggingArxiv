# 语义手势者：一种能够感知语义并同步生成语言手势的系统

发布时间：2024年05月16日

`Agent

解释：这篇论文介绍了一个名为Semantic Gesticulator的框架，它利用大型语言模型（LLM）来生成与语音紧密相连的真实手势。这个框架可以被视为一个智能代理（Agent），因为它能够根据语音内容和节奏生成相应的手势，从而实现非言语沟通。它通过一个生成检索系统来选择合适的手势，并使用基于GPT的模型来确保手势的自然性和语义适当性。这个系统的设计和功能表明它是一个能够自主执行任务的智能系统，因此归类为Agent。` `人机交互` `虚拟现实`

> Semantic Gesticulator: Semantics-Aware Co-Speech Gesture Synthesis

# 摘要

> 我们推出了Semantic Gesticulator框架，旨在创造与语音紧密相连的真实手势。这些富含语义的手势对于非言语沟通至关重要，但它们往往隐藏在人类动作的稀疏角落。为了克服这一难题，我们利用大型语言模型构建了一个生成检索系统，它能从动作库中精准挑选出与语音相匹配的手势。我们的动作库基于语言学研究精心编制，包含了一系列高质量的身体和手部动作数据。我们还开发了一个基于GPT的模型，它能根据语音节奏生成逼真的手势，并通过语义对齐机制确保手势与语音的和谐统一。用户研究证实，我们的系统不仅手势自然，而且在语义适当性上超越了现有技术。

> In this work, we present Semantic Gesticulator, a novel framework designed to synthesize realistic gestures accompanying speech with strong semantic correspondence. Semantically meaningful gestures are crucial for effective non-verbal communication, but such gestures often fall within the long tail of the distribution of natural human motion. The sparsity of these movements makes it challenging for deep learning-based systems, trained on moderately sized datasets, to capture the relationship between the movements and the corresponding speech semantics. To address this challenge, we develop a generative retrieval framework based on a large language model. This framework efficiently retrieves suitable semantic gesture candidates from a motion library in response to the input speech. To construct this motion library, we summarize a comprehensive list of commonly used semantic gestures based on findings in linguistics, and we collect a high-quality motion dataset encompassing both body and hand movements. We also design a novel GPT-based model with strong generalization capabilities to audio, capable of generating high-quality gestures that match the rhythm of speech. Furthermore, we propose a semantic alignment mechanism to efficiently align the retrieved semantic gestures with the GPT's output, ensuring the naturalness of the final animation. Our system demonstrates robustness in generating gestures that are rhythmically coherent and semantically explicit, as evidenced by a comprehensive collection of examples. User studies confirm the quality and human-likeness of our results, and show that our system outperforms state-of-the-art systems in terms of semantic appropriateness by a clear margin.

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x1.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x2.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x3.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x4.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x5.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x6.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x7.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x8.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x9.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x10.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x11.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x12.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x13.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x14.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x15.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x16.png)

![语义手势者：一种能够感知语义并同步生成语言手势的系统](../../../paper_images/2405.09814/x17.png)

[Arxiv](https://arxiv.org/abs/2405.09814)