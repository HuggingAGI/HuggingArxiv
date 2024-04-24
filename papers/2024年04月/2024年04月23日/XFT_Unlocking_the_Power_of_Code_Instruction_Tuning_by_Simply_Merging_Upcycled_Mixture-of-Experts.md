# XFT：轻松融合再利用的专家混合模型，释放代码指令优化的强大能量。

发布时间：2024年04月23日

`LLM应用` `机器学习` `软件开发`

> XFT: Unlocking the Power of Code Instruction Tuning by Simply Merging Upcycled Mixture-of-Experts

# 摘要

> 我们推出了 XFT，这是一种简洁而高效的训练框架，它通过融合升级版专家混合模型（MoE），充分激发了指令调优的大型语言模型（LLMs）的潜能。传统稀疏升级方法在提升指令调优方面效果有限，而 XFT 通过引入共享专家机制和创新的路由权重归一化策略，显著增强了这一能力。经过对升级后的 MoE 模型进行精细调优，XFT 采用了一种可学习的模型融合技术，将之还原为密集模型，而计算成本却与密集模型相当，达到了升级版 MoE 的性能水平。在 1.3 亿参数的模型上应用 XFT，我们打造了一个新的小型代码 LLM（参数量小于 3B），在 HumanEval 和 HumanEval+ 测试中分别达到了 67.1 和 64.6 的准确率。在相同数据集和模型架构下，XFT 在 HumanEval+ 的监督微调（SFT）上提升了 13%，同时在 MBPP+、MultiPL-E 和 DS-1000 上也实现了 2% 至 13% 的一致性提升，证明了其广泛的适用性。XFT 与现有技术如 Evol-Instruct 和 OSS-Instruct 互为补充，为代码指令调优提供了新的优化路径。相关代码已在 https://github.com/ise-uiuc/xft 上开源。

> We introduce XFT, a simple yet powerful training scheme, by simply merging upcycled Mixture-of-Experts (MoE) to unleash the performance limit of instruction-tuned code Large Language Models (LLMs). While vanilla sparse upcycling fails to improve instruction tuning, XFT introduces a shared expert mechanism with a novel routing weight normalization strategy into sparse upcycling, which significantly boosts instruction tuning. After fine-tuning the upcycled MoE model, XFT introduces a learnable model merging mechanism to compile the upcycled MoE model back to a dense model, achieving upcycled MoE-level performance with only dense-model compute. By applying XFT to a 1.3B model, we create a new state-of-the-art tiny code LLM (<3B) with 67.1 and 64.6 pass@1 on HumanEval and HumanEval+ respectively. With the same data and model architecture, XFT improves supervised fine-tuning (SFT) by 13% on HumanEval+, along with consistent improvements from 2% to 13% on MBPP+, MultiPL-E, and DS-1000, demonstrating its generalizability. XFT is fully orthogonal to existing techniques such as Evol-Instruct and OSS-Instruct, opening a new dimension for improving code instruction tuning. Codes are available at https://github.com/ise-uiuc/xft .

[Arxiv](https://arxiv.org/abs/2404.15247)