# 定向领域微调：针对特定训练任务，精细调整不同模态

发布时间：2024年06月24日

`LLM应用

这篇论文摘要描述了一种针对特定领域任务定制教学数据集，并利用LORA技术微调大型语言模型（LLMs）和大型视觉语言模型（LVLMs）参数的方法。这种方法旨在提高模型在特定任务上的性能，如文本生成、视频字幕和问答等。通过精细化的微调，模型在特定数据集上的表现得到了显著提升。这与LLM应用的分类相符，因为它关注的是如何应用LLMs来提高特定任务的性能，而不是探讨LLMs的理论基础或Agent的行为，也不是关于检索增强生成（RAG）的具体应用。` `人工智能`

> Directed Domain Fine-Tuning: Tailoring Separate Modalities for Specific Training Tasks

# 摘要

> 大型语言模型（LLMs）和大型视觉语言模型（LVLMs）在人工智能领域，尤其是在文本生成、视频字幕和问答等任务中，一直处于领先地位。传统上，为了增强泛化能力、理解主题间的关系和识别模式，这些模型通常在广泛的知识库或数据集上进行训练。然而，我们提出了一种新方法：为特定领域的不同模态任务定制教学数据集，并利用LORA技术微调模型参数。这种方法不仅消除了与任务无关的噪声，还显著提升了模型生成内容的精确度。以Video-LLaVA为例，我们通过其多模态架构，将烹饪图像、视频和问题分别输入到相应的编码器中，专注于烹饪相关信息的提取和处理。通过这种精细化的微调，我们的模型在YouCook2数据集上的表现比原始版本提升了2%，尽管训练数据集的大小仅为原始的2.5%和23.76%。

> Large language models (LLMs) and large visual language models (LVLMs) have been at the forefront of the artificial intelligence field, particularly for tasks like text generation, video captioning, and question-answering. Typically, it is more applicable to train these models on broader knowledge bases or datasets to increase generalizability, learn relationships between topics, and recognize patterns. Instead, we propose to provide instructional datasets specific to the task of each modality within a distinct domain and then fine-tune the parameters of the model using LORA. With our approach, we can eliminate all noise irrelevant to the given task while also ensuring that the model generates with enhanced precision. For this work, we use Video-LLaVA to generate recipes given cooking videos without transcripts. Video-LLaVA's multimodal architecture allows us to provide cooking images to its image encoder, cooking videos to its video encoder, and general cooking questions to its text encoder. Thus, we aim to remove all noise unrelated to cooking while improving our model's capabilities to generate specific ingredient lists and detailed instructions. As a result, our approach to fine-tuning Video-LLaVA leads to gains over the baseline Video-LLaVA by 2% on the YouCook2 dataset. While this may seem like a marginal increase, our model trains on an image instruction dataset 2.5% the size of Video-LLaVA's and a video instruction dataset 23.76% of Video-LLaVA's.

[Arxiv](https://arxiv.org/abs/2406.16346)