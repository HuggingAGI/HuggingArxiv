# 大型生成模型辅助的说话人脸语义通信系统

发布时间：2024年11月06日

`LLM应用` `人工智能`

> Large Generative Model-assisted Talking-face Semantic Communication System

# 摘要

> 生成式人工智能（AI）的快速发展不断揭示语义通信（SemCom）的潜力。然而，当前的说话人脸语义通信系统仍然面临诸如低带宽利用率、语义歧义以及体验质量（QoE）下降等挑战。本研究引入了一个专为说话人脸视频通信量身定制的大型生成模型辅助说话人脸语义通信（LGM-TSC）系统。首先，我们在发射端基于 FunASR 模型引入了一个生成语义提取器（GSE），将语义稀疏的说话人脸视频转换为具有高信息密度的文本。其次，我们基于大型语言模型（LLM）建立了一个私有知识库（KB）用于语义消歧和校正，并辅以联合知识库 - 语义信道编码方案。最后，在接收端，我们提出了一个生成语义重建器（GSR），它利用 BERT-VITS2 和 SadTalker 模型将文本转换回与用户音色匹配的高 QoE 说话人脸视频。仿真结果证明了所提出的 LGM-TSC 系统的可行性和有效性。

> The rapid development of generative Artificial Intelligence (AI) continually unveils the potential of Semantic Communication (SemCom). However, current talking-face SemCom systems still encounter challenges such as low bandwidth utilization, semantic ambiguity, and diminished Quality of Experience (QoE). This study introduces a Large Generative Model-assisted Talking-face Semantic Communication (LGM-TSC) System tailored for the talking-face video communication. Firstly, we introduce a Generative Semantic Extractor (GSE) at the transmitter based on the FunASR model to convert semantically sparse talking-face videos into texts with high information density. Secondly, we establish a private Knowledge Base (KB) based on the Large Language Model (LLM) for semantic disambiguation and correction, complemented by a joint knowledge base-semantic-channel coding scheme. Finally, at the receiver, we propose a Generative Semantic Reconstructor (GSR) that utilizes BERT-VITS2 and SadTalker models to transform text back into a high-QoE talking-face video matching the user's timbre. Simulation results demonstrate the feasibility and effectiveness of the proposed LGM-TSC system.

[Arxiv](https://arxiv.org/abs/2411.03876)