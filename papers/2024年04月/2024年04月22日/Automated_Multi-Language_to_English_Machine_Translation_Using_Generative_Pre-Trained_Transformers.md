# 利用生成式预训练变换器实现的自动化多语言至英语机器翻译。

发布时间：2024年04月22日

`LLM应用` `机器翻译` `数据科学`

> Automated Multi-Language to English Machine Translation Using Generative Pre-Trained Transformers

# 摘要

> 语言翻译的精准与高效是信息处理的关键任务，而在机器学习和数据科学领域，追求精确且迅速的机器翻译技术始终备受关注。本研究探讨了利用本地化的生成预训练变换器（GPT）模型，实现自动化的零样本、逐句、多自然语言向英文的黑盒翻译。我们选取了16种不同的开源GPT模型，这些模型均未经过定制化微调，直接从Huggingface的大型语言模型库中获取，并以翻译后的TED演讲稿作为基准数据集，对50种非英语语言进行英文翻译。所有GPT模型的推理过程均在本地的单个A100 Nvidia GPU上独立完成。我们采用BLEU、GLEU、METEOR和chrF等文本重叠度量标准来评估语言翻译的准确性，并记录了每句翻译所需的实际时间。在BLEU评分标准下，ReMM-v2-L2-13B模型以所有测试语言的平均得分$0.152$位居榜首；GLEU评分标准下，同样为ReMM-v2-L2-13B模型，平均得分为$0.256$；chrF评分标准下，Llama2-chat-AYT-13B模型以平均得分$0.448$领先；METEOR评分标准下，ReMM-v2-L2-13B模型以平均得分$0.438$获得最佳表现。

> The task of accurate and efficient language translation is an extremely important information processing task. Machine learning enabled and automated translation that is accurate and fast is often a large topic of interest in the machine learning and data science communities. In this study, we examine using local Generative Pretrained Transformer (GPT) models to perform automated zero shot black-box, sentence wise, multi-natural-language translation into English text. We benchmark 16 different open-source GPT models, with no custom fine-tuning, from the Huggingface LLM repository for translating 50 different non-English languages into English using translated TED Talk transcripts as the reference dataset. These GPT model inference calls are performed strictly locally, on single A100 Nvidia GPUs. Benchmark metrics that are reported are language translation accuracy, using BLEU, GLEU, METEOR, and chrF text overlap measures, and wall-clock time for each sentence translation. The best overall performing GPT model for translating into English text for the BLEU metric is ReMM-v2-L2-13B with a mean score across all tested languages of $0.152$, for the GLEU metric is ReMM-v2-L2-13B with a mean score across all tested languages of $0.256$, for the chrF metric is Llama2-chat-AYT-13B with a mean score across all tested languages of $0.448$, and for the METEOR metric is ReMM-v2-L2-13B with a mean score across all tested languages of $0.438$.

[Arxiv](https://arxiv.org/abs/2404.14680)