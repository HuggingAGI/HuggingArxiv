# LaB-RAG：用于放射学报告生成的标签增强式检索增强生成

发布时间：2024年11月25日

`RAG` `图像描述`

> LaB-RAG: Label Boosted Retrieval Augmented Generation for Radiology Report Generation

# 摘要

> 在当下的图像描述模式中，深度学习模型被训练从潜在特征的图像嵌入来生成文本。我们对这些潜在特征应为高维向量且需要模型微调处理的观点提出质疑。在此，我们提出了标签增强检索增强生成（LaB-RAG），这是一种基于文本的图像描述方法，借助分类标签形式的图像描述符来增强配备预训练大型语言模型（LLMs）的标准检索增强生成（RAG）。我们在放射学报告生成（RRG）的情境中研究此方法，其任务是依据一组放射图像（如 X 光片）生成详述临床医生观察结果的报告。我们认为，针对提取的图像嵌入的简单线性分类器能够有效地将 X 光转化为文本空间，形成特定于放射学的标签。结合标准 RAG，我们表明这些派生的文本标签能与通用领域的 LLMs 共同用于生成放射学报告。在从未训练生成语言模型或图像特征编码器模型，也从未直接向 LLM 展示 X 光的情况下，我们证明，与其他基于检索的 RRG 方法相比，LaB-RAG 在自然语言和放射学语言指标上表现更优，同时与其他微调的视觉语言 RRG 模型相比也取得了颇具竞争力的结果。我们进一步展示了 LaB-RAG 各组件的实验结果，以更好地理解我们的方法。最后，我们对一种流行的 RRG 指标的使用予以批判，认为有可能在无真实数据泄露的情况下人为抬高其结果。

> In the current paradigm of image captioning, deep learning models are trained to generate text from image embeddings of latent features. We challenge the assumption that these latent features ought to be high-dimensional vectors which require model fine tuning to handle. Here we propose Label Boosted Retrieval Augmented Generation (LaB-RAG), a text-based approach to image captioning that leverages image descriptors in the form of categorical labels to boost standard retrieval augmented generation (RAG) with pretrained large language models (LLMs). We study our method in the context of radiology report generation (RRG), where the task is to generate a clinician's report detailing their observations from a set of radiological images, such as X-rays. We argue that simple linear classifiers over extracted image embeddings can effectively transform X-rays into text-space as radiology-specific labels. In combination with standard RAG, we show that these derived text labels can be used with general-domain LLMs to generate radiology reports. Without ever training our generative language model or image feature encoder models, and without ever directly "showing" the LLM an X-ray, we demonstrate that LaB-RAG achieves better results across natural language and radiology language metrics compared with other retrieval-based RRG methods, while attaining competitive results compared to other fine-tuned vision-language RRG models. We further present results of our experiments with various components of LaB-RAG to better understand our method. Finally, we critique the use of a popular RRG metric, arguing it is possible to artificially inflate its results without true data-leakage.

[Arxiv](https://arxiv.org/abs/2411.16523)