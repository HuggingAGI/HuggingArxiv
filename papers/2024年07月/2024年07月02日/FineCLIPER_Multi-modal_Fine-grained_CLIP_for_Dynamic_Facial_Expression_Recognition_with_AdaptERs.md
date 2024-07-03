# FineCLIPER：一款结合多模态细粒度 CLIP 技术与适应性调整器的系统，专为动态面部表情识别设计。

发布时间：2024年07月02日

`LLM应用` `人工智能` `计算机视觉`

> FineCLIPER: Multi-modal Fine-grained CLIP for Dynamic Facial Expression Recognition with AdaptERs

# 摘要

> 动态面部表情识别（DFER）对理解人类行为至关重要，但现有方法因高质量数据稀缺、面部动态利用不足及表情语义模糊等问题表现受限。为此，我们创新性地提出了“FineCLIPER”框架，该框架通过以下设计提升性能：首先，通过扩展类别标签为正负文本描述，并利用CLIP模型计算跨模态相似性，以更好地区分相似表情；其次，采用分层策略，从视频帧中提取面部掩码和地标，并借助MLLM生成详细面部变化描述，从而有效挖掘视频中的有用线索。此外，通过参数高效微调（PEFT），我们实现了对大型预训练模型（如CLIP）的高效适应。FineCLIPER在多个数据集上，无论是在有监督还是零-shot环境下，均以少量参数达到了顶尖性能，并通过分析和消融研究进一步证实了其有效性。

> Dynamic Facial Expression Recognition (DFER) is crucial for understanding human behavior. However, current methods exhibit limited performance mainly due to the scarcity of high-quality data, the insufficient utilization of facial dynamics, and the ambiguity of expression semantics, etc. To this end, we propose a novel framework, named Multi-modal Fine-grained CLIP for Dynamic Facial Expression Recognition with AdaptERs (FineCLIPER), incorporating the following novel designs: 1) To better distinguish between similar facial expressions, we extend the class labels to textual descriptions from both positive and negative aspects, and obtain supervision by calculating the cross-modal similarity based on the CLIP model; 2) Our FineCLIPER adopts a hierarchical manner to effectively mine useful cues from DFE videos. Specifically, besides directly embedding video frames as input (low semantic level), we propose to extract the face segmentation masks and landmarks based on each frame (middle semantic level) and utilize the Multi-modal Large Language Model (MLLM) to further generate detailed descriptions of facial changes across frames with designed prompts (high semantic level). Additionally, we also adopt Parameter-Efficient Fine-Tuning (PEFT) to enable efficient adaptation of large pre-trained models (i.e., CLIP) for this task. Our FineCLIPER achieves SOTA performance on the DFEW, FERV39k, and MAFW datasets in both supervised and zero-shot settings with few tunable parameters. Analysis and ablation studies further validate its effectiveness.

[Arxiv](https://arxiv.org/abs/2407.02157)