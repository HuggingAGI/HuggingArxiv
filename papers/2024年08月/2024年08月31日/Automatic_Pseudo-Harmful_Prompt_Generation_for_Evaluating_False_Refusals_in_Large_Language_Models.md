# 本研究旨在通过自动生成伪有害提示，评估大型语言模型在处理错误拒绝时的表现。

发布时间：2024年08月31日

`LLM应用` `人工智能` `网络安全`

> Automatic Pseudo-Harmful Prompt Generation for Evaluating False Refusals in Large Language Models

# 摘要

> 安全对齐的 LLM 有时会误拒无害的提示，如“如何杀蚊”，这不仅令用户沮丧，还可能引发公众对价值对齐的反感。本文中，我们首创了一种方法，自动生成多样、内容可控且模型依赖的伪有害提示。据此，我们构建了规模十倍于现有数据集的 PHTest，涵盖更多误拒模式，并单独标记争议提示。在 PHTest 上评估 20 个 LLM，揭示了新见解。研究发现，减少误拒与提高防越狱安全性间存在权衡，且许多防越狱措施显著增加误拒率，损害可用性。我们的方法和数据集助力开发者评估和优化更安全、更可用的 LLM。代码和数据集已公开于 https://github.com/umd-huang-lab/FalseRefusal。

> Safety-aligned large language models (LLMs) sometimes falsely refuse pseudo-harmful prompts, like "how to kill a mosquito," which are actually harmless. Frequent false refusals not only frustrate users but also provoke a public backlash against the very values alignment seeks to protect. In this paper, we propose the first method to auto-generate diverse, content-controlled, and model-dependent pseudo-harmful prompts. Using this method, we construct an evaluation dataset called PHTest, which is ten times larger than existing datasets, covers more false refusal patterns, and separately labels controversial prompts. We evaluate 20 LLMs on PHTest, uncovering new insights due to its scale and labeling. Our findings reveal a trade-off between minimizing false refusals and improving safety against jailbreak attacks. Moreover, we show that many jailbreak defenses significantly increase the false refusal rates, thereby undermining usability. Our method and dataset can help developers evaluate and fine-tune safer and more usable LLMs. Our code and dataset are available at https://github.com/umd-huang-lab/FalseRefusal

[Arxiv](https://arxiv.org/abs/2409.00598)