# AutoTest：借助测试用例，进化选择代码解决方案

发布时间：2024年08月22日

`LLM应用` `软件开发` `自动化测试`

> AutoTest: Evolutionary Code Solution Selection with Test Cases

# 摘要

> 随着代码生成技术的进步，从众多候选方案中挑选出最佳代码解决方案变得尤为关键。本研究引入AutoTest技术，它巧妙结合自动化测试用例生成与代码执行，借助进化遗传算法精炼选择流程。AutoTest首先借助codegen-16B等大型预训练模型，提供代码方案及对应测试用例。随后，通过执行这些方案并评估其在测试用例上的表现，形成共识集。借助进化遗传算法的选择、变异与交叉机制，结合alpha和beta参数的微调，实现精准排序，最终选出最优代码方案。在HumanEval基准测试中，AutoTest表现卓越，该数据集涵盖164个编程难题，AutoTest在pass@1评分上较基线方法提升了约10%。

> With the development of code generation techniques, selecting the correct code solution from multiple candidate solutions has become a crucial task. This study proposes AutoTest, a novel technique that combines automated test case generation with code solution execution to optimize the selection process using an evolutionary genetic algorithm. Firstly, AutoTest utilizes large pre-trained language models such as codegen-16B, code-davinci-002, and incoder-6B to provide code solutions and their corresponding test cases. Then, by executing the code solutions and evaluating their performance on the test cases, a consensus set is formed. Fine-grained ranking is achieved through the selection, mutation, and crossover mechanisms based on the evolutionary genetic algorithm, with the adjustment of alpha and beta parameters. Finally, the best code solution is chosen. AutoTest demonstrates significant performance improvements on the HumanEval benchmark test. The HumanEval dataset consists of 164 programming problems, and AutoTest achieves approximately a 10% improvement over the baseline method in terms of pass@1 score.

[Arxiv](https://arxiv.org/abs/2408.12125)