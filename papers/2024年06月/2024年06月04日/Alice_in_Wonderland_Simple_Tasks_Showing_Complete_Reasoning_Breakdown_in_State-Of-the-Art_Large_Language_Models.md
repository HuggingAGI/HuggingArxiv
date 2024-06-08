# 《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃

发布时间：2024年06月04日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在面对常识问题时的推理能力缺陷，并呼吁对当前LLMs的能力进行重新评估，并制定新的标准化基准来检测这些缺陷。这属于对LLMs理论层面的深入分析和批判，因此归类为LLM理论。` `人工智能` `常识推理`

> Alice in Wonderland: Simple Tasks Showing Complete Reasoning Breakdown in State-Of-the-Art Large Language Models

# 摘要

> 大型语言模型（LLMs）常被视为基础模型的典范，它们在多种任务和条件下，以少量或零样本的方式展现出卓越的迁移能力，并遵循一种缩放定律，预示着随着预训练规模的扩大，其功能将得到提升。然而，我们在此揭示了一个惊人的事实：即便是当前最尖端的、在最大规模上训练的LLMs，在面对一个简短且人类易于解决的常识问题时，其功能和推理能力却遭遇了戏剧性的崩溃。这些模型不仅对其错误答案过度自信，还常常提供看似合理却实则荒谬的“推理”解释，以支持其错误的回答。尽管尝试了多种增强提示和多步骤重新评估等标准干预措施，仍未能纠正其错误。我们呼吁科学和技术界紧急重新评估当前LLMs的能力声明，并共同制定新的标准化基准，以准确检测这些未被现有评估程序揭示的基本推理缺陷。论文实验的复现代码及原始数据可在https://github.com/LAION-AI/AIW获取。

> Large Language Models (LLMs) are often described as being instances of foundation models - that is, models that transfer strongly across various tasks and conditions in few-show or zero-shot manner, while exhibiting scaling laws that predict function improvement when increasing the pre-training scale. These claims of excelling in different functions and tasks rely on measurements taken across various sets of standardized benchmarks showing high scores for such models. We demonstrate here a dramatic breakdown of function and reasoning capabilities of state-of-the-art models trained at the largest available scales which claim strong function, using a simple, short, conventional common sense problem formulated in concise natural language, easily solvable by humans. The breakdown is dramatic, as models also express strong overconfidence in their wrong solutions, while providing often non-sensical "reasoning"-like explanations akin to confabulations to justify and backup the validity of their clearly failed responses, making them sound plausible. Various standard interventions in an attempt to get the right solution, like various type of enhanced prompting, or urging the models to reconsider the wrong solutions again by multi step re-evaluation, fail. We take these initial observations to the scientific and technological community to stimulate urgent re-assessment of the claimed capabilities of current generation of LLMs, Such re-assessment also requires common action to create standardized benchmarks that would allow proper detection of such basic reasoning deficits that obviously manage to remain undiscovered by current state-of-the-art evaluation procedures and benchmarks. Code for reproducing experiments in the paper and raw experiments data can be found at https://github.com/LAION-AI/AIW

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/Humpty_Dumpty_Tenniel.jpg)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x1.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x2.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x3.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x4.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x5.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x6.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x7.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x8.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x9.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x10.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x11.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x12.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x13.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x14.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x15.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x16.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x17.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x18.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x19.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x20.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x21.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x22.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x23.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x24.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x25.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x26.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x27.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x28.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x29.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x30.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x31.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x32.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x33.png)

![《爱丽丝梦游仙境》：简单任务暴露出顶尖大型语言模型的推理全盘崩溃](../../../paper_images/2406.02061/x34.png)

[Arxiv](https://arxiv.org/abs/2406.02061)