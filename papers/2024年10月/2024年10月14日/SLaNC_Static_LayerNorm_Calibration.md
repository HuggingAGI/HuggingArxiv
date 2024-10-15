# SLaNC：静态层归一化校准

发布时间：2024年10月14日

`LLM理论` `硬件加速器` `人工智能`

> SLaNC: Static LayerNorm Calibration

# 摘要

> 随着大型语言模型（LLM）的规模不断扩大，专用硬件加速器的制造商面临巨大挑战，也推动了AI行业中硬件创新设计的快速发展。为了在现有硬件的计算和存储限制下高效处理LLM，量化技术成为研究焦点，旨在降低计算、通信和存储需求。然而，量化到低精度格式带来了数值表示范围有限的挑战。特别是在处理Transformer模型时，LayerNorm的计算成为瓶颈，因其需要比硬件支持的更宽动态范围。本文提出了一种高效的缩放技术，可在推理阶段轻松应用于Transformer模型，通过基于前线性层静态权重的简单缩放，离线计算缩放因子，确保推理过程中无延迟或计算开销，并避免数值问题。该方法在多种硬件架构上实现了平滑、准确且资源高效的推理，并得到了理论和数值模拟的支持。

> The ever increasing sizes of Large Language Models (LLMs) beyond hundreds of billions of parameters have generated enormous pressure on the manufacturers of dedicated hardware accelerators and made the innovative design of the latter one of the most rapidly expanding fields of the AI industry. Various approaches have been explored to enable efficient and accurate processing of LLMs on the available accelerators given their computational and storage limitations. Among these, various quantization techniques have become the main focus of the community as a means of reducing the compute, communication and storage requirements. Quantization to lower precision formats naturally poses a number of challenges caused by the limited range of the available value representations. When it comes to processing the popular Transformer models on hardware, one of the main issues becomes calculation of the LayerNorm simply because accumulation of the variance requires a much wider dynamic range than the hardware enables. In this article, we address this matter and propose a computationally-efficient scaling technique that can be easily applied to Transformer models during inference. Our method suggests a straightforward way of scaling the LayerNorm inputs based on the static weights of the immediately preceding linear layers. The scaling factors are computed offline, based solely on the linear layer weights, hence no latency or computational overhead is added during inference. Most importantly, our technique ensures that no numerical issues such as overflow or underflow could happen during the compute. This approach offers smooth, accurate and resource-effective inference across a wide range of hardware architectures. The article provides theoretical justification as well as supporting numerical simulations.

[Arxiv](https://arxiv.org/abs/2410.10553)