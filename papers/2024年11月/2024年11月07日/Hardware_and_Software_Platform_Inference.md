# 硬件与软件平台的推断

发布时间：2024年11月07日

`LLM应用` `机器学习`

> Hardware and Software Platform Inference

# 摘要

> 如今，由于前期硬件基础设施和能源成本高昂，购买大型语言模型（LLM）的推理服务而非自行托管已成为常见的商业操作。但作为买家，没有办法核实所宣传服务的真实性，比如服务所使用的硬件平台，像是否真的用 NVIDIA H100 提供服务。而且，有报道称，模型供应商可能提供与宣传稍有不同的模型，往往是为了让它们能在更便宜的硬件上运行。如此一来，客户为能在更贵硬件上访问强大的模型支付了高价，最终却由更便宜硬件上（可能性能更差）的更廉价模型提供服务。在本文中，我们引入了	extit{	extbf{硬件和软件平台推理（HSPI）}}——一种仅依据（黑盒）机器学习模型的输入输出行为来识别底层\GPU{}架构和软件栈的方法。我们的方法借助各种\GPU{}架构和编译器的固有差异来区分不同的\GPU{}类型和软件栈。通过分析模型输出中的数值模式，我们提出了一个分类框架，能够精确识别用于模型推理的\GPU{}以及底层软件配置。我们的成果表明从黑盒模型推断\GPU{}类型是可行的。我们针对在不同真实硬件上服务的模型评估了 HSPI，发现在白盒环境下，我们能以 83.9％至 100％的准确率区分不同的\GPU{}。即便在黑盒环境中，我们也能取得比随机猜测准确率高三倍的结果。

> It is now a common business practice to buy access to large language model (LLM) inference rather than self-host, because of significant upfront hardware infrastructure and energy costs. However, as a buyer, there is no mechanism to verify the authenticity of the advertised service including the serving hardware platform, e.g. that it is actually being served using an NVIDIA H100. Furthermore, there are reports suggesting that model providers may deliver models that differ slightly from the advertised ones, often to make them run on less expensive hardware. That way, a client pays premium for a capable model access on more expensive hardware, yet ends up being served by a (potentially less capable) cheaper model on cheaper hardware. In this paper we introduce \textit{\textbf{hardware and software platform inference (HSPI)}} -- a method for identifying the underlying \GPU{} architecture and software stack of a (black-box) machine learning model solely based on its input-output behavior. Our method leverages the inherent differences of various \GPU{} architectures and compilers to distinguish between different \GPU{} types and software stacks. By analyzing the numerical patterns in the model's outputs, we propose a classification framework capable of accurately identifying the \GPU{} used for model inference as well as the underlying software configuration. Our findings demonstrate the feasibility of inferring \GPU{} type from black-box models. We evaluate HSPI against models served on different real hardware and find that in a white-box setting we can distinguish between different \GPU{}s with between $83.9\%$ and $100\%$ accuracy. Even in a black-box setting we are able to achieve results that are up to three times higher than random guess accuracy.

[Arxiv](https://arxiv.org/abs/2411.05197)