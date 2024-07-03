# MORPHEUS 项目旨在通过探索和利用潜在空间，从个性化对话历史中精准建模角色。

发布时间：2024年07月02日

`LLM应用` `人工智能` `对话系统`

> MORPHEUS: Modeling Role from Personalized Dialogue History by Exploring and Utilizing Latent Space

# 摘要

> 个性化对话生成 (PDG) 旨在根据角色特征创造连贯回应。传统方法依赖外部角色数据，常因稀缺和隐私问题受限。我们提出的 MORPHEUS 框架，通过三阶段训练，从对话历史中探索并利用潜在空间的角色信息，创建角色代码本，有效构建角色信息分布，使模型能泛化至新角色，生成个性化对话。实验证明，MORPHEUS 不仅提升角色信息提取，还优化了回应生成，无需外部角色数据，并可高效微调大型语言模型。

> Personalized Dialogue Generation (PDG) aims to create coherent responses according to roles or personas. Traditional PDG relies on external role data, which can be scarce and raise privacy concerns. Approaches address these issues by extracting role information from dialogue history, which often fail to generically model roles in continuous space. To overcome these limitations, we introduce a novel framework \textbf{MO}dels \textbf{R}oles from \textbf{P}ersonalized Dialogue \textbf{H}istory by \textbf{E}xploring and \textbf{U}tilizing Latent \textbf{S}pace (MORPHEUS) through a three-stage training process. Specifically, we create a persona codebook to represent roles in latent space compactly, and this codebook is used to construct a posterior distribution of role information. This method enables the model to generalize across roles, allowing the generation of personalized dialogues even for unseen roles. Experiments on both Chinese and English datasets demonstrate that MORPHEUS enhances the extraction of role information, and improves response generation without external role data. Additionally, MORPHEUS can be considered an efficient fine-tuning for large language models.

[Arxiv](https://arxiv.org/abs/2407.02345)