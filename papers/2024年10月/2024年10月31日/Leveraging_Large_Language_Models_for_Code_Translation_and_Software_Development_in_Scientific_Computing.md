# 借助大型语言模型实现科学计算中的代码翻译与软件开发

发布时间：2024年10月31日

`LLM应用` `科学计算` `代码开发`

> Leveraging Large Language Models for Code Translation and Software Development in Scientific Computing

# 摘要

> 基础模型和生成式人工智能（GenAI）的出现，有望变革科学计算领域的生产力，尤其是在代码开发、重构以及编程语言的转换上。不过，由于 GenAI 的输出无法确保正确，人工干预仍不可或缺。部分干预可借助特定任务工具实现自动化，同时还需其他用于正确性验证和有效提示开发的手段。我们探究了 GenAI 在大型强子对撞机（LHC）用于模拟粒子相互作用的遗留 Fortran 代码库中的代码翻译、语言互操作性及代码库检查方面的应用。在此过程中，我们开发了工具 CodeScribe，它将提示工程与用户监督相结合，构建了高效的代码转换流程。在本文中，我们展示了 CodeScribe 怎样助力将 Fortran 代码转为 C++，为遗留系统与现代 C++库的集成生成 Fortran-C API，并为代码组织和算法实现提供开发者支持。我们也阐述了 AI 驱动的代码翻译面临的挑战，突出了其在提升科学计算工作流程生产力方面的益处。

> The emergence of foundational models and generative artificial intelligence (GenAI) is poised to transform productivity in scientific computing, especially in code development, refactoring, and translating from one programming language to another. However, because the output of GenAI cannot be guaranteed to be correct, manual intervention remains necessary. Some of this intervention can be automated through task-specific tools, alongside additional methodologies for correctness verification and effective prompt development. We explored the application of GenAI in assisting with code translation, language interoperability, and codebase inspection within a legacy Fortran codebase used to simulate particle interactions at the Large Hadron Collider (LHC). In the process, we developed a tool, CodeScribe, which combines prompt engineering with user supervision to establish an efficient process for code conversion. In this paper, we demonstrate how CodeScribe assists in converting Fortran code to C++, generating Fortran-C APIs for integrating legacy systems with modern C++ libraries, and providing developer support for code organization and algorithm implementation. We also address the challenges of AI-driven code translation and highlight its benefits for enhancing productivity in scientific computing workflows.

[Arxiv](https://arxiv.org/abs/2410.24119)