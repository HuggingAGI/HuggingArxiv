# [GSM-Plus 是一套全面的评测基准，旨在深入检验大型语言模型在解决数学问题时的鲁棒性表现。](https://arxiv.org/abs/2402.19255)

发布时间：2024年02月29日

`LLM应用`

> GSM-Plus: A Comprehensive Benchmark for Evaluating the Robustness of LLMs as Mathematical Problem Solvers

> LLMs在各数学推理基准上屡创佳绩，但也引发了争议——它们究竟是真正理解和应用数学知识，还是仅仅依赖数学推理的“小聪明”。一个有力的例证是，对数学问题稍作调整，LLMs就可能做出错误判断。为此，我们设计了一系列数学问题变体，用以检验LLMs数学推理能力的稳健性，并推出了扩充版的对抗性小学数学(\datasetname)数据集，在GSM8K基础上增加了多样化的数学扰动。实验证明，尽管不同LLMs的数学推理能力层次不齐，但总体而言其表现并不稳健。即使是已在GSM8K中解答过的问题，只要添加新信息或变换问题焦点，LLMs仍可能出现差错。此外，我们还研究了如何通过融合现有提示技术提高LLMs的稳健性，尝试了一种创新的方法——基于推理目标与计算结果逐步生成和验证每一个中间思考过程。相关代码和数据可在\url{https://github.com/qtli/GSM-Plus}获取。

> Large language models (LLMs) have achieved impressive performance across various mathematical reasoning benchmarks. However, there are increasing debates regarding whether these models truly understand and apply mathematical knowledge or merely rely on shortcuts for mathematical reasoning. One essential and frequently occurring evidence is that when the math questions are slightly changed, LLMs can behave incorrectly. This motivates us to evaluate the robustness of LLMs' math reasoning capability by testing a wide range of question variations. We introduce the adversarial grade school math (\datasetname) dataset, an extension of GSM8K augmented with various mathematical perturbations. Our experiments on 25 LLMs and 4 prompting techniques show that while LLMs exhibit different levels of math reasoning abilities, their performances are far from robust. In particular, even for problems that have been solved in GSM8K, LLMs can make mistakes when new statements are added or the question targets are altered. We also explore whether more robust performance can be achieved by composing existing prompting methods, in which we try an iterative method that generates and verifies each intermediate thought based on its reasoning goal and calculation result. Code and data are available at \url{https://github.com/qtli/GSM-Plus}.

[Arxiv](https://arxiv.org/abs/2402.19255)