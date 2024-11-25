# LARP：借助学习所得的自回归生成先验来对视频进行标记化

发布时间：2024年10月28日

`LLM应用` `生成模型`

> LARP: Tokenizing Videos with a Learned Autoregressive Generative Prior

# 摘要

> 我们推出了 LARP，这是一款全新的视频标记器，旨在攻克当下用于自回归（AR）生成模型的视频标记化方法存在的局限。和直接把局部视觉块编码成离散标记的传统分块式标记器有别，LARP 引入了一种整体性的标记化方案，借助一组习得的整体性查询从视觉内容中获取信息。如此设计让 LARP 能够获取更多全局和语义层面的表征，而非局限于局部块级别的信息。再者，它支持任意数量的离散标记，具备灵活性，能够依据任务的特定需求进行自适应且高效的标记化。为了让离散标记空间与下游的 AR 生成任务相适配，LARP 整合了一个轻量级的 AR 变压器作为训练时的先验模型，能在其离散潜在空间中预测下一个标记。通过在训练过程中融入先验模型，LARP 习得了一个潜在空间，不但针对视频重建做了优化，而且其架构更有益于自回归生成。此外，这一过程为离散标记确定了一个顺序，在训练时逐步将它们推向最优配置，保证在推理时更顺畅、更精准的 AR 生成。综合实验表明 LARP 性能强劲，在 UCF101 类条件视频生成基准上达成了顶尖的 FVD 指标。LARP 增强了 AR 模型与视频的兼容性，为构建统一的高保真多模态大型语言模型（MLLMs）开辟了可能。

> We present LARP, a novel video tokenizer designed to overcome limitations in current video tokenization methods for autoregressive (AR) generative models. Unlike traditional patchwise tokenizers that directly encode local visual patches into discrete tokens, LARP introduces a holistic tokenization scheme that gathers information from the visual content using a set of learned holistic queries. This design allows LARP to capture more global and semantic representations, rather than being limited to local patch-level information. Furthermore, it offers flexibility by supporting an arbitrary number of discrete tokens, enabling adaptive and efficient tokenization based on the specific requirements of the task. To align the discrete token space with downstream AR generation tasks, LARP integrates a lightweight AR transformer as a training-time prior model that predicts the next token on its discrete latent space. By incorporating the prior model during training, LARP learns a latent space that is not only optimized for video reconstruction but is also structured in a way that is more conducive to autoregressive generation. Moreover, this process defines a sequential order for the discrete tokens, progressively pushing them toward an optimal configuration during training, ensuring smoother and more accurate AR generation at inference time. Comprehensive experiments demonstrate LARP's strong performance, achieving state-of-the-art FVD on the UCF101 class-conditional video generation benchmark. LARP enhances the compatibility of AR models with videos and opens up the potential to build unified high-fidelity multimodal large language models (MLLMs).

[Arxiv](https://arxiv.org/abs/2410.21264)