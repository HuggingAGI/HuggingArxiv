# MeaCap 是一种“记忆增强型零样本图像描述”技术，它利用记忆机制提升在未见过的图像上进行自动描述的能力。

发布时间：2024年03月06日

`Agent`

> MeaCap: Memory-Augmented Zero-shot Image Captioning

> 对于无需配对图像-文本数据的零样本图像描述任务，研究将其策略划分为两大阵营：免训练法和纯文本训练法。两者均借助预训练的视觉-语言模型（如CLIP）评估图像与文本的相似度，并采用预训练语言模型生成描述，不过后者会额外利用文本语料库进行训练。尽管这些方法在部分评价指标上表现抢眼，但普遍存在短板：免训练方法容易产生不实描述，而纯文本训练法则可能丧失对新场景的适应能力。为此，本文创新性地提出了“记忆增强零样本图像描述框架”——MeaCap。该框架内置文本记忆模块，通过独特的检索-筛选机制锁定与图像紧密关联的关键概念，并将我们设计的记忆增强视觉相关融合得分应用于关键词到完整句子的语言模型中，使得MeaCap生成的描述既能紧扣图像核心概念，又能减少臆想成分、融入更多真实世界的知识。最终，MeaCap在一系列零样本图像描述任务上刷新了当前最优性能记录，其代码已开源至https://github.com/joeyz0z/MeaCap。

> Zero-shot image captioning (IC) without well-paired image-text data can be divided into two categories, training-free and text-only-training. Generally, these two types of methods realize zero-shot IC by integrating pretrained vision-language models like CLIP for image-text similarity evaluation and a pre-trained language model (LM) for caption generation. The main difference between them is whether using a textual corpus to train the LM. Though achieving attractive performance w.r.t. some metrics, existing methods often exhibit some common drawbacks. Training-free methods tend to produce hallucinations, while text-only-training often lose generalization capability. To move forward, in this paper, we propose a novel Memory-Augmented zero-shot image Captioning framework (MeaCap). Specifically, equipped with a textual memory, we introduce a retrieve-then-filter module to get key concepts that are highly related to the image. By deploying our proposed memory-augmented visual-related fusion score in a keywords-to-sentence LM, MeaCap can generate concept-centered captions that keep high consistency with the image with fewer hallucinations and more world-knowledge. The framework of MeaCap achieves the state-of-the-art performance on a series of zero-shot IC settings. Our code is available at https://github.com/joeyz0z/MeaCap.

[Arxiv](https://arxiv.org/abs/2403.03715)