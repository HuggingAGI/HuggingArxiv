# 《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。

发布时间：2024年06月04日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在处理常识问题时的局限性，特别是在推理能力方面的缺陷。论文指出，尽管这些模型在标准化基准测试中表现出色，但在面对简单的常识问题时，它们的表现远不如人类，并且对自己的错误答案表现出过度自信。此外，论文还提到了这些模型在提供解释时常常产生无意义的“推理”，这表明它们可能在虚构故事以自圆其说。论文呼吁科学和技术界重新审视LLMs的实际能力，并提出需要制定新的标准化基准来揭示和纠正这些推理缺陷。因此，这篇论文更偏向于对LLMs理论层面的探讨和批评，而不是具体的应用或Agent、RAG相关的研究。` `人工智能`

> Alice in Wonderland: Simple Tasks Showing Complete Reasoning Breakdown in State-Of-the-Art Large Language Models

# 摘要

> 大型语言模型（LLMs）常被视为基础模型的典范，它们在多种任务和条件下展现出强大的跨领域能力，并随着预训练规模的扩大和预测功能的提升，显示出规模法则。然而，这些模型在标准化基准测试中的高分背后，我们发现了一个惊人的现象：面对一个简单、用自然语言表述的常识问题，这些最尖端的模型却显得力不从心，而人类却能轻易解答。更甚者，这些模型对自己的错误答案过度自信，并提供看似合理却常无意义的“推理”解释，仿佛在虚构故事以自圆其说。尽管尝试了多种增强提示和多步骤重新评估等标准方法，仍未能纠正这些错误。我们呼吁科学和技术界紧急重新审视这些LLMs的实际能力，并共同制定新的标准化基准，以揭示并纠正这些未被现有评估程序和基准所察觉的基本推理缺陷。论文实验的复现代码和原始数据可在https://github.com/LAION-AI/AIW获取。

> Large Language Models (LLMs) are often described as being instances of foundation models - that is, models that transfer strongly across various tasks and conditions in few-show or zero-shot manner, while exhibiting scaling laws that predict function improvement when increasing the pre-training scale. These claims of excelling in different functions and tasks rely on measurements taken across various sets of standardized benchmarks showing high scores for such models. We demonstrate here a dramatic breakdown of function and reasoning capabilities of state-of-the-art models trained at the largest available scales which claim strong function, using a simple, short, conventional common sense problem formulated in concise natural language, easily solvable by humans. The breakdown is dramatic, as models also express strong overconfidence in their wrong solutions, while providing often non-sensical "reasoning"-like explanations akin to confabulations to justify and backup the validity of their clearly failed responses, making them sound plausible. Various standard interventions in an attempt to get the right solution, like various type of enhanced prompting, or urging the models to reconsider the wrong solutions again by multi step re-evaluation, fail. We take these initial observations to the scientific and technological community to stimulate urgent re-assessment of the claimed capabilities of current generation of LLMs, Such re-assessment also requires common action to create standardized benchmarks that would allow proper detection of such basic reasoning deficits that obviously manage to remain undiscovered by current state-of-the-art evaluation procedures and benchmarks. Code for reproducing experiments in the paper and raw experiments data can be found at https://github.com/LAION-AI/AIW

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/Humpty_Dumpty_Tenniel.jpg)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x1.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x2.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x3.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x4.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x5.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x6.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x7.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x8.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x9.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x10.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x11.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x12.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x13.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x14.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x15.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x16.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x17.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x18.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x19.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x20.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x21.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x22.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x23.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x24.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x25.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x26.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x27.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x28.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x29.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x30.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x31.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x32.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x33.png)

![《爱丽丝梦游仙境》揭示：顶尖大型语言模型在简单任务上遭遇全面推理失效。](../../../paper_images/2406.02061/x34.png)

[Arxiv](https://arxiv.org/abs/2406.02061)