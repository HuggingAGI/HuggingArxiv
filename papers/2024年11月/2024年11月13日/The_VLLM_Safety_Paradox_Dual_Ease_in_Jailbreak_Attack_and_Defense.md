# VLLM 安全悖论：越狱攻击和防御的双重轻松

发布时间：2024年11月13日

`LLM应用` `视觉语言模型` `网络安全`

> The VLLM Safety Paradox: Dual Ease in Jailbreak Attack and Defense

# 摘要

> 视觉大型语言模型（VLLMs）容易受到越狱攻击的脆弱性并不令人惊讶。然而，最近针对这些攻击的防御机制在基准测试中已经达到了接近饱和的性能，而且往往付出的努力极小。这种攻击和防御同时的高性能呈现出一个令人困惑的悖论。解决它对于推进可信模型的发展至关重要。为了解决这个研究空白，我们首先研究为什么 VLLMs 容易受到这些攻击。然后我们做出了一个关键的观察：现有的防御机制存在一个“过度谨慎”的问题，导致即使在存在良性输入的情况下也会出现意外的弃权。此外，我们发现两种代表性的越狱评估方法经常表现出偶然的一致性。这种限制在评估攻击策略或防御机制时可能会产生误导。除了这些实证观察之外，我们在这项工作中的另一个贡献是重新利用现有的 LLM 的护栏，作为 VLLM 响应之前的一种有效的替代检测器。我们相信这些发现为重新思考关于基准数据集、评估方法和防御策略的 VLLM 安全性的基础发展提供了有用的见解。

> The vulnerability of Vision Large Language Models (VLLMs) to jailbreak attacks appears as no surprise. However, recent defense mechanisms against these attacks have reached near-saturation performance on benchmarks, often with minimal effort. This simultaneous high performance in both attack and defense presents a perplexing paradox. Resolving it is critical for advancing the development of trustworthy models. To address this research gap, we first investigate why VLLMs are prone to these attacks. We then make a key observation: existing defense mechanisms suffer from an \textbf{over-prudence} problem, resulting in unexpected abstention even in the presence of benign inputs. Additionally, we find that the two representative evaluation methods for jailbreak often exhibit chance agreement. This limitation makes it potentially misleading when evaluating attack strategies or defense mechanisms. Beyond these empirical observations, our another contribution in this work is to repurpose the guardrails of LLMs on the shelf, as an effective alternative detector prior to VLLM response. We believe these findings offer useful insights to rethink the foundational development of VLLM safety with respect to benchmark datasets, evaluation methods, and defense strategies.

[Arxiv](https://arxiv.org/abs/2411.08410)