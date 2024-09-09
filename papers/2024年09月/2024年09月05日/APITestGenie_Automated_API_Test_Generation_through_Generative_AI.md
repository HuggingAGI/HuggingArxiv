# APITestGenie：利用生成式 AI 自动生成 API 测试

发布时间：2024年09月05日

`LLM应用` `软件开发`

> APITestGenie: Automated API Test Generation through Generative AI

# 摘要

> 由 LLM 驱动的智能助手能高精度生成程序和测试代码，提升开发与测试效率。然而，LLM 在测试 Web API 方面的应用研究尚显不足，这些 API 是现代软件系统的基石，测试难度颇高。为此，我们推出了 APITestGenie，一种利用 LLM 从业务需求和 API 规范生成可执行 API 测试脚本的方法与工具。实验显示，该工具在 10 个真实 API 中，57% 的情况下能生成有效脚本，三次尝试后成功率提升至 80%。我们建议在集成至 CI/CD 管道前，人工验证或优化生成的脚本，将 APITestGenie 定位为测试助手的角色。行业专家对采用该工具改进 API 测试流程表现出浓厚兴趣。

> Intelligent assistants powered by Large Language Models (LLMs) can generate program and test code with high accuracy, boosting developers' and testers' productivity. However, there is a lack of studies exploring LLMs for testing Web APIs, which constitute fundamental building blocks of modern software systems and pose significant test challenges. Hence, in this article, we introduce APITestGenie, an approach and tool that leverages LLMs to generate executable API test scripts from business requirements and API specifications. In experiments with 10 real-world APIs, the tool generated valid test scripts 57% of the time. With three generation attempts per task, this success rate increased to 80%. Human intervention is recommended to validate or refine generated scripts before integration into CI/CD pipelines, positioning our tool as a productivity assistant rather than a replacement for testers. Feedback from industry specialists indicated a strong interest in adopting our tool for improving the API test process.

[Arxiv](https://arxiv.org/abs/2409.03838)