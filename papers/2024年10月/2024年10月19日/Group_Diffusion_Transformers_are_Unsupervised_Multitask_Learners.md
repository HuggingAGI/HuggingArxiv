# Group Diffusion Transformers 是一种无监督的多任务学习模型。

发布时间：2024年10月19日

`LLM应用` `视觉生成` `人工智能`

> Group Diffusion Transformers are Unsupervised Multitask Learners

# 摘要

> 尽管 LLM 在 NLP 领域大放异彩，但视觉生成任务如图像翻译、风格迁移和角色定制仍依赖于特定任务的数据集。为此，我们提出了 Group Diffusion Transformers (GDTs)，通过将任务重新定义为组生成问题，统一了多样化的视觉生成任务。GDTs 通过在图像间连接自注意力标记，对扩散变换器进行了微调，使其能隐式捕捉跨图像关系。我们的设计使得 GDTs 能利用多模态数据进行无监督预训练。在涵盖 30 个视觉生成任务的综合基准测试中，GDTs 展现了出色的零-shot 性能，无需额外微调。消融研究进一步证实了其关键组件的有效性，展示了 GDTs 作为通用视觉生成系统的巨大潜力。

> While large language models (LLMs) have revolutionized natural language processing with their task-agnostic capabilities, visual generation tasks such as image translation, style transfer, and character customization still rely heavily on supervised, task-specific datasets. In this work, we introduce Group Diffusion Transformers (GDTs), a novel framework that unifies diverse visual generation tasks by redefining them as a group generation problem. In this approach, a set of related images is generated simultaneously, optionally conditioned on a subset of the group. GDTs build upon diffusion transformers with minimal architectural modifications by concatenating self-attention tokens across images. This allows the model to implicitly capture cross-image relationships (e.g., identities, styles, layouts, surroundings, and color schemes) through caption-based correlations. Our design enables scalable, unsupervised, and task-agnostic pretraining using extensive collections of image groups sourced from multimodal internet articles, image galleries, and video frames. We evaluate GDTs on a comprehensive benchmark featuring over 200 instructions across 30 distinct visual generation tasks, including picture book creation, font design, style transfer, sketching, colorization, drawing sequence generation, and character customization. Our models achieve competitive zero-shot performance without any additional fine-tuning or gradient updates. Furthermore, ablation studies confirm the effectiveness of key components such as data scaling, group size, and model design. These results demonstrate the potential of GDTs as scalable, general-purpose visual generation systems.

[Arxiv](https://arxiv.org/abs/2410.15027)