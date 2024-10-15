# FlatQuant：平坦性在 LLM 量化中举足轻重

发布时间：2024年10月12日

`LLM理论` `人工智能` `计算机硬件`

> FlatQuant: Flatness Matters for LLM Quantization

# 摘要

> 近期，量化技术在大型语言模型（LLMs）的压缩与加速中大放异彩。然而，LLMs中的异常值使得权重与激活值的展平成为关键，以最小化量化误差。尽管先前研究尝试了多种预量化变换来抑制异常值，但我们发现这些变换后的数据仍可能保持陡峭与分散。为此，我们提出了FlatQuant，一种新的后训练量化方法，旨在通过快速且可学习的仿射变换增强数据平坦性。通过识别并定制每层线性变换，FlatQuant在数小时内完成轻量级校准。为降低运行时开销，我们采用Kronecker分解并融合所有操作于单一内核。实验证明，FlatQuant不仅刷新了量化基准，更在LLaMA-3-70B模型的W4A4量化中实现了低于1%的精度损失，超越了SpinQuant 7.5%。同时，FlatQuant将预量化变换的减速从0.26倍降至0.07倍，分别带来2.3倍预填充与1.7倍解码的加速。代码已公开，详见：https://github.com/ruikangliu/FlatQuant。

> Recently, quantization has been widely used for the compression and acceleration of large language models~(LLMs). Due to the outliers in LLMs, it is crucial to flatten weights and activations to minimize quantization error with the equally spaced quantization points. Prior research explores various pre-quantization transformations to suppress outliers, such as per-channel scaling and Hadamard transformation. However, we observe that these transformed weights and activations can still remain steep and outspread. In this paper, we propose FlatQuant (Fast and Learnable Affine Transformation), a new post-training quantization approach to enhance flatness of weights and activations. Our approach identifies optimal affine transformations tailored to each linear layer, calibrated in hours via a lightweight objective. To reduce runtime overhead, we apply Kronecker decomposition to the transformation matrices, and fuse all operations in FlatQuant into a single kernel. Extensive experiments show that FlatQuant sets up a new state-of-the-art quantization benchmark. For instance, it achieves less than $\textbf{1}\%$ accuracy drop for W4A4 quantization on the LLaMA-3-70B model, surpassing SpinQuant by $\textbf{7.5}\%$. For inference latency, FlatQuant reduces the slowdown induced by pre-quantization transformation from 0.26x of QuaRot to merely $\textbf{0.07x}$, bringing up to $\textbf{2.3x}$ speedup for prefill and $\textbf{1.7x}$ speedup for decoding, respectively. Code is available at: \url{https://github.com/ruikangliu/FlatQuant}.

[Arxiv](https://arxiv.org/abs/2410.09426)