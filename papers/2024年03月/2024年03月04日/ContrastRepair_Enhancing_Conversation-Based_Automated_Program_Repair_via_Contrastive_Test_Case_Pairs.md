# [ContrastRepair 是一种创新方法，通过构建并利用对比测试用例对，有效提升基于对话模式的自动化程序修复能力。](https://arxiv.org/abs/2403.01971)

发布时间：2024年03月04日

`Agent`

> ContrastRepair: Enhancing Conversation-Based Automated Program Repair via Contrastive Test Case Pairs

> 自动化程序修复技术APR致力于智能生成修复程序错误的补丁，近期，像ChatGPT这类大型语言模型在APR研究中崭露头角，特别是在对话式APR框架下成果喜人。然而，对话式APR的效果好坏很大程度上依赖于高质量的反馈信息。为此，我们创新性地提出了基于对话的APR方法——ContrastRepair，它通过向LLM输入对比测试对以提升修复效率。一对对比测试由失效测试和正常运行测试构成，能有效地引导LLM定位问题核心。ContrastRepair的核心思想是缩小自动生成的正常运行测试与原始失效测试之间的差异，从而精准锁定错误根源。借助这种富有信息且针对性强的反馈机制，ContrastRepair助力LLM生成更高效的bug修复代码。我们采用当前最尖端的LLM ChatGPT作为基础，设计出可与之反复交互直至产出合理补丁的ContrastRepair系统。经过在Defects4j、QuixBugs及HumanEval-Java等多个权威数据集上的严格测试，ContrastRepair展现出显著优势，不仅超越现有方法，还刷新了程序修复领域的技术新高度。以Defects4j 1.2和2.0为例，ContrastRepair成功修复了总计337个bug案例中的143例，相比之下，最佳基准方法仅修复了124例bug。

> Automated Program Repair (APR) aims to automatically generate patches for rectifying software bugs. Recent strides in Large Language Models (LLM), such as ChatGPT, have yielded encouraging outcomes in APR, especially within the conversation-driven APR framework. Nevertheless, the efficacy of conversation-driven APR is contingent on the quality of the feedback information. In this paper, we propose ContrastRepair, a novel conversation-based APR approach that augments conversation-driven APR by providing LLMs with contrastive test pairs. A test pair consists of a failing test and a passing test, which offer contrastive feedback to the LLM. Our key insight is to minimize the difference between the generated passing test and the given failing test, which can better isolate the root causes of bugs. By providing informative and specific feedback, ContrastRepair enables the LLM to produce effective bug fixes. The implementation of ContrastRepair is based on the state-of-the-art LLM, ChatGPT, and it iteratively interacts with ChatGPT until plausible patches are generated. We evaluate ContrastRepair on multiple benchmark datasets, including Defects4j, QuixBugs, and HumanEval-Java. The results demonstrate that ContrastRepair significantly outperforms existing methods, achieving a new state-of-the-art in program repair. For instance, among Defects4j 1.2 and 2.0, ContrastRepair correctly repairs 143 out of all 337 bug cases, while the best-performing baseline fixes 124 bugs.

[Arxiv](https://arxiv.org/abs/2403.01971)