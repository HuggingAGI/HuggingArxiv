# RETAIN：一款交互式工具，专为引导 LLM 迁移的回归测试而设计

发布时间：2024年09月05日

`LLM应用` `软件开发` `人工智能`

> RETAIN: Interactive Tool for Regression Testing Guided LLM Migration

# 摘要

> 随着大型语言模型（LLM）在各类应用中的普及，其快速演变为开发者提供了持续优化的契机。然而，这种频繁的适应也带来了模型迁移时的性能退化风险。尽管已有工具简化了提示工程的复杂性，但针对 LLM 迁移的回归测试需求仍未得到充分满足。为此，我们推出了 RETAIN，一个专为 LLM 迁移回归测试设计的工具。RETAIN 包含两个核心部分：一是为 LLM 迁移定制的交互界面，二是帮助理解模型行为差异的错误发现模块。该模块能生成详细的错误描述，助力提示优化。实证研究显示，RETAIN 在自动评估中表现优异，相比手动评估，用户能识别更多错误，实验更多提示，并在规定时间内提升 12% 的性能指标。

> Large Language Models (LLMs) are increasingly integrated into diverse applications. The rapid evolution of LLMs presents opportunities for developers to enhance applications continuously. However, this constant adaptation can also lead to performance regressions during model migrations. While several interactive tools have been proposed to streamline the complexity of prompt engineering, few address the specific requirements of regression testing for LLM Migrations. To bridge this gap, we introduce RETAIN (REgression Testing guided LLM migrAtIoN), a tool designed explicitly for regression testing in LLM Migrations. RETAIN comprises two key components: an interactive interface tailored to regression testing needs during LLM migrations, and an error discovery module that facilitates understanding of differences in model behaviors. The error discovery module generates textual descriptions of various errors or differences between model outputs, providing actionable insights for prompt refinement. Our automatic evaluation and empirical user studies demonstrate that RETAIN, when compared to manual evaluation, enabled participants to identify twice as many errors, facilitated experimentation with 75% more prompts, and achieves 12% higher metric scores in a given time frame.

[Arxiv](https://arxiv.org/abs/2409.03928)