# 锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置

发布时间：2024年04月15日

`LLM应用` `图像合成`

> ANCHOR: LLM-driven News Subject Conditioning for Text-to-Image Synthesis

# 摘要

> 文本到图像合成技术已大幅提升图像质量，但现有评估多依赖于描述性指令。新闻图片标题则更注重实用性，提供丰富的情境和命名实体信息，而非具体物体描述，呈现出抽象性。为此，我们推出了抽象新闻标题与高层次上下文表示（ANCHOR）数据集，收集了5家新闻机构的70,000多个样本，旨在测试T2I模型对新闻标题中主题的捕捉能力。借助大型语言模型在语言和常识推理上的卓越表现，我们研究了不同LLM在解析抽象标题中关键主题的能力。我们提出的“主题感知微调”（SAFE）方法，通过LLM生成的主题权重来提升合成图像中关键主题的表现，并针对新闻图像和标题的领域分布进行定制化微调，其在ANCHOR数据集上的表现超越了现有技术。发布ANCHOR数据集，我们期望推动T2I模型自然语言理解能力的进一步研究。

> Text-to-Image (T2I) Synthesis has made tremendous strides in enhancing synthesized image quality, but current datasets evaluate model performance only on descriptive, instruction-based prompts. Real-world news image captions take a more pragmatic approach, providing high-level situational and Named-Entity (NE) information and limited physical object descriptions, making them abstractive. To evaluate the ability of T2I models to capture intended subjects from news captions, we introduce the Abstractive News Captions with High-level cOntext Representation (ANCHOR) dataset, containing 70K+ samples sourced from 5 different news media organizations. With Large Language Models (LLM) achieving success in language and commonsense reasoning tasks, we explore the ability of different LLMs to identify and understand key subjects from abstractive captions. Our proposed method Subject-Aware Finetuning (SAFE), selects and enhances the representation of key subjects in synthesized images by leveraging LLM-generated subject weights. It also adapts to the domain distribution of news images and captions through custom Domain Fine-tuning, outperforming current T2I baselines on ANCHOR. By launching the ANCHOR dataset, we hope to motivate research in furthering the Natural Language Understanding (NLU) capabilities of T2I models.

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/abstractive_example.png)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/dataset_preprocess.png)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/model_arch.png)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/70ee9fb70d37464a5a557fe5a18ea3c30ead034af4b81af2177ae053b6c2194f.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/70ee9fb70d37464a5a557fe5a18ea3c30ead034af4b81af2177ae053b6c2194f.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/70ee9fb70d37464a5a557fe5a18ea3c30ead034af4b81af2177ae053b6c2194f.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/70ee9fb70d37464a5a557fe5a18ea3c30ead034af4b81af2177ae053b6c2194f.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/fac3d2f4be9b67f5c3de73db737ca469dc851d953c4be45afbd8ca64cef8c94f.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/fac3d2f4be9b67f5c3de73db737ca469dc851d953c4be45afbd8ca64cef8c94f.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/fac3d2f4be9b67f5c3de73db737ca469dc851d953c4be45afbd8ca64cef8c94f.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/fac3d2f4be9b67f5c3de73db737ca469dc851d953c4be45afbd8ca64cef8c94f.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/1577174bbc.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/1577174bbc.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/1577174bbc.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/1577174bbc.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/article_topics.png)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/abstractive-eval-quest.png)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/gen-eval-ques.png)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/61772washington_post.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/61772washington_post.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/61772washington_post.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/595103guardian.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/595103guardian.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/595103guardian.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/149871washington_post.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/149871washington_post.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/149871washington_post.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/685007guardian.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/685007guardian.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/685007guardian.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/1183194guardian.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/1183194guardian.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/1183194guardian.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/1183194guardian.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/727f4b7a97e3e60d19822c61d70d00fed8444ca1dca2ef3cf23d9351ddff06c1.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/727f4b7a97e3e60d19822c61d70d00fed8444ca1dca2ef3cf23d9351ddff06c1.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/727f4b7a97e3e60d19822c61d70d00fed8444ca1dca2ef3cf23d9351ddff06c1.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/727f4b7a97e3e60d19822c61d70d00fed8444ca1dca2ef3cf23d9351ddff06c1.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/e812925fa4ccc10b148af456663a01a1069c45b3aca1f84928479f5b6698b84f.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/e812925fa4ccc10b148af456663a01a1069c45b3aca1f84928479f5b6698b84f.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/e812925fa4ccc10b148af456663a01a1069c45b3aca1f84928479f5b6698b84f.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/e812925fa4ccc10b148af456663a01a1069c45b3aca1f84928479f5b6698b84f.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/a9e14e37383d1ae1a0b47e45e26131f9bd586c5131310af768e40a2475bac7e4.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/a9e14e37383d1ae1a0b47e45e26131f9bd586c5131310af768e40a2475bac7e4.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/a9e14e37383d1ae1a0b47e45e26131f9bd586c5131310af768e40a2475bac7e4.jpg)

![锚定：借助大型语言模型实现文本至图像合成中的新闻主题条件设置](../../../paper_images/2404.10141/a9e14e37383d1ae1a0b47e45e26131f9bd586c5131310af768e40a2475bac7e4.jpg)

[Arxiv](https://arxiv.org/abs/2404.10141)