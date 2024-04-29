# 借助超大型语言模型，我们能够对谣言进行评估。

发布时间：2024年04月11日

`LLM应用` `社交媒体` `信息安全`

> Rumour Evaluation with Very Large Language Models

# 摘要

> 对话式提示工程的LLMs为输出创造提供了精准控制，提升了模型的多功能性、适应性和即兴检索能力。然而，数字虚假信息的泛滥已引起社会广泛关注。社交媒体的匿名性、易得性和广泛传播为谣言的滋生提供了温床。本研究旨在借助先进的提示依赖型LLMs，通过扩展RumourEval任务在Twitter数据集上的研究，来对抗虚假信息。我们采用了两种基于提示的LLM变种（GPT-3.5-turbo和GPT-4），对RumourEval的两个子任务进行了扩展：（1）真实性预测；（2）立场分类。在真实性预测方面，我们对每个GPT变种进行了三种不同分类方案的实验，并在零次、一次和少次的设置中进行了测试。我们的最佳成绩显著超过了以往的成果。在立场分类方面，基于提示的方法与之前的结果相当，但并未超过微调方法的效果。此外，谣言立场子任务也被扩展，支持多类分类。所有生成的预测结果都附带了置信度评分，这些评分由LLM提供，用以评估其可信度，并附有事后解释，以增强模型的可解释性和可解释性。我们的核心宗旨是利用人工智能服务于社会公益。

> Conversational prompt-engineering-based large language models (LLMs) have enabled targeted control over the output creation, enhancing versatility, adaptability and adhoc retrieval. From another perspective, digital misinformation has reached alarming levels. The anonymity, availability and reach of social media offer fertile ground for rumours to propagate. This work proposes to leverage the advancement of prompting-dependent LLMs to combat misinformation by extending the research efforts of the RumourEval task on its Twitter dataset. To the end, we employ two prompting-based LLM variants (GPT-3.5-turbo and GPT-4) to extend the two RumourEval subtasks: (1) veracity prediction, and (2) stance classification. For veracity prediction, three classifications schemes are experimented per GPT variant. Each scheme is tested in zero-, one- and few-shot settings. Our best results outperform the precedent ones by a substantial margin. For stance classification, prompting-based-approaches show comparable performance to prior results, with no improvement over finetuning methods. Rumour stance subtask is also extended beyond the original setting to allow multiclass classification. All of the generated predictions for both subtasks are equipped with confidence scores determining their trustworthiness degree according to the LLM, and post-hoc justifications for explainability and interpretability purposes. Our primary aim is AI for social good.

[Arxiv](https://arxiv.org/abs/2404.16859)