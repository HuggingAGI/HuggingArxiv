# Top Pass：通过优化 Pass@k 排名，提升代码生成质量

发布时间：2024年08月11日

`LLM应用` `软件开发` `人工智能`

> Top Pass: Improve Code Generation by Pass@k-Maximized Code Ranking

# 摘要

> 随着大型语言模型的进步，代码生成能力得到了显著提升。然而，面对复杂问题，现有的基于 LLM 的代码生成方法往往难以在几次尝试内产出无误代码。当前的解决策略是生成大量候选程序，寄希望于其中之一能正确运行。但用户通常期望通过少量审查或测试就能找到正确代码，否则系统将失去实用性。为此，我们提出了 Top Pass 方法，该方法能从众多候选中高效识别出潜在的正确解决方案。通过优化 pass@k 损失函数，Top Pass 提升了候选列表顶部的质量，使用户能以最少尝试找到正确答案。实验显示，与现有顶尖方法相比，Top Pass 在 CodeContests 基准上实现了 32.9% 的 pass@1 相对提升，显著增强了代码生成模型的实用性。

> Code generation has been greatly enhanced by the profound advancements in Large Language Models (LLMs) recently. Nevertheless, such LLM-based code generation approaches still struggle to generate error-free code in a few tries when faced with complex problems. To address this, the prevailing strategy is to sample a huge number of candidate programs, with the hope of any one in them could work. However, users of code generation systems usually expect to find a correct program by reviewing or testing only a small number of code candidates. Otherwise, the system would be unhelpful. In this paper, we propose Top Pass, a code ranking approach that identifies potential correct solutions from a large number of candidates. Top Pass directly optimizes the pass@k loss function, enhancing the quality at the top of the candidate list. This enables the user to find the correct solution within as few tries as possible. Experimental results on four benchmarks indicate that our Top Pass method enhances the usability of code generation models by producing better ranking results, particularly achieving a 32.9\% relative improvement in pass@1 on CodeContests when compared to the state-of-the-art ranking method.

[Arxiv](https://arxiv.org/abs/2408.05715)