# SimpleLLM4AD：一款集成了图表视觉问答的端到端视觉语言模型，专为自动驾驶设计。

发布时间：2024年07月30日

`LLM应用` `自动驾驶` `视觉语言模型`

> SimpleLLM4AD: An End-to-End Vision-Language Model with Graph Visual Question Answering for Autonomous Driving

# 摘要

> 随着大型语言模型（LLMs）的迅猛发展，众多领域迎来了新的机遇，端到端自动驾驶（e2eAD）便是其中之一。我们借助视觉语言模型（VLM），提出了一种名为SimpleLLM4AD的e2eAD方法。该方法将e2eAD任务细分为感知、预测、规划和行为四个阶段，每个阶段通过视觉问答（VQA）对相互连接，形成Graph VQA（GVQA）。通过VLM逐阶段推理GVQA中的VQA对，我们的方法实现了语言驱动的端到端驾驶。视觉转换器（ViT）模型处理nuScenes视觉数据，VLM则负责解释和推理视觉信息。感知阶段识别并分类环境中的物体，预测阶段预测其运动，规划阶段制定安全高效的驾驶策略，行为阶段则将策略转化为可执行命令。实验结果显示，SimpleLLM4AD在复杂驾驶场景中表现出色。

> Many fields could benefit from the rapid development of the large language models (LLMs). The end-to-end autonomous driving (e2eAD) is one of the typically fields facing new opportunities as the LLMs have supported more and more modalities. Here, by utilizing vision-language model (VLM), we proposed an e2eAD method called SimpleLLM4AD. In our method, the e2eAD task are divided into four stages, which are perception, prediction, planning, and behavior. Each stage consists of several visual question answering (VQA) pairs and VQA pairs interconnect with each other constructing a graph called Graph VQA (GVQA). By reasoning each VQA pair in the GVQA through VLM stage by stage, our method could achieve e2e driving with language. In our method, vision transformers (ViT) models are employed to process nuScenes visual data, while VLM are utilized to interpret and reason about the information extracted from the visual inputs. In the perception stage, the system identifies and classifies objects from the driving environment. The prediction stage involves forecasting the potential movements of these objects. The planning stage utilizes the gathered information to develop a driving strategy, ensuring the safety and efficiency of the autonomous vehicle. Finally, the behavior stage translates the planned actions into executable commands for the vehicle. Our experiments demonstrate that SimpleLLM4AD achieves competitive performance in complex driving scenarios.

[Arxiv](https://arxiv.org/abs/2407.21293)