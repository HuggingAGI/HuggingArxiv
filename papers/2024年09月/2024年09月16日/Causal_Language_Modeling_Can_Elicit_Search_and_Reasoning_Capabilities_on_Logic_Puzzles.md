# 因果语言建模能够激发逻辑谜题中的搜索与推理能力

发布时间：2024年09月16日

`LLM应用`

> Causal Language Modeling Can Elicit Search and Reasoning Capabilities on Logic Puzzles

# 摘要

> 近年来，基于 Transformer 架构的因果语言建模在大型语言模型 (LLM) 中展现出卓越能力。然而，LLM 中基本搜索和推理能力的出现程度仍存争议。本研究探讨因果语言建模能否解决数独等复杂任务。为解数独，模型需先搜索所有空单元格，决定填充目标，再应用适当策略。有时策略仅缩小可能值范围而非确定确切值，需多次应用策略。实验表明，按解题逻辑步骤训练的 Transformer 模型能有效解数独（正确率 $94.21\%$）。无此训练，模型则无法掌握数独。此外，模型在 Zebra 谜题（爱因斯坦谜题）中也表现出色（正确率 $92.04\%$）。通过线性探测，我们还能从模型内部表示中解码单元格可能值信息，暗示 Transformer 权重中隐含强大推理引擎。

> Causal language modeling using the Transformer architecture has yielded remarkable capabilities in Large Language Models (LLMs) over the last few years. However, the extent to which fundamental search and reasoning capabilities emerged within LLMs remains a topic of ongoing debate. In this work, we study if causal language modeling can learn a complex task such as solving Sudoku puzzles. To solve a Sudoku, the model is first required to search over all empty cells of the puzzle to decide on a cell to fill and then apply an appropriate strategy to fill the decided cell. Sometimes, the application of a strategy only results in thinning down the possible values in a cell rather than concluding the exact value of the cell. In such cases, multiple strategies are applied one after the other to fill a single cell. We observe that Transformer models trained on this synthetic task can indeed learn to solve Sudokus (our model solves $94.21\%$ of the puzzles fully correctly) when trained on a logical sequence of steps taken by a solver. We find that training Transformers with the logical sequence of steps is necessary and without such training, they fail to learn Sudoku. We also extend our analysis to Zebra puzzles (known as Einstein puzzles) and show that the model solves $92.04 \%$ of the puzzles fully correctly. In addition, we study the internal representations of the trained Transformer and find that through linear probing, we can decode information about the set of possible values in any given cell from them, pointing to the presence of a strong reasoning engine implicit in the Transformer weights.

[Arxiv](https://arxiv.org/abs/2409.10502)