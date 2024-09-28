# Robotic-CLIP：为机器人应用量身定制，通过动作数据微调 CLIP。

发布时间：2024年09月26日

`Agent` `机器人` `人工智能`

> Robotic-CLIP: Fine-tuning CLIP on Action Data for Robotic Applications

# 摘要

> 视觉语言模型在机器人应用中提取关键特征方面功不可没。其中，对比语言-图像预训练 (CLIP) 在需要视觉和语言理解的机器人任务中广泛应用。然而，CLIP 仅基于静态图像与文本的配对数据训练，尚未完全适应动态动作的机器人任务。为此，我们提出了 Robotic-CLIP，旨在提升机器人感知能力。我们首先收集并标注大量动作数据，然后通过在 309,433 个视频 (~7.4 百万帧) 上微调 CLIP，构建 Robotic-CLIP。通过融入动作数据，Robotic-CLIP 不仅继承了 CLIP 的图像处理优势，还增强了在机器人环境中理解动作的能力。实验结果显示，Robotic-CLIP 在多种语言驱动的机器人任务中表现优异。此外，我们还验证了 Robotic-CLIP 在实际抓取任务中的有效性。

> Vision language models have played a key role in extracting meaningful features for various robotic applications. Among these, Contrastive Language-Image Pretraining (CLIP) is widely used in robotic tasks that require both vision and natural language understanding. However, CLIP was trained solely on static images paired with text prompts and has not yet been fully adapted for robotic tasks involving dynamic actions. In this paper, we introduce Robotic-CLIP to enhance robotic perception capabilities. We first gather and label large-scale action data, and then build our Robotic-CLIP by fine-tuning CLIP on 309,433 videos (~7.4 million frames) of action data using contrastive learning. By leveraging action data, Robotic-CLIP inherits CLIP's strong image performance while gaining the ability to understand actions in robotic contexts. Intensive experiments show that our Robotic-CLIP outperforms other CLIP-based models across various language-driven robotic tasks. Additionally, we demonstrate the practical effectiveness of Robotic-CLIP in real-world grasping applications.

[Arxiv](https://arxiv.org/abs/2409.17727)