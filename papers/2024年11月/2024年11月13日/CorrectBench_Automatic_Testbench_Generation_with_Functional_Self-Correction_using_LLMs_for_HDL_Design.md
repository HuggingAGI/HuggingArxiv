# CorrectBench：使用大型语言模型（LLMs）对 HDL 设计进行具有功能自校正的自动测试平台生成

发布时间：2024年11月13日

`LLM应用` `硬件设计` `测试平台生成`

> CorrectBench: Automatic Testbench Generation with Functional Self-Correction using LLMs for HDL Design

# 摘要

> 功能仿真在数字硬件设计中是必不可少的一步。最近，利用大型语言模型（LLMs）进行硬件测试平台生成任务的兴趣日益浓厚。然而，与 LLMs 相关的内在不稳定性经常导致生成的测试平台出现功能错误。以前的方法在没有人工干预的情况下不包含自动功能校正机制，并且仍然成功率低，特别是对于顺序任务。为了解决这个问题，我们提出了 CorrectBench，这是一个具有功能自验证和自校正的自动测试平台生成框架。仅利用自然语言中的 RTL 规范，所提出的方法能够以 88.85%的成功率验证生成的测试平台的正确性。此外，所提出的基于 LLM 的校正器利用在自验证过程中获得的错误信息对生成的测试平台进行功能自校正。比较分析表明，我们的方法在所有评估任务中的通过率为 70.13%，而之前基于 LLM 的测试平台生成框架为 52.18%，直接基于 LLM 的生成方法为 33.33%。特别是在顺序电路中，我们工作的性能比以前在顺序任务中的工作高出 62.18%，通过率几乎是直接方法的 5 倍。代码和实验结果在链接 https://github.com/AutoBench/CorrectBench 开源。

> Functional simulation is an essential step in digital hardware design. Recently, there has been a growing interest in leveraging Large Language Models (LLMs) for hardware testbench generation tasks. However, the inherent instability associated with LLMs often leads to functional errors in the generated testbenches. Previous methods do not incorporate automatic functional correction mechanisms without human intervention and still suffer from low success rates, especially for sequential tasks. To address this issue, we propose CorrectBench, an automatic testbench generation framework with functional self-validation and self-correction. Utilizing only the RTL specification in natural language, the proposed approach can validate the correctness of the generated testbenches with a success rate of 88.85%. Furthermore, the proposed LLM-based corrector employs bug information obtained during the self-validation process to perform functional self-correction on the generated testbenches. The comparative analysis demonstrates that our method achieves a pass ratio of 70.13% across all evaluated tasks, compared with the previous LLM-based testbench generation framework's 52.18% and a direct LLM-based generation method's 33.33%. Specifically in sequential circuits, our work's performance is 62.18% higher than previous work in sequential tasks and almost 5 times the pass ratio of the direct method. The codes and experimental results are open-sourced at the link: https://github.com/AutoBench/CorrectBench

[Arxiv](https://arxiv.org/abs/2411.08510)