# 借助大型语言模型，我们能够对历史死亡数据进行精细编码，揭示过去岁月中生命消逝的种种原因。这一过程不仅是对数据的整理，更是对历史的一次深刻回望。

发布时间：2024年05月13日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在自动化历史死因ICD-10代码分配任务中的应用，这是一个具体的应用场景，涉及到了LLMs在特定数据集上的表现和准确率。虽然文中提到了模型的性能和改进建议，但主要关注点是LLMs在实际任务中的应用，而不是对LLMs理论的深入探讨或Agent的设计与实现，也不是关于检索增强生成（RAG）的研究。因此，根据论文摘要的内容，最合适的分类是LLM应用。` `医疗编码` `历史研究`

> Coding historical causes of death data with Large Language Models

# 摘要

> 本文探讨了预训练的生成式大型语言模型（LLMs）在自动化历史死因ICD-10代码分配任务中的应用潜力。由于历史死因叙述复杂，传统上依赖编码专家手工操作。我们测试了GPT-3.5、GPT-4和Llama 2在HiCaD数据集上的表现，该数据集涵盖了1861至1901年间英国三地的19,361例死亡记录。结果显示，这些模型分别能准确分配69%、83%和40%的ICD-10代码，而传统机器学习方法的准确率可达89%。LLMs对现代术语的死因处理更佳，对简短死因（1-2词）的识别也优于长篇叙述。目前，LLMs在历史死因编码任务上的表现尚不理想，我们建议通过进一步微调或探索新框架来提升其性能。

> This paper investigates the feasibility of using pre-trained generative Large Language Models (LLMs) to automate the assignment of ICD-10 codes to historical causes of death. Due to the complex narratives often found in historical causes of death, this task has traditionally been manually performed by coding experts. We evaluate the ability of GPT-3.5, GPT-4, and Llama 2 LLMs to accurately assign ICD-10 codes on the HiCaD dataset that contains causes of death recorded in the civil death register entries of 19,361 individuals from Ipswich, Kilmarnock, and the Isle of Skye from the UK between 1861-1901. Our findings show that GPT-3.5, GPT-4, and Llama 2 assign the correct code for 69%, 83%, and 40% of causes, respectively. However, we achieve a maximum accuracy of 89% by standard machine learning techniques. All LLMs performed better for causes of death that contained terms still in use today, compared to archaic terms. Also they perform better for short causes (1-2 words) compared to longer causes. LLMs therefore do not currently perform well enough for historical ICD-10 code assignment tasks. We suggest further fine-tuning or alternative frameworks to achieve adequate performance.

[Arxiv](https://arxiv.org/abs/2405.07560)