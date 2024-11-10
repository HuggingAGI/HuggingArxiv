# 关于大型语言模型在自动化软件重构中的潜力的实证研究

发布时间：2024年11月07日

`LLM应用`

> An Empirical Study on the Potential of LLMs in Automated Software Refactoring

# 摘要

> 大型语言模型（LLM）的最新进展，使其有可能用 LLM 自动重构源代码。然而，与人类专家相比，LLM 在自动和准确进行重构方面的表现如何仍不清楚。为了填补这一空白，在本文中，我们进行了一项实证研究，以调查 LLM 在自动化软件重构中的潜力，重点是识别重构机会和推荐重构解决方案。我们首先构建了一个高质量的重构数据集，包括来自 20 个项目的 180 个真实世界的重构，并在该数据集上进行实证研究。以待重构的 Java 文档作为输入，ChatGPT 和 Gemini 分别仅从 180 个重构机会中识别出 28 个和 7 个。然而，解释预期的重构子类别并缩小提示中的搜索空间，大大将 ChatGPT 的成功率从 15.6％提高到 86.7％。关于重构解决方案的推荐，ChatGPT 为 180 个重构推荐了 176 个重构解决方案，并且 63.6％的推荐解决方案与（甚至优于）人类专家构建的解决方案相当。然而，ChatGPT 建议的 176 个解决方案中有 13 个，Gemini 建议的 137 个解决方案中有 9 个是不安全的，因为它们要么改变了源代码的功能，要么引入了语法错误，这表明基于 LLM 的重构存在风险。为此，我们提出了一种称为 RefactoringMirror 的检测和重新应用策略，以避免这种不安全的重构。通过使用经过充分测试的重构引擎将识别的重构重新应用到原始代码中，我们可以有效地减轻与基于 LLM 的自动化重构相关的风险，同时仍然利用 LLM 的智能来获得有价值的重构建议。

> Recent advances in large language models (LLMs), make it potentially feasible to automatically refactor source code with LLMs. However, it remains unclear how well LLMs perform compared to human experts in conducting refactorings automatically and accurately. To fill this gap, in this paper, we conduct an empirical study to investigate the potential of LLMs in automated software refactoring, focusing on the identification of refactoring opportunities and the recommendation of refactoring solutions. We first construct a high-quality refactoring dataset comprising 180 real-world refactorings from 20 projects, and conduct the empirical study on the dataset. With the to-be-refactored Java documents as input, ChatGPT and Gemini identified only 28 and 7 respectively out of the 180 refactoring opportunities. However, explaining the expected refactoring subcategories and narrowing the search space in the prompts substantially increased the success rate of ChatGPT from 15.6% to 86.7%. Concerning the recommendation of refactoring solutions, ChatGPT recommended 176 refactoring solutions for the 180 refactorings, and 63.6% of the recommended solutions were comparable to (even better than) those constructed by human experts. However, 13 out of the 176 solutions suggested by ChatGPT and 9 out of the 137 solutions suggested by Gemini were unsafe in that they either changed the functionality of the source code or introduced syntax errors, which indicate the risk of LLM-based refactoring. To this end, we propose a detect-and-reapply tactic, called RefactoringMirror, to avoid such unsafe refactorings. By reapplying the identified refactorings to the original code using thoroughly tested refactoring engines, we can effectively mitigate the risks associated with LLM-based automated refactoring while still leveraging LLM's intelligence to obtain valuable refactoring recommendations.

[Arxiv](https://arxiv.org/abs/2411.04444)