# UVLLM：一个运用 LLMs 的自动化通用 RTL 验证框架

发布时间：2024年11月25日

`LLM应用` `硬件设计` `嵌入式系统`

> UVLLM: An Automated Universal RTL Verification Framework using LLMs

# 摘要

> 验证嵌入式系统中的硬件设计极为关键，但往往费力又耗时。现有的解决方案虽提升了自动化水平，却常依赖不切实际的假设。为应对这些挑战，我们推出全新框架 UVLLM，将大型语言模型（LLMs）与通用验证方法（UVM）相结合，放宽此类假设。UVLLM 大幅增强了易出错的寄存器传输级（RTL）代码测试与修复的自动化程度，这是验证开发的关键一环。与现有方法不同，UVLLM 能确保在验证过程中触发所有错误，在我们所提出的基准上，语法错误修复率达 86.99%，功能错误修复率达 71.92%。这些成果显示验证效率大幅提升。另外，我们的研究指出了 LLM 应用的当前局限，尤其是对大量训练数据的依赖。我们强调了 LLMs 在硬件设计验证中的变革潜力，并为未来 AI 驱动的硬件设计方法研究指明了有前景的方向。数据集和代码的 Repo.：https://anonymous.4open.science/r/UVLLM/。

> Verifying hardware designs in embedded systems is crucial but often labor-intensive and time-consuming. While existing solutions have improved automation, they frequently rely on unrealistic assumptions. To address these challenges, we introduce a novel framework, UVLLM, which combines Large Language Models (LLMs) with the Universal Verification Methodology (UVM) to relax these assumptions. UVLLM significantly enhances the automation of testing and repairing error-prone Register Transfer Level (RTL) codes, a critical aspect of verification development. Unlike existing methods, UVLLM ensures that all errors are triggered during verification, achieving a syntax error fix rate of 86.99% and a functional error fix rate of 71.92% on our proposed benchmark. These results demonstrate a substantial improvement in verification efficiency. Additionally, our study highlights the current limitations of LLM applications, particularly their reliance on extensive training data. We emphasize the transformative potential of LLMs in hardware design verification and suggest promising directions for future research in AI-driven hardware design methodologies. The Repo. of dataset and code: https://anonymous.4open.science/r/UVLLM/.

[Arxiv](https://arxiv.org/abs/2411.16238)