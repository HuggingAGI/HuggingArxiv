# 我们真的需要一个 LLM+VQA 系统来识别视觉概念吗？

发布时间：2024年10月17日

`LLM应用` `人工智能` `计算机视觉`

> Help Me Identify: Is an LLM+VQA System All We Need to Identify Visual Concepts?

# 摘要

> 人类能从少量视觉数据中学习新对象，并能对新颖场景中某些概念的存在与否给出令人信服的语言解释，这是人类认知的重要特征。例如，通过喙、羽毛等特征，我们能识别出“鸟”。受此启发，我们提出了一种零样本学习框架，结合大型语言模型和视觉问答系统，进行细粒度视觉概念学习。我们利用 GPT-3 生成视觉对象的详细描述，并将其转化为二进制问题，通过 VQA 系统解答，从而判断对象在测试图像中的存在与否。实验结果显示，我们的方法在性能上与现有零样本和少样本学习方法相当，且计算开销小，推理过程完全透明。

> An ability to learn about new objects from a small amount of visual data and produce convincing linguistic justification about the presence/absence of certain concepts (that collectively compose the object) in novel scenarios is an important characteristic of human cognition. This is possible due to abstraction of attributes/properties that an object is composed of e.g. an object `bird' can be identified by the presence of a beak, feathers, legs, wings, etc. Inspired by this aspect of human reasoning, in this work, we present a zero-shot framework for fine-grained visual concept learning by leveraging large language model and Visual Question Answering (VQA) system. Specifically, we prompt GPT-3 to obtain a rich linguistic description of visual objects in the dataset. We convert the obtained concept descriptions into a set of binary questions. We pose these questions along with the query image to a VQA system and aggregate the answers to determine the presence or absence of an object in the test images. Our experiments demonstrate comparable performance with existing zero-shot visual classification methods and few-shot concept learning approaches, without substantial computational overhead, yet being fully explainable from the reasoning perspective.

[Arxiv](https://arxiv.org/abs/2410.13651)