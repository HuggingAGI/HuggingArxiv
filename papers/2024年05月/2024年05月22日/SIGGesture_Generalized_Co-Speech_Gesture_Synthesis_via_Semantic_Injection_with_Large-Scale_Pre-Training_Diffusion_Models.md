# SIGGesture：借助大规模预训练扩散模型注入语义，实现通用共语手势的合成

发布时间：2024年05月22日

`Agent

理由：这篇论文主要介绍了一种新的方法（SIGesture），用于自动生成与语音同步的高质量3D手势，这对于虚拟角色和游戏领域的Agent行为模拟至关重要。论文中提到的基于扩散的方法和利用大型语言模型的泛化能力来定制语义手势，以及通过语义注入模块在扩散逆过程中融入语义信息，都是为了增强Agent的表现力和真实性。因此，这篇论文更符合Agent分类，因为它专注于提升虚拟角色的行为生成技术。` `虚拟角色`

> SIGGesture: Generalized Co-Speech Gesture Synthesis via Semantic Injection with Large-Scale Pre-Training Diffusion Models

# 摘要

> 自动生成与语音同步的高质量3D手势，对于虚拟角色和游戏领域至关重要。传统方法虽能合成与语音节奏同步的手势，却常忽视语义手势的融入。这些手势在序列中稀疏且分布不均，难以端到端学习。此外，现有方法难以将生成的手势泛化至自然语音环境。为此，我们推出了SIGGesture，一种基于扩散的新方法，旨在合成既真实又富含语义的手势。首先，我们基于大规模数据集预训练，构建了用于节奏手势合成的强大扩散基础模型。接着，利用大型语言模型的泛化能力，为不同语音内容定制语义手势。最后，通过语义注入模块，在扩散逆过程中巧妙融入语义信息。实验证明，SIGGesture不仅超越了现有技术，还展现出卓越的泛化能力和可控性。

> The automated synthesis of high-quality 3D gestures from speech is of significant value in virtual humans and gaming. Previous methods focus on synthesizing gestures that are synchronized with speech rhythm, yet they frequently overlook the inclusion of semantic gestures. These are sparse and follow a long-tailed distribution across the gesture sequence, making them difficult to learn in an end-to-end manner. Moreover, generating gestures, rhythmically aligned with speech, faces a significant issue that cannot be generalized to in-the-wild speeches. To address these issues, we introduce SIGGesture, a novel diffusion-based approach for synthesizing realistic gestures that are of both high quality and semantically pertinent. Specifically, we firstly build a strong diffusion-based foundation model for rhythmical gesture synthesis by pre-training it on a collected large-scale dataset with pseudo labels. Secondly, we leverage the powerful generalization capabilities of Large Language Models (LLMs) to generate proper semantic gestures for the various speech content. Finally, we propose a semantic injection module to infuse semantic information into the synthesized results during diffusion reverse process. Extensive experiments demonstrate that the proposed SIGGesture significantly outperforms existing baselines and shows excellent generalization and controllability.

[Arxiv](https://arxiv.org/abs/2405.13336)