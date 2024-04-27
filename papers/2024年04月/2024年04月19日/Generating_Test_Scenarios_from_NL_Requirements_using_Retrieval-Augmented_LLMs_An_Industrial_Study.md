# 本研究探讨了如何利用增强检索功能的大规模语言模型，从自然语言需求中生成测试场景，以适应工业界的实际应用需求。

发布时间：2024年04月19日

`分类：RAG` `软件测试`

> Generating Test Scenarios from NL Requirements using Retrieval-Augmented LLMs: An Industrial Study

# 摘要

> 测试场景是针对特定软件功能验证的详细测试案例，它们通过定义软件运行条件和预期成果，确保软件功能的全面测试。这些场景对于在多变条件下系统化测试应用、识别潜在问题、确保性能和可靠性至关重要。然而，设计测试场景既繁琐又复杂，它要求深入理解软件功能及其相关领域知识，这对时间和资源有限的工程师和测试团队来说是一项挑战。本论文提出了一种名为RAGTAG的自动化测试场景生成方法，该方法利用检索增强生成（RAG）技术结合大型语言模型（LLMs），以整合特定领域的知识。我们在奥地利邮政的两个工业项目中进行了RAGTAG的评估，这些项目需求涉及德语和英语两种语言。通过与四位专家的访谈调查，我们从五个维度——相关性、覆盖度、准确性、连贯性和可行性——验证了RAGTAG的潜力。尽管面对双语需求分析的挑战，RAGTAG仍能生成与需求紧密对齐、全面覆盖预期功能各个方面的测试场景。这些场景不仅易于专家理解，也适合在项目环境中进行测试。尽管整体正确性达到满意水平，但在捕捉精确动作序列和领域细节方面仍有改进空间，这表明在使用LLMs时，领域专业知识的运用至关重要。

> Test scenarios are specific instances of test cases that describe actions to validate a particular software functionality. By outlining the conditions under which the software operates and the expected outcomes, test scenarios ensure that the software functionality is tested in an integrated manner. Test scenarios are crucial for systematically testing an application under various conditions, including edge cases, to identify potential issues and guarantee overall performance and reliability. Specifying test scenarios is tedious and requires a deep understanding of software functionality and the underlying domain. It further demands substantial effort and investment from already time- and budget-constrained requirements engineers and testing teams. This paper presents an automated approach (RAGTAG) for test scenario generation using Retrieval-Augmented Generation (RAG) with Large Language Models (LLMs). RAG allows the integration of specific domain knowledge with LLMs' generation capabilities. We evaluate RAGTAG on two industrial projects from Austrian Post with bilingual requirements in German and English. Our results from an interview survey conducted with four experts on five dimensions -- relevance, coverage, correctness, coherence and feasibility, affirm the potential of RAGTAG in automating test scenario generation. Specifically, our results indicate that, despite the difficult task of analyzing bilingual requirements, RAGTAG is able to produce scenarios that are well-aligned with the underlying requirements and provide coverage of different aspects of the intended functionality. The generated scenarios are easily understandable to experts and feasible for testing in the project environment. The overall correctness is deemed satisfactory; however, gaps in capturing exact action sequences and domain nuances remain, underscoring the need for domain expertise when applying LLMs.

[Arxiv](https://arxiv.org/abs/2404.12772)