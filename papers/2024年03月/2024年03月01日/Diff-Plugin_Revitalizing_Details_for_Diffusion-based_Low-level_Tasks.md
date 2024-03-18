# Diff-Plugin：激活扩散式底层任务中的精细细节，赋予其新的生命力

发布时间：2024年03月01日

`Agent`

> Diff-Plugin: Revitalizing Details for Diffusion-based Low-level Tasks

> 扩散模型在大规模数据驱动下，在图像生成领域取得了卓越成果，但因其内在随机性，在要求精细保持图像细节的多元低层次任务处理上力有不逮。因此，我们创新性地提出了Diff-Plugin框架，它能让单一预训练扩散模型跨多个低层次任务生成高质量图像。首先，我们设计了一个轻巧的Task-Plugin模块，采用双重分支结构以提供针对不同任务的先验信息，引导扩散过程精准保留图像内容。接下来，我们推出了能依据文本指令智能选取相应Task-Plugin的Plugin-Selector，使得用户仅需通过自然语言就能完成对图像进行多项低层次任务编辑的操作。经过在八大低层次视觉任务上的全面实验，Diff-Plugin展现出了超越现有方法的优势，尤其是在实际应用场景中的表现更为突出。此外，通过消融实验我们进一步证实了Diff-Plugin具有稳定、可控的训练特性，并且能在不同规模数据集上实现稳健的训练效果。

> Diffusion models trained on large-scale datasets have achieved remarkable progress in image synthesis. However, due to the randomness in the diffusion process, they often struggle with handling diverse low-level tasks that require details preservation. To overcome this limitation, we present a new Diff-Plugin framework to enable a single pre-trained diffusion model to generate high-fidelity results across a variety of low-level tasks. Specifically, we first propose a lightweight Task-Plugin module with a dual branch design to provide task-specific priors, guiding the diffusion process in preserving image content. We then propose a Plugin-Selector that can automatically select different Task-Plugins based on the text instruction, allowing users to edit images by indicating multiple low-level tasks with natural language. We conduct extensive experiments on 8 low-level vision tasks. The results demonstrate the superiority of Diff-Plugin over existing methods, particularly in real-world scenarios. Our ablations further validate that Diff-Plugin is stable, schedulable, and supports robust training across different dataset sizes.

[Arxiv](https://arxiv.org/abs/2403.00644)