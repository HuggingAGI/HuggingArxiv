# LoLCATs：探索大型语言模型的低秩线性化

发布时间：2024年10月14日

`LLM理论` `人工智能`

> LoLCATs: On Low-Rank Linearizing of Large Language Models

# 摘要

> 最近的研究揭示了将大型语言模型（LLMs）线性化的可能性，通过替换二次注意力为线性等效物，避免了高昂的预训练成本。然而，这种线性化往往导致模型质量大幅下降，且仍需处理数十亿token，仅适用于较小的LLMs。为此，我们提出了低秩线性转换（LoLCATs），一种仅需两步的简单方法，显著提升线性化质量，同时大幅减少内存和计算需求。首先，我们通过训练线性注意力匹配softmax注意力，实现注意力转移。接着，利用低秩适应（LoRA）调整误差，恢复模型质量。LoLCATs不仅显著提升了线性化质量、训练效率和可扩展性，还从Llama 3 8B和Mistral 7B v0.1中生成了最先进的次二次LLMs，在5-shot MMLU上提升了20多个点。此外，LoLCATs仅使用过去方法0.2%的参数和0.4%的训练token，成功创建了首个70B和405B线性化LLMs（比先前工作大50倍）。在与先前方法同等计算预算下，LoLCATs显著提升了线性化质量，将线性化与原始Llama 3.1 70B和405B LLMs在5-shot MMLU上的差距分别缩小了77.8%和78.1%。

> Recent works show we can linearize large language models (LLMs) -- swapping the quadratic attentions of popular Transformer-based LLMs with subquadratic analogs, such as linear attention -- avoiding the expensive pretraining costs. However, linearizing LLMs often significantly degrades model quality, still requires training over billions of tokens, and remains limited to smaller 1.3B to 7B LLMs. We thus propose Low-rank Linear Conversion via Attention Transfer (LoLCATs), a simple two-step method that improves LLM linearizing quality with orders of magnitudes less memory and compute. We base these steps on two findings. First, we can replace an LLM's softmax attentions with closely-approximating linear attentions, simply by training the linear attentions to match their softmax counterparts with an output MSE loss ("attention transfer"). Then, this enables adjusting for approximation errors and recovering LLM quality simply with low-rank adaptation (LoRA). LoLCATs significantly improves linearizing quality, training efficiency, and scalability. We significantly reduce the linearizing quality gap and produce state-of-the-art subquadratic LLMs from Llama 3 8B and Mistral 7B v0.1, leading to 20+ points of improvement on 5-shot MMLU. Furthermore, LoLCATs does so with only 0.2% of past methods' model parameters and 0.4% of their training tokens. Finally, we apply LoLCATs to create the first linearized 70B and 405B LLMs (50x larger than prior work). When compared with prior approaches under the same compute budgets, LoLCATs significantly improves linearizing quality, closing the gap between linearized and original Llama 3.1 70B and 405B LLMs by 77.8% and 78.1% on 5-shot MMLU.

[Arxiv](https://arxiv.org/abs/2410.10254)