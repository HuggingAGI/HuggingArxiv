# Yo'LLaVA：专属于您的语言与视觉智能伴侣

发布时间：2024年06月13日

`Agent

理由：这篇论文介绍了一个新的系统（Yo'LLaVA），该系统能够通过个性化主题进行交流，并使用示例图像来嵌入个性化主题到潜在令牌中。这种系统的行为类似于一个智能代理（Agent），因为它能够根据特定的输入（如示例图像）来调整其行为和输出，以适应特定的任务或情境。这与Agent的定义相符，即一个能够感知环境并采取行动以达到目标的系统。因此，这篇论文更适合归类为Agent。` `个性化服务` `人工智能`

> Yo'LLaVA: Your Personalized Language and Vision Assistant

# 摘要

> 大型多模态模型（LMMs）在图像描述、视觉问答等任务上表现出色，但它们对知识的理解仍停留在通用层面，如识别一只狗，却难以识别特定个体的宠物狗。人类推理则更倾向于在具体情境中进行，例如，人们更关心“我应该为我的狗的生日买什么？”而非泛泛而谈。本文提出了一项新任务，即个性化LMMs，使其能就特定主题进行交流。我们开发的Yo'LLaVA系统，通过少量示例图像，将个性化主题嵌入到潜在令牌中，实现了更高效的概念学习和更优的视觉属性编码，超越了现有的强大提示方法。

> Large Multimodal Models (LMMs) have shown remarkable capabilities across a variety of tasks (e.g., image captioning, visual question answering). While broad, their knowledge remains generic (e.g., recognizing a dog), and they are unable to handle personalized subjects (e.g., recognizing a user's pet dog). Human reasoning, in contrast, typically operates within the context of specific subjects in our surroundings. For example, one might ask, "What should I buy for my dog's birthday?"; as opposed to a generic inquiry about "What should I buy for a dog's birthday?". Similarly, when looking at a friend's image, the interest lies in seeing their activities (e.g., "my friend is holding a cat"), rather than merely observing generic human actions (e.g., "a man is holding a cat"). In this paper, we introduce the novel task of personalizing LMMs, so that they can have conversations about a specific subject. We propose Yo'LLaVA, which learns to embed a personalized subject into a set of latent tokens given a handful of example images of the subject. Our qualitative and quantitative analyses reveal that Yo'LLaVA can learn the concept more efficiently using fewer tokens and more effectively encode the visual attributes compared to strong prompting baselines (e.g., LLaVA).

![Yo'LLaVA：专属于您的语言与视觉智能伴侣](../../../paper_images/2406.09400/x1.png)

![Yo'LLaVA：专属于您的语言与视觉智能伴侣](../../../paper_images/2406.09400/x2.png)

![Yo'LLaVA：专属于您的语言与视觉智能伴侣](../../../paper_images/2406.09400/x3.png)

![Yo'LLaVA：专属于您的语言与视觉智能伴侣](../../../paper_images/2406.09400/x5.png)

![Yo'LLaVA：专属于您的语言与视觉智能伴侣](../../../paper_images/2406.09400/mam.png)

![Yo'LLaVA：专属于您的语言与视觉智能伴侣](../../../paper_images/2406.09400/bo.png)

[Arxiv](https://arxiv.org/abs/2406.09400)