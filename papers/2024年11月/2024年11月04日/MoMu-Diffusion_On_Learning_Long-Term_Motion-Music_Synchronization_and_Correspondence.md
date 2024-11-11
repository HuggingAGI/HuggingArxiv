# MoMu-Diffusion：关于学习长期运动-音乐同步和对应关系

发布时间：2024年11月04日

`其他`

> MoMu-Diffusion: On Learning Long-Term Motion-Music Synchronization and Correspondence

# 摘要

> 运动到音乐和音乐到运动分别被研究，各自在其各自的领域吸引了大量的研究兴趣。人类运动和音乐之间的相互作用是高级人类智能的反映，在它们之间建立统一的关系尤为重要。然而，迄今为止，还没有工作共同考虑它们来探索其中的模态对齐。为了弥补这一差距，我们提出了一个新颖的框架，称为 MoMu-Diffusion，用于长期和同步的运动 - 音乐生成。首先，为了减轻长序列带来的巨大计算成本，我们提出了一种新颖的双向对比节奏变分自编码器（BiCoR-VAE），为运动和音乐输入提取模态对齐的潜在表示。随后，利用对齐的潜在空间，我们引入了一个基于多模态 Transformer 的扩散模型和一个交叉引导采样策略，以实现各种生成任务，包括跨模态、多模态和可变长度生成。大量实验表明，MoMu-Diffusion 在定性和定量上都超过了最近的最先进方法，并且能够合成逼真、多样、长期和节拍匹配的音乐或运动序列。生成的样本和代码可在 https://momu-diffusion.github.io/ 获得。

> Motion-to-music and music-to-motion have been studied separately, each attracting substantial research interest within their respective domains. The interaction between human motion and music is a reflection of advanced human intelligence, and establishing a unified relationship between them is particularly important. However, to date, there has been no work that considers them jointly to explore the modality alignment within. To bridge this gap, we propose a novel framework, termed MoMu-Diffusion, for long-term and synchronous motion-music generation. Firstly, to mitigate the huge computational costs raised by long sequences, we propose a novel Bidirectional Contrastive Rhythmic Variational Auto-Encoder (BiCoR-VAE) that extracts the modality-aligned latent representations for both motion and music inputs. Subsequently, leveraging the aligned latent spaces, we introduce a multi-modal Transformer-based diffusion model and a cross-guidance sampling strategy to enable various generation tasks, including cross-modal, multi-modal, and variable-length generation. Extensive experiments demonstrate that MoMu-Diffusion surpasses recent state-of-the-art methods both qualitatively and quantitatively, and can synthesize realistic, diverse, long-term, and beat-matched music or motion sequences. The generated samples and codes are available at https://momu-diffusion.github.io/

[Arxiv](https://arxiv.org/abs/2411.01805)