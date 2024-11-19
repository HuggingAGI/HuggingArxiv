# REACCEPT：基于动态验证与大型语言模型的生产和测试代码自动协同进化

发布时间：2024年11月17日

`LLM应用`

> REACCEPT: Automated Co-evolution of Production and Test Code Based on Dynamic Validation and Large Language Models

# 摘要

> 同步生产和测试代码，也就是 PT 协同进化，在软件开发生命周期里对于软件质量极为关键。现有的自动 PT 协同进化手段，要么运用预先设定的启发式规则，要么依赖于机器学习技术的简单运用。受底层技术所限，现有的方法要么只是部分实现了 PT 协同进化（比如，仅能自动化识别过时的测试代码），要么准确性欠佳。
    在本文中，我们提出了 REACCEPT 这一全新的方法，它借助大型语言模型和动态验证来全面实现 PT 协同进化（即能够同时识别和更新过时的测试用例）。REACCEPT 依靠基于经验的提示模板生成、动态验证以及检索增强生成技术来达成自动化的 PT 协同进化。为评估 REACCEPT 的有效性，我们针对 537 个 Java 项目的数据集展开了广泛实验，并将 REACCEPT 的性能与若干前沿方法进行了对比。结果显示，REACCEPT 在正确识别的过时测试代码上达成了 60.16%的更新准确率，比最先进的技术 CEPROT 高出 90%。这证明 REACCEPT 能够切实助力开发人员维护测试代码，提升整体软件质量并降低维护工作量。

> Synchronizing production and test code, known as PT co-evolution, is critical for software quality in the software development lifecycle. Existing methods for automatic PT co-evolution either utilize predefined heuristic rules or rely on simple application of machine learning techniques. Due to the limitations of underlying techniques, existing methods either only partially automate PT co-evolution (e.g., only automate obsolete test code identification) or result in low accuracy.
  In this paper, we propose REACCEPT, a novel approach that leverages large language models and dynamic validation to fully automate PT co-evolution (i.e., capable of both identifying and updating obsolete test cases). REACCEPT relies on experience-based prompt template generation, dynamic validation, and retrieval-augmented generation techniques to accomplish automated PT co-evolution. To evaluate REACCEPT's effectiveness, we extensive experiments with a dataset of 537 Java projects and compared REACCEPT's performance with several state-of-the-art methods. Results show that REACCEPT achieved an update accuracy of 60.16% on correctly identified obsolete test code, surpassing the state-of-the-art technique CEPROT by 90%. This confirms that REACCEPT can effectively assist developers in maintaining test code, improving overall software quality and reducing maintenance effort.

[Arxiv](https://arxiv.org/abs/2411.11033)