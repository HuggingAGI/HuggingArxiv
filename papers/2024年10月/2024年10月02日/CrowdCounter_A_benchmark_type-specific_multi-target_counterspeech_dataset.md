# CrowdCounter：一款专为多目标反驳言论设计的特定类型数据集基准

发布时间：2024年10月02日

`LLM应用` `社交媒体` `数据集`

> CrowdCounter: A benchmark type-specific multi-target counterspeech dataset

# 摘要

> 反驳言论为应对仇恨言论提供了一种既维护言论自由又不失为良策的替代方案。然而，撰写有效反驳言论对版主和用户而言颇具挑战。因此，开发反驳言论撰写工具刻不容缓。现有数据集中回复质量与多样性的不足，是开发此类工具的一大难题。为此，我们推出了CrowdCounter数据集，包含3,425对仇恨言论与反驳言论，涵盖六种类型（同理心、幽默、质疑、警告、羞辱、矛盾），实属首创。我们的标注平台设计鼓励标注者创作类型特定、非冗余且高质量的反驳言论。我们评估了两种生成反驳言论的框架——普通与类型控制提示，涉及四个大型语言模型。评估指标包括相关性、多样性和质量。结果显示，Flan-T5在普通框架中表现最佳。类型控制提示虽提升回复相关性，但可能降低语言质量。DialoGPT则在遵循指令、准确生成类型特定反驳言论方面表现卓越。

> Counterspeech presents a viable alternative to banning or suspending users for hate speech while upholding freedom of expression. However, writing effective counterspeech is challenging for moderators/users. Hence, developing suggestion tools for writing counterspeech is the need of the hour. One critical challenge in developing such a tool is the lack of quality and diversity of the responses in the existing datasets. Hence, we introduce a new dataset - CrowdCounter containing 3,425 hate speech-counterspeech pairs spanning six different counterspeech types (empathy, humor, questioning, warning, shaming, contradiction), which is the first of its kind. The design of our annotation platform itself encourages annotators to write type-specific, non-redundant and high-quality counterspeech. We evaluate two frameworks for generating counterspeech responses - vanilla and type-controlled prompts - across four large language models. In terms of metrics, we evaluate the responses using relevance, diversity and quality. We observe that Flan-T5 is the best model in the vanilla framework across different models. Type-specific prompts enhance the relevance of the responses, although they might reduce the language quality. DialoGPT proves to be the best at following the instructions and generating the type-specific counterspeech accurately.

[Arxiv](https://arxiv.org/abs/2410.01400)