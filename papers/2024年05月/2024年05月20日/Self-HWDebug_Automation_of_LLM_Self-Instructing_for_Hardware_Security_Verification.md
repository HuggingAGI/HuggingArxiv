# Self-HWDebug：利用LLM自我指导实现硬件安全验证的自动化

发布时间：2024年05月20日

`LLM应用

这篇论文主要讨论了如何利用大型语言模型（LLMs）来自动生成调试指令，以帮助解决硬件设计中的安全漏洞问题。具体来说，论文提出了一个名为Self-HWDebug的框架，该框架利用LLMs来生成针对特定硬件错误的缓解指令。这种方法减少了人类专家在调试过程中的参与，提高了调试效率和质量。因此，这篇论文属于LLM应用类别，因为它展示了LLMs在特定领域（硬件设计安全漏洞调试）的实际应用。` `硬件设计` `网络安全`

> Self-HWDebug: Automation of LLM Self-Instructing for Hardware Security Verification

# 摘要

> 指令调优的大型语言模型（LLMs）的兴起，为人工智能（AI）带来了显著进步，尤其是在响应特定提示方面。尽管这些模型广受欢迎，但将其应用于硬件设计中的安全漏洞调试，如RTL模块，特别是在SoC级别，仍面临诸多挑战。关键问题在于，精确设计指令以定位和缓解漏洞，需要人类专家投入大量时间和专业知识。为此，本文提出了创新框架Self-HWDebug，它利用LLMs自动生成调试指令。该框架首先提供一组已识别的关键硬件CWE列表中的错误及其缓解方案，然后引导LLMs生成针对性的缓解指令。这些LLM生成的指令随后被用作参考，解决同一CWE类别但在不同设计中的漏洞，展示了框架在相关安全问题上的解决方案扩展能力。Self-HWDebug通过模型自身输出来指导调试，大幅减少了人为干预。经过全面测试，Self-HWDebug不仅减轻了专家的负担，还提升了调试过程的质量。

> The rise of instruction-tuned Large Language Models (LLMs) marks a significant advancement in artificial intelligence (AI) (tailored to respond to specific prompts). Despite their popularity, applying such models to debug security vulnerabilities in hardware designs, i.e., register transfer language (RTL) modules, particularly at system-on-chip (SoC) level, presents considerable challenges. One of the main issues lies in the need for precisely designed instructions for pinpointing and mitigating the vulnerabilities, which requires substantial time and expertise from human experts. In response to this challenge, this paper proposes Self-HWDebug, an innovative framework that leverages LLMs to automatically create required debugging instructions. In Self-HWDebug, a set of already identified bugs from the most critical hardware common weakness enumeration (CWE) listings, along with mitigation resolutions, is provided to the framework, followed by prompting the LLMs to generate targeted instructions for such mitigation. The LLM-generated instructions are subsequently used as references to address vulnerabilities within the same CWE category but in totally different designs, effectively demonstrating the framework's ability to extend solutions across related security issues. Self-HWDebug significantly reduces human intervention by using the model's own output to guide debugging. Through comprehensive testing, Self-HWDebug proves not only to reduce experts' effort/time but also to even improve the quality of the debugging process.

[Arxiv](https://arxiv.org/abs/2405.12347)