# MotionGPT-2：一个用于动作生成与理解的通用动作语言模型

发布时间：2024年10月29日

`LLM应用` `数字人类` `动作生成`

> MotionGPT-2: A General-Purpose Motion-Language Model for Motion Generation and Understanding

# 摘要

> 近年来，由数字人类的新兴需求所推动，从描述性文本生成逼真的人体动作这一研究备受关注。尽管成果斐然，但现有方法常受限于有限的控制模式、任务的特定性，且仅着眼于身体动作的表征。本文中，我们推出了 MotionGPT-2，这是一个统一的大型动作语言模型（LMLM），解决了上述局限。MotionGPT-2 借助预训练的大型语言模型（LLMs），能够适应多种动作相关任务，并支持多模态控制条件。它把多模态输入（如文本和单帧姿势）量化为离散且 LLM 可解读的标记，将其无缝融入 LLM 的词汇表。随后，这些标记被整合成统一的提示，通过预训练再微调的模式引导 LLM 生成动作输出。我们还指出，得益于创新的动作离散化框架 Part-Aware VQVAE，它能确保身体和手部动作的精细表征，所提出的 MotionGPT-2 对颇具挑战的 3D 整体动作生成任务具有高度适应性。大量实验和可视化结果验证了我们方法的有效性，表明了 MotionGPT-2 在动作生成、动作描述和广义动作完成任务中的适应性。

> Generating lifelike human motions from descriptive texts has experienced remarkable research focus in the recent years, propelled by the emerging requirements of digital humans.Despite impressive advances, existing approaches are often constrained by limited control modalities, task specificity, and focus solely on body motion representations.In this paper, we present MotionGPT-2, a unified Large Motion-Language Model (LMLM) that addresses these limitations. MotionGPT-2 accommodates multiple motion-relevant tasks and supporting multimodal control conditions through pre-trained Large Language Models (LLMs). It quantizes multimodal inputs-such as text and single-frame poses-into discrete, LLM-interpretable tokens, seamlessly integrating them into the LLM's vocabulary. These tokens are then organized into unified prompts, guiding the LLM to generate motion outputs through a pretraining-then-finetuning paradigm. We also show that the proposed MotionGPT-2 is highly adaptable to the challenging 3D holistic motion generation task, enabled by the innovative motion discretization framework, Part-Aware VQVAE, which ensures fine-grained representations of body and hand movements. Extensive experiments and visualizations validate the effectiveness of our method, demonstrating the adaptability of MotionGPT-2 across motion generation, motion captioning, and generalized motion completion tasks.

[Arxiv](https://arxiv.org/abs/2410.21747)