# ChatRex：驾驭多模态 LLM 达成联合感知与理解

发布时间：2024年11月27日

`LLM应用` `计算机视觉` `多模态语言模型`

> ChatRex: Taming Multimodal LLM for Joint Perception and Understanding

# 摘要

> 感知与理解乃计算机视觉的两大支柱。尽管多模态大型语言模型（MLLM）已彰显出非凡的视觉理解能力，但其准确感知能力却有所欠缺，比如顶尖模型 Qwen2-VL 在 COCO 数据集上的召回率仅为 43.9，这给诸多需要感知与理解相结合的任务带来了限制。在本研究中，我们致力于从模型设计和数据开发的视角来填补这一感知空缺。我们首先推出 ChatRex，这是一款具备解耦感知设计的 MLLM。我们并非让 LLM 直接预测框坐标，而是把来自通用提议网络的输出框输入 LLM，使其输出相应的框索引以表明检测结果，将回归任务转化为 LLM 更擅长处理的基于检索的任务。从数据方面来说，我们构建了一个全自动的数据引擎，并打造了具有多种粒度的 Rexverse-2M 数据集，以支撑感知与理解的联合训练。经过标准的两阶段训练，ChatRex 在保持多模态理解性能的同时，展现出强大的感知能力。这两种能力的结合同时开启了众多颇具吸引力的应用，体现了感知与理解在 MLLM 中的互补作用。代码可在 url{https://github.com/IDEA-Research/ChatRex}获取。

> Perception and understanding are two pillars of computer vision. While multimodal large language models (MLLM) have demonstrated remarkable visual understanding capabilities, they arguably lack accurate perception abilities, e.g. the stage-of-the-art model Qwen2-VL only achieves a 43.9 recall rate on the COCO dataset, limiting many tasks requiring the combination of perception and understanding. In this work, we aim to bridge this perception gap from both model designing and data development perspectives. We first introduce ChatRex, an MLLM with a decoupled perception design. Instead of having the LLM directly predict box coordinates, we feed the output boxes from a universal proposal network into the LLM, allowing it to output the corresponding box indices to represent its detection results, turning the regression task into a retrieval-based task that LLM handles more proficiently. From the data perspective, we build a fully automated data engine and construct the Rexverse-2M dataset which possesses multiple granularities to support the joint training of perception and understanding. After standard two-stage training, ChatRex demonstrates strong perception capabilities while preserving multimodal understanding performance. The combination of these two capabilities simultaneously unlocks many attractive applications, demonstrating the complementary roles of both perception and understanding in MLLM. Code is available at url{https://github.com/IDEA-Research/ChatRex}.

[Arxiv](https://arxiv.org/abs/2411.18363)