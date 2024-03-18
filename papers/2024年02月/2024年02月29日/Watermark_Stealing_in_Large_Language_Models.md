# 在大型语言模型（LLM）中探讨水印窃取问题

发布时间：2024年02月29日

`LLM应用`

> Watermark Stealing in Large Language Models

> LLM 水印作为识别 AI 内容的有效手段备受瞩目，有人认为现有技术已接近实战阶段。但本研究对此提出异议，揭示了水印窃取（WS）是这类技术的一大安全隐患。研究证明，通过调用带水印 LLN 的 API 进行逆向解析，不仅能如先前研究所示实施可行的伪造攻击，还意外地大幅提升了擦除攻击的效果。我们首开先河，提出了自动化 WS 算法，并首次在真实场景下对欺骗与擦除攻击进行了全方位探究。实验显示，攻击者仅需不足50美元的成本，就能以超过80%的成功率轻松破解并擦除那些曾被认为安全可靠的尖端水印方案。这一系列发现在一定程度上颠覆了业界对 LLM 水印技术的传统认知，迫切要求研发更为坚固的水印保护机制。为了推动进一步研究，我们已在 https://watermark-stealing.org 上公开了所有代码及相关实例。

> LLM watermarking has attracted attention as a promising way to detect AI-generated content, with some works suggesting that current schemes may already be fit for deployment. In this work we dispute this claim, identifying watermark stealing (WS) as a fundamental vulnerability of these schemes. We show that querying the API of the watermarked LLM to approximately reverse-engineer a watermark enables practical spoofing attacks, as suggested in prior work, but also greatly boosts scrubbing attacks, which was previously unnoticed. We are the first to propose an automated WS algorithm and use it in the first comprehensive study of spoofing and scrubbing in realistic settings. We show that for under $50 an attacker can both spoof and scrub state-of-the-art schemes previously considered safe, with average success rate of over 80%. Our findings challenge common beliefs about LLM watermarking, stressing the need for more robust schemes. We make all our code and additional examples available at https://watermark-stealing.org.

[Arxiv](https://arxiv.org/abs/2402.19361)