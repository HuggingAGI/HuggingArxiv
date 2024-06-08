# 《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效

发布时间：2024年06月04日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在常识推理方面的局限性，特别是在标准化基准测试之外的表现。论文指出了LLMs在面对简单常识问题时的失败，并强调了这些模型在错误答案上的过度自信以及提供的荒谬解释。此外，论文呼吁重新评估LLMs的能力，并提出需要新的标准化基准来揭示这些模型在推理上的基本缺陷。这些内容主要关注LLMs的理论性能和评估方法，因此属于LLM理论分类。` `人工智能` `常识推理`

> Alice in Wonderland: Simple Tasks Showing Complete Reasoning Breakdown in State-Of-the-Art Large Language Models

# 摘要

> 大型语言模型（LLMs）常被视为基础模型的典范，它们在多种任务和条件下展现出强大的零样本或少样本迁移能力，并遵循规模法则，预示着随着预训练规模的扩大，功能将得到提升。然而，我们发现，尽管这些模型在标准化基准测试中表现出色，但在面对一个简单的人类易解的常识问题时，其功能和推理能力却遭遇了戏剧性的失败。这些模型不仅对其错误答案过度自信，还常常提供看似合理却荒谬的“推理”解释。尽管尝试了多种增强提示和多步骤重新评估等标准干预措施，仍未能纠正其错误。我们呼吁科学和技术界紧急重新评估当前LLMs的能力，并共同制定新的标准化基准，以揭示这些未被现有评估程序和基准所发现的基本推理缺陷。论文实验的复现代码和原始数据可在https://github.com/LAION-AI/AIW获取。

> Large Language Models (LLMs) are often described as being instances of foundation models - that is, models that transfer strongly across various tasks and conditions in few-show or zero-shot manner, while exhibiting scaling laws that predict function improvement when increasing the pre-training scale. These claims of excelling in different functions and tasks rely on measurements taken across various sets of standardized benchmarks showing high scores for such models. We demonstrate here a dramatic breakdown of function and reasoning capabilities of state-of-the-art models trained at the largest available scales which claim strong function, using a simple, short, conventional common sense problem formulated in concise natural language, easily solvable by humans. The breakdown is dramatic, as models also express strong overconfidence in their wrong solutions, while providing often non-sensical "reasoning"-like explanations akin to confabulations to justify and backup the validity of their clearly failed responses, making them sound plausible. Various standard interventions in an attempt to get the right solution, like various type of enhanced prompting, or urging the models to reconsider the wrong solutions again by multi step re-evaluation, fail. We take these initial observations to the scientific and technological community to stimulate urgent re-assessment of the claimed capabilities of current generation of LLMs, Such re-assessment also requires common action to create standardized benchmarks that would allow proper detection of such basic reasoning deficits that obviously manage to remain undiscovered by current state-of-the-art evaluation procedures and benchmarks. Code for reproducing experiments in the paper and raw experiments data can be found at https://github.com/LAION-AI/AIW

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/Humpty_Dumpty_Tenniel.jpg)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x1.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x2.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x3.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x4.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x5.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x6.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x7.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x8.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x9.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x10.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x11.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x12.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x13.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x14.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x15.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x16.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x17.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x18.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x19.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x20.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x21.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x22.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x23.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x24.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x25.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x26.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x27.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x28.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x29.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x30.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x31.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x32.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x33.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效](../../../paper_images/2406.02061/x34.png)

[Arxiv](https://arxiv.org/abs/2406.02061)