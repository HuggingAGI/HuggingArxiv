# SoftTiger，作为一款专为医疗工作流程打造的临床基础模型，旨在提升医疗服务效率与质量。

发布时间：2024年02月29日

`LLM应用`

> SoftTiger: A Clinical Foundation Model for Healthcare Workflows

> 我们推出了 SoftTiger——一款专为医疗保健流程设计的基础型临床大模型（CLaM），旨在攻克医疗智能化进程中的核心难题——临床笔记的叙事性与非结构化特征。为了遵循国际互操作性标准，我们针对国际患者概要、临床印象和医疗就诊记录这三个关键细分任务收集并标注了相关数据，并利用公有及权威认证的临床数据，对最先进的 LLM 进行精细调整训练。训练过程中，模型先学会处理如缩写展开、时间信息抽取等基础临床任务，进而习得完成印象总结、就诊记录总结等复杂下游临床任务的能力。同时，我们还成功应对了医疗场景下的一些特殊建模挑战，比如超长上下文窗口。经过盲比测试，SoftTiger 表现优于众多主流开源模型及 GPT-3.5，并且与 Gemini-pro 媲美，距离 GPT-4 的差距也十分微小。我们坚信 LLM 将成为推动医疗保健行业数字化和普惠化进程的重要基石。因此，我们决定公开发布规模分别为 130 亿和 700 亿参数的 SoftTiger 模型，同时提供创新可扩展评估所需的数据集和代码，力求为医疗保健产业带来显著的价值提升。

> We release and introduce SoftTiger, a clinical large language model (CLaM) designed as a foundation model for healthcare workflows. The narrative and unstructured nature of clinical notes is a major obstacle for healthcare intelligentization. We address a critical problem of structuring clinical notes into clinical data, according to international interoperability standards. We collect and annotate data for three critical subtasks, namely, international patient summary, clinical impression and medical encounter. We then supervised fine-tuned a state-of-the-art LLM using public and credentialed clinical data. The training is orchestrated in a way that the target model can first support basic clinical tasks such as abbreviation expansion and temporal information extraction, and then learn to perform more complex downstream clinical tasks such as impression and encounter summary. Moreover, we address, several modeling challenges in the healthcare context, e.g., extra long context window. Our blind pairwise evaluation shows that SoftTiger outperforms other popular open-source models and GPT-3.5, comparable to Gemini-pro, and only has a mild gap from GPT-4. We believe that LLMs may become a step-stone towards healthcare digitalization and democratization. Therefore, we publicly release SoftTiger models at scales of 13 billion and 70 billion parameters, as well as datasets and code for our innovative scalable evaluation, hopefully, making a significant contribution to the healthcare industry.

[Arxiv](https://arxiv.org/abs/2403.00868)