# 编程无孤岛：借助代码搜索、生成与修复，迈向全自动编程

发布时间：2024年09月05日

`LLM应用` `软件工程` `人工智能`

> No Man is an Island: Towards Fully Automatic Programming by Code Search, Code Generation and Program Repair

# 摘要

> 自动编程旨在减少人类在代码生成中的干预，一直是软件工程领域的长期挑战。研究人员正致力于三个主要方向：（1）从外部数据库中重用代码片段的代码搜索；（2）从自然语言生成新代码片段的代码生成；（3）通过修复错误来改进现有代码的程序修复。尽管技术有所进步，但现有方法的有效性仍有限，如搜索代码的可用性和生成代码的正确性。借鉴开发人员常用的外部工具，如代码搜索引擎和测试工具，我们提出了 \toolname{}，一个整合了代码搜索、生成和修复的自动编程框架。该框架利用大型语言模型（LLMs），首先通过不同策略检索相似代码片段，进而指导代码生成。生成的代码通过编译器和测试用例验证，并构建修复提示以生成正确补丁。初步实验显示，该框架帮助 CodeLlama 解决了 267 个编程问题，改进率达 62.53%。作为通用框架，\toolname{} 首次将三个研究领域结合，并展示了传统工具增强 LLMs 在自动编程中应用的潜力。

> Automatic programming attempts to minimize human intervention in the generation of executable code, and has been a long-standing challenge in the software engineering community. To advance automatic programming, researchers are focusing on three primary directions: (1) code search that reuses existing code snippets from external databases; (2) code generation that produces new code snippets from natural language; and (3) program repair that refines existing code snippets by fixing detected bugs. Despite significant advancements, the effectiveness of state-of-the-art techniques is still limited, such as the usability of searched code and the correctness of generated code.
  Motivated by the real-world programming process, where developers usually use various external tools to aid their coding processes, such as code search engines and code testing tools, in this work, we propose \toolname{}, an automatic programming framework that leverages recent large language models (LLMs) to integrate the three research areas to address their inherent limitations. In particular, our framework first leverages different code search strategies to retrieve similar code snippets, which are then used to further guide the code generation process of LLMs. Our framework further validates the quality of generated code by compilers and test cases, and constructs repair prompts to query LLMs for generating correct patches. We conduct preliminary experiments to demonstrate the potential of our framework, \eg helping CodeLlama solve 267 programming problems with an improvement of 62.53\%. As a generic framework, \toolname{} can integrate various code search, generation, and repair tools, combining these three research areas together for the first time. More importantly, it demonstrates the potential of using traditional SE tools to enhance the usability of LLMs in automatic programming.

[Arxiv](https://arxiv.org/abs/2409.03267)