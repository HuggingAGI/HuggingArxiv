# 视觉大型语言模型推理的相图：基于图像与指令交互的视角

发布时间：2024年11月01日

`LLM理论` `计算机视觉`

> Phase Diagram of Vision Large Language Models Inference: A Perspective from Interaction across Image and Instruction

# 摘要

> 视觉大型语言模型（VLLMs）通常把图像标记嵌入与文本标记嵌入的串联当作输入，进行因果建模。不过，其内部行为尚未被充分探究，这引发了两类标记相互作用的疑问。为探究模型推理过程中的这种多模态交互，在本文中，我们测量了来自不同模态标记的隐藏状态向量之间的上下文关联。我们的实验揭示了基于 Transformer 的 LMs 深度下 VLLMs 的四阶段推理动态，包括：（I）对齐：在极早期的层中，模态间出现上下文关联，意味着特征空间的对齐。（II）模态内编码：在早期层中，模态内的上下文关联增强，而模态间的相互作用受到抑制，表明模态内的局部编码。（III）模态间编码：在较晚的层中，跨模态的上下文关联增强，意味着跨模态的深度融合。（IV）输出准备：在极晚的层中，全局上下文关联减少，隐藏状态朝着解嵌入空间对齐。

> Vision Large Language Models (VLLMs) usually take input as a concatenation of image token embeddings and text token embeddings and conduct causal modeling. However, their internal behaviors remain underexplored, raising the question of interaction among two types of tokens. To investigate such multimodal interaction during model inference, in this paper, we measure the contextualization among the hidden state vectors of tokens from different modalities. Our experiments uncover a four-phase inference dynamics of VLLMs against the depth of Transformer-based LMs, including (I) Alignment: In very early layers, contextualization emerges between modalities, suggesting a feature space alignment. (II) Intra-modal Encoding: In early layers, intra-modal contextualization is enhanced while inter-modal interaction is suppressed, suggesting a local encoding within modalities. (III) Inter-modal Encoding: In later layers, contextualization across modalities is enhanced, suggesting a deeper fusion across modalities. (IV) Output Preparation: In very late layers, contextualization is reduced globally, and hidden states are aligned towards the unembedding space.

[Arxiv](https://arxiv.org/abs/2411.00646)