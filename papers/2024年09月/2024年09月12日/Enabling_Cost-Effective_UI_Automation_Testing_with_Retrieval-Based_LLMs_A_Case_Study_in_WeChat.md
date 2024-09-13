# 利用基于检索的 LLM 实现高性价比的 UI 自动化测试：微信实践案例

发布时间：2024年09月12日

`RAG` `软件测试` `移动应用`

> Enabling Cost-Effective UI Automation Testing with Retrieval-Based LLMs: A Case Study in WeChat

# 摘要

> UI自动化测试对保障移动应用质量至关重要。尽管机器学习技术在生成测试方面日益普及，但仍面临UI元素不匹配等挑战。大型语言模型（LLM）通过其语义理解能力解决了这些问题，但在工业级应用测试中，成本优化和知识限制仍存在显著差距。为此，我们推出CAT，结合机器学习和LLM与最佳实践，为工业应用提供高性价比的UI自动化测试。CAT利用检索增强生成（RAG）获取工业应用使用示例，辅助LLM生成特定操作序列，并结合机器学习技术，以LLM为优化器，精准映射UI目标元素。在微信测试数据集上的评估显示，CAT以0.34美元成本实现90%自动化，超越现有技术。此外，CAT已集成至微信测试平台，有效检测141个错误，显著提升开发者测试效率。

> UI automation tests play a crucial role in ensuring the quality of mobile applications. Despite the growing popularity of machine learning techniques to generate these tests, they still face several challenges, such as the mismatch of UI elements. The recent advances in Large Language Models (LLMs) have addressed these issues by leveraging their semantic understanding capabilities. However, a significant gap remains in applying these models to industrial-level app testing, particularly in terms of cost optimization and knowledge limitation. To address this, we introduce CAT to create cost-effective UI automation tests for industry apps by combining machine learning and LLMs with best practices. Given the task description, CAT employs Retrieval Augmented Generation (RAG) to source examples of industrial app usage as the few-shot learning context, assisting LLMs in generating the specific sequence of actions. CAT then employs machine learning techniques, with LLMs serving as a complementary optimizer, to map the target element on the UI screen. Our evaluations on the WeChat testing dataset demonstrate the CAT's performance and cost-effectiveness, achieving 90% UI automation with $0.34 cost, outperforming the state-of-the-art. We have also integrated our approach into the real-world WeChat testing platform, demonstrating its usefulness in detecting 141 bugs and enhancing the developers' testing process.

[Arxiv](https://arxiv.org/abs/2409.07829)