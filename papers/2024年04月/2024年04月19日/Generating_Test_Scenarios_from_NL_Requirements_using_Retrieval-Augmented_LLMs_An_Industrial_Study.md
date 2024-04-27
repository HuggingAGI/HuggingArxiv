# 本工业研究探讨了如何利用增强检索功能的大型语言模型，从自然语言需求中生成测试场景。

发布时间：2024年04月19日

`RAG` `软件测试`

> Generating Test Scenarios from NL Requirements using Retrieval-Augmented LLMs: An Industrial Study

# 摘要

> 测试场景是针对特定软件功能的测试用例的具体应用，它们通过定义软件运行条件和预期成果，确保软件功能的全面集成测试。这些场景对于在多变条件下系统性地测试应用程序、捕捉边缘情况、发现潜在问题以及确保软件的整体性能和可靠性至关重要。然而，制定测试场景既繁琐又复杂，它不仅要求深入掌握软件功能和相关领域知识，还对时间和预算本就紧张的需求工程师和测试团队提出了更高的要求。本论文提出了一种名为RAGTAG的自动化测试场景生成方法，该方法利用检索增强生成（RAG）技术和大型语言模型（LLM）。RAG技术使得特定领域的知识能够与LLM的生成能力相结合。我们在奥地利邮政的两个双语（德语和英语）工业项目中对RAGTAG进行了评估。通过与四位专家就相关性、覆盖度、准确性、连贯性和可行性五个方面进行的访谈调查，我们证实了RAGTAG在自动化生成测试场景方面的潜力。尽管面对分析双语需求的挑战，RAGTAG仍能生成与原始需求高度契合且全面覆盖预期功能各个方面的场景。这些场景不仅易于专家理解，也适合在项目环境中进行测试。尽管整体正确性得到了认可，但在捕捉精确动作序列和领域细节方面仍有改进空间，这表明在使用LLM时，领域专业知识的运用至关重要。

> Test scenarios are specific instances of test cases that describe actions to validate a particular software functionality. By outlining the conditions under which the software operates and the expected outcomes, test scenarios ensure that the software functionality is tested in an integrated manner. Test scenarios are crucial for systematically testing an application under various conditions, including edge cases, to identify potential issues and guarantee overall performance and reliability. Specifying test scenarios is tedious and requires a deep understanding of software functionality and the underlying domain. It further demands substantial effort and investment from already time- and budget-constrained requirements engineers and testing teams. This paper presents an automated approach (RAGTAG) for test scenario generation using Retrieval-Augmented Generation (RAG) with Large Language Models (LLMs). RAG allows the integration of specific domain knowledge with LLMs' generation capabilities. We evaluate RAGTAG on two industrial projects from Austrian Post with bilingual requirements in German and English. Our results from an interview survey conducted with four experts on five dimensions -- relevance, coverage, correctness, coherence and feasibility, affirm the potential of RAGTAG in automating test scenario generation. Specifically, our results indicate that, despite the difficult task of analyzing bilingual requirements, RAGTAG is able to produce scenarios that are well-aligned with the underlying requirements and provide coverage of different aspects of the intended functionality. The generated scenarios are easily understandable to experts and feasible for testing in the project environment. The overall correctness is deemed satisfactory; however, gaps in capturing exact action sequences and domain nuances remain, underscoring the need for domain expertise when applying LLMs.

[Arxiv](https://arxiv.org/abs/2404.12772)