# 还在正轨上吗？利用激活监测大型语言模型任务漂移

发布时间：2024年06月02日

`Agent

理由：这篇论文主要关注的是如何通过分析大型语言模型（LLMs）的激活来检测和防止提示注入攻击，这是一种特定的安全机制，用于保护LLMs不被误导执行非预期的任务。这种机制可以被视为一种智能代理（Agent），它监控和调整LLMs的行为以确保其按照用户的意图执行任务。因此，这篇论文更符合Agent分类，因为它涉及到了对LLMs行为的监控和调整，以应对外部威胁。` `信息安全` `人工智能`

> Are you still on track!? Catching LLM Task Drift with Activations

# 摘要

> 大型语言模型（LLMs）在增强检索应用中扮演着关键角色，处理来自不同可信度和来源的多样化输入。然而，这也带来了提示注入攻击的风险，即LLM可能被误导执行非用户本意的指令，导致任务偏移。为此，我们提出通过分析LLM的激活来检测这种偏移。通过比较外部输入处理前后的激活，我们开发了两种探测技术，其中线性分类器在检测任务偏移上表现出色，甚至在未见过的攻击类型中也展现出良好的泛化能力。我们的方法无需修改LLM或生成文本，确保了高度的部署性和成本效益。为了推动基于激活的任务检查和可解释性研究，我们将发布包含超过500,000实例和先进模型表示的TaskTracker工具包。

> Large Language Models (LLMs) are routinely used in retrieval-augmented applications to orchestrate tasks and process inputs from users and other sources. These inputs, even in a single LLM interaction, can come from a variety of sources, of varying trustworthiness and provenance. This opens the door to prompt injection attacks, where the LLM receives and acts upon instructions from supposedly data-only sources, thus deviating from the user's original instructions. We define this as task drift, and we propose to catch it by scanning and analyzing the LLM's activations. We compare the LLM's activations before and after processing the external input in order to detect whether this input caused instruction drift. We develop two probing methods and find that simply using a linear classifier can detect drift with near perfect ROC AUC on an out-of-distribution test set. We show that this approach generalizes surprisingly well to unseen task domains, such as prompt injections, jailbreaks, and malicious instructions, without being trained on any of these attacks. Our setup does not require any modification of the LLM (e.g., fine-tuning) or any text generation, thus maximizing deployability and cost efficiency and avoiding reliance on unreliable model output. To foster future research on activation-based task inspection, decoding, and interpretability, we will release our large-scale TaskTracker toolkit, comprising a dataset of over 500K instances, representations from 4 SoTA language models, and inspection tools.

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x1.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x2.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x3.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x4.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x5.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x6.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x7.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x8.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x9.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x10.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x11.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x12.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x13.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x14.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x15.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x16.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x17.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x18.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x19.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x20.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x21.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x22.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x23.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x24.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x25.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x26.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x27.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x28.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x29.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x30.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x31.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x32.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x33.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x34.png)

![还在正轨上吗？利用激活监测大型语言模型任务漂移](../../../paper_images/2406.00799/x35.png)

[Arxiv](https://arxiv.org/abs/2406.00799)