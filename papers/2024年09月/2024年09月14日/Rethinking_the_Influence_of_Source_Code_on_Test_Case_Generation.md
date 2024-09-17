# 源代码如何影响测试用例生成？让我们重新审视这一问题。

发布时间：2024年09月14日

`LLM应用` `软件开发`

> Rethinking the Influence of Source Code on Test Case Generation

# 摘要

> 大型语言模型（LLM）广泛用于辅助测试生成，但若源代码有误，LLM 生成的测试会受误导。我们评估了五个开源和六个闭源 LLM 在四个数据集上的表现，发现错误代码显著降低了测试的准确性、覆盖率和错误检测能力。例如，HumanEval 数据集中，正确代码下 LLM 测试准确率为 80.45%，错误代码下仅为 57.12%。APPS 数据集中，正确代码提示检测到 39.85% 的错误，错误代码提示仅 19.61%。这些结果提示，LLM 在成熟代码上可防未来错误，但在早期代码上可能固化现有错误。因此，提升 LLM 对错误代码的抵抗力，以生成更可靠的测试，成为未来研究的重要方向。

> Large language models (LLMs) have been widely applied to assist test generation with the source code under test provided as the context. This paper aims to answer the question: If the source code under test is incorrect, will LLMs be misguided when generating tests? The effectiveness of test cases is measured by their accuracy, coverage, and bug detection effectiveness. Our evaluation results with five open- and six closed-source LLMs on four datasets demonstrate that incorrect code can significantly mislead LLMs in generating correct, high-coverage, and bug-revealing tests. For instance, in the HumanEval dataset, LLMs achieve 80.45% test accuracy when provided with task descriptions and correct code, but only 57.12% when given task descriptions and incorrect code. For the APPS dataset, prompts with correct code yield tests that detect 39.85% of the bugs, while prompts with incorrect code detect only 19.61%. These findings have important implications for the deployment of LLM-based testing: using it on mature code may help protect against future regression, but on early-stage immature code, it may simply bake in errors. Our findings also underscore the need for further research to improve LLMs resilience against incorrect code in generating reliable and bug-revealing tests.

[Arxiv](https://arxiv.org/abs/2409.09464)