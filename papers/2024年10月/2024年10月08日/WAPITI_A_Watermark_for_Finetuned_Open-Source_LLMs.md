# WAPITI：为微调开源 LLM 打造的水印

发布时间：2024年10月08日

`LLM应用` `人工智能` `网络安全`

> WAPITI: A Watermark for Finetuned Open-Source LLMs

# 摘要

> 在 LLM 生成的文本中嵌入不可察觉的统计模式，使其可被算法检测，水印技术因此成为解决 LLM 潜在危害和偏见的有力工具。然而，开源模型面临两大挑战：与微调模型的兼容性问题及易受微调攻击。为此，我们提出 WAPITI，通过参数集成将水印从基础模型转移到微调模型，实现首个保留微调能力的开源 LLM 水印，并有效防御微调攻击。实验证明，WAPITI 不仅能成功注入水印，还与微调模型高度兼容。我们还深入探讨了参数编辑对水印强度及模型整体能力的影响。

> Watermarking of large language models (LLMs) generation embeds an imperceptible statistical pattern within texts, making it algorithmically detectable. Watermarking is a promising method for addressing potential harm and biases from LLMs, as it enables traceability, accountability, and detection of manipulated content, helping to mitigate unintended consequences. However, for open-source models, watermarking faces two major challenges: (i) incompatibility with fine-tuned models, and (ii) vulnerability to fine-tuning attacks. In this work, we propose WAPITI, a new method that transfers watermarking from base models to fine-tuned models through parameter integration. To the best of our knowledge, we propose the first watermark for fine-tuned open-source LLMs that preserves their fine-tuned capabilities. Furthermore, our approach offers an effective defense against fine-tuning attacks. We test our method on various model architectures and watermarking strategies. Results demonstrate that our method can successfully inject watermarks and is highly compatible with fine-tuned models. Additionally, we offer an in-depth analysis of how parameter editing influences the watermark strength and overall capabilities of the resulting models.

[Arxiv](https://arxiv.org/abs/2410.06467)