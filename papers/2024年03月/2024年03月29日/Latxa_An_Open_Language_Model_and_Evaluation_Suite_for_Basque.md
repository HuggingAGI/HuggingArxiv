# Latxa：巴斯克语的开源语言模型与评估工具集

发布时间：2024年03月29日

`LLM应用` `语言模型` `低资源语言`

> Latxa: An Open Language Model and Evaluation Suite for Basque

# 摘要

> 我们自豪地推出Latxa，这是一系列巴斯克语的大型语言模型，参数量从7亿到700亿不等。Latxa继承自Llama 2，并在此基础上，我们利用包含430万文档和42亿标记的新巴斯克语文本进行了预训练。针对巴斯克语高质量基准资源的匮乏，我们新增了4个多项选择评估数据集：EusProficiency，涵盖5169道官方语言能力测试题目；EusReading，包含352道阅读理解题目；EusTrivia，囊括5个知识领域的1715个趣味问题；以及EusExams，源自公共考试的16774道题目。经过广泛评估，Latxa在性能上大幅超越了所有先前的开放模型。并且，尽管在阅读理解和知识密集型任务上略逊于GPT-4 Turbo，但在语言熟练度和理解能力方面，Latxa展现出了竞争力。Latxa模型家族、新的预训练语料库和评估数据集均已在https://github.com/hitz-zentroa/latxa上以开源许可形式发布，助力低资源语言大型语言模型构建方法的可复制研究。

> We introduce Latxa, a family of large language models for Basque ranging from 7 to 70 billion parameters. Latxa is based on Llama 2, which we continue pretraining on a new Basque corpus comprising 4.3M documents and 4.2B tokens. Addressing the scarcity of high-quality benchmarks for Basque, we further introduce 4 multiple choice evaluation datasets: EusProficiency, comprising 5,169 questions from official language proficiency exams; EusReading, comprising 352 reading comprehension questions; EusTrivia, comprising 1,715 trivia questions from 5 knowledge areas; and EusExams, comprising 16,774 questions from public examinations. In our extensive evaluation, Latxa outperforms all previous open models we compare to by a large margin. In addition, it is competitive with GPT-4 Turbo in language proficiency and understanding, despite lagging behind in reading comprehension and knowledge-intensive tasks. Both the Latxa family of models, as well as our new pretraining corpora and evaluation datasets, are publicly available under open licenses at https://github.com/hitz-zentroa/latxa. Our suite enables reproducible research on methods to build LLMs for low-resource languages.

[Arxiv](https://arxiv.org/abs/2403.20266)