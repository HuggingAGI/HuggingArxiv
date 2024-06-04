# 你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。

发布时间：2024年06月02日

`Agent

理由：这篇论文主要讨论了大型语言模型（LLMs）在面对提示注入攻击时的应对策略，通过分析LLM的激活状态来识别和防止任务漂移。这种方法涉及到对LLM行为的监控和调整，类似于一个智能代理（Agent）的行为，即通过内部状态的分析来调整对外部输入的处理。因此，这篇论文更符合Agent分类，因为它关注的是如何通过监控和调整LLM的行为来应对外部威胁，而不是直接关于LLM的理论研究或应用开发。` `网络安全` `人工智能`

> Are you still on track!? Catching LLM Task Drift with Activations

# 摘要

> 大型语言模型（LLMs）在增强检索应用中广泛用于协调任务和处理多源输入，这些输入的可信度和来源参差不齐。这种多样性为提示注入攻击提供了机会，攻击者通过伪装成数据源向LLM发送指令，导致其偏离用户初衷。我们称这种现象为任务漂移，并提出通过分析LLM的激活来识别此类漂移。通过比较外部输入处理前后LLM的激活状态，我们能够检测输入是否引发了指令偏离。我们开发了两种探测技术，并发现简单的线性分类器在分布外的测试集上几乎完美地识别了任务漂移。令人惊讶的是，这种方法在未曾训练过的任务领域（如提示注入、越狱和恶意指令）中同样表现出色。我们的方法无需修改LLM或生成文本，确保了高部署性和成本效益，同时避免了依赖不可靠的模型输出。为了推动基于激活的任务检查、解码和可解释性研究，我们将发布包含超过500,000个实例、来自4个顶尖语言模型的表示和检查工具的TaskTracker工具包。

> Large Language Models (LLMs) are routinely used in retrieval-augmented applications to orchestrate tasks and process inputs from users and other sources. These inputs, even in a single LLM interaction, can come from a variety of sources, of varying trustworthiness and provenance. This opens the door to prompt injection attacks, where the LLM receives and acts upon instructions from supposedly data-only sources, thus deviating from the user's original instructions. We define this as task drift, and we propose to catch it by scanning and analyzing the LLM's activations. We compare the LLM's activations before and after processing the external input in order to detect whether this input caused instruction drift. We develop two probing methods and find that simply using a linear classifier can detect drift with near perfect ROC AUC on an out-of-distribution test set. We show that this approach generalizes surprisingly well to unseen task domains, such as prompt injections, jailbreaks, and malicious instructions, without being trained on any of these attacks. Our setup does not require any modification of the LLM (e.g., fine-tuning) or any text generation, thus maximizing deployability and cost efficiency and avoiding reliance on unreliable model output. To foster future research on activation-based task inspection, decoding, and interpretability, we will release our large-scale TaskTracker toolkit, comprising a dataset of over 500K instances, representations from 4 SoTA language models, and inspection tools.

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x1.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x2.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x3.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x4.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x5.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x6.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x7.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x8.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x9.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x10.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x11.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x12.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x13.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x14.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x15.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x16.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x17.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x18.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x19.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x20.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x21.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x22.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x23.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x24.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x25.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x26.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x27.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x28.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x29.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x30.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x31.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x32.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x33.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x34.png)

![你的大型语言模型是否偏离了正轨？通过激活监测，我们能及时捕捉到任务漂移的迹象。](../../../paper_images/2406.00799/x35.png)

[Arxiv](https://arxiv.org/abs/2406.00799)