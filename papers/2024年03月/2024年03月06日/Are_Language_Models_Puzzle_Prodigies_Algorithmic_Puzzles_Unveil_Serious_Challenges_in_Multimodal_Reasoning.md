# [语言模型堪称解谜高手吗？通过算法谜题，我们发现它们在解决多模态推理问题时面临重大挑战。](https://arxiv.org/abs/2403.03864)

发布时间：2024年03月06日

`LLM应用`

> Are Language Models Puzzle Prodigies? Algorithmic Puzzles Unveil Serious Challenges in Multimodal Reasoning

> 本篇论文创新性地将多模态解谜任务融入视觉问答情境，并推出全新数据集 AlgoPuzzleVQA，旨在测试多模态语言模型在解决涵盖布尔逻辑、组合学、图论、优化、搜索等多元数学及算法主题的难题时，所需具备的视觉理解、语言理解和高级算法推理能力。这个谜题数据集源自自动转化的人类编写代码，确保每个谜题均有精确答案，无需人工繁琐运算，从而实现推理难度和数据集规模的无限扩展。然而，研究揭示像GPT4V和Gemini这样的大型语言模型在解谜任务上的表现颇为受限，尤其在大量谜题的多选问答环境中，其性能几乎等同于随机选择。这一发现突显了在解决复杂的推理问题时，如何有效融合视觉、语言与算法知识所面临的艰巨挑战。

> This paper introduces the novel task of multimodal puzzle solving, framed within the context of visual question-answering. We present a new dataset, AlgoPuzzleVQA designed to challenge and evaluate the capabilities of multimodal language models in solving algorithmic puzzles that necessitate both visual understanding, language understanding, and complex algorithmic reasoning. We create the puzzles to encompass a diverse array of mathematical and algorithmic topics such as boolean logic, combinatorics, graph theory, optimization, search, etc., aiming to evaluate the gap between visual data interpretation and algorithmic problem-solving skills. The dataset is generated automatically from code authored by humans. All our puzzles have exact solutions that can be found from the algorithm without tedious human calculations. It ensures that our dataset can be scaled up arbitrarily in terms of reasoning complexity and dataset size. Our investigation reveals that large language models (LLMs) such as GPT4V and Gemini exhibit limited performance in puzzle-solving tasks. We find that their performance is near random in a multi-choice question-answering setup for a significant number of puzzles. The findings emphasize the challenges of integrating visual, language, and algorithmic knowledge for solving complex reasoning problems.