# [Text-guided Explorable Image Super-resolution，即借助文本引导实现可交互式探索的图像超分辨率技术。]

发布时间：2024年03月02日

`Agent`

> Text-guided Explorable Image Super-resolution

> 本文聚焦于开放域图像超分辨率的零样本文本驱动探索难题，旨在无需针对特定退化情况训练，就能依据用户需求和不同大幅度降采样因子，找到既丰富多样又语义精确，同时与低分辨率输入保持数据连贯的重建方案。我们创新性地提出了两种零样本文本引导的超分辨率策略：一是调整文本转图像\textit{T2I}扩散模型的生成流程，增强其对低分辨率输入的自洽性；二是将语言指导融入基于扩散的零样本修复技术中。实验表明，这两种方法能在确保与劣质输入数据一致的基础上，有效生成符合文本提示语义的多样化高质量恢复结果。我们在极端超分辨率任务上评估了这些新提出的基线方法，并在恢复质量、多样性及解空间探索性等方面展现出了显著优势。

> In this paper, we introduce the problem of zero-shot text-guided exploration of the solutions to open-domain image super-resolution. Our goal is to allow users to explore diverse, semantically accurate reconstructions that preserve data consistency with the low-resolution inputs for different large downsampling factors without explicitly training for these specific degradations. We propose two approaches for zero-shot text-guided super-resolution - i) modifying the generative process of text-to-image \textit{T2I} diffusion models to promote consistency with low-resolution inputs, and ii) incorporating language guidance into zero-shot diffusion-based restoration methods. We show that the proposed approaches result in diverse solutions that match the semantic meaning provided by the text prompt while preserving data consistency with the degraded inputs. We evaluate the proposed baselines for the task of extreme super-resolution and demonstrate advantages in terms of restoration quality, diversity, and explorability of solutions.

[Arxiv](https://arxiv.org/abs/2403.01124)