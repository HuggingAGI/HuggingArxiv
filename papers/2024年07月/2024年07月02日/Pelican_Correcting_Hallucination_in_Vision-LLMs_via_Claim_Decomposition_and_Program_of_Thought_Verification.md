# Pelican 通过声明分解和思维程序验证，有效纠正了视觉-LLMs中的幻觉问题。

发布时间：2024年07月02日

`LLM应用` `计算机视觉` `人工智能`

> Pelican: Correcting Hallucination in Vision-LLMs via Claim Decomposition and Program of Thought Verification

# 摘要

> 大型视觉语言模型 (LVLMs) 在处理视觉指令任务时易产生幻觉，影响了其可靠性和实际应用。为此，我们设计了 Pelican 框架，通过声明验证来识别并减少幻觉。Pelican 先将视觉声明拆解为一系列基于一阶谓词的子声明，这些子声明如同计算图的节点，由 (谓词, 问题) 对构成。接着，我们运用 Program-of-Thought 提示技术，生成灵活组合外部工具的 Python 代码来解答这些问题。Pelican 的创新之处在于：(1) 引入中间变量精确锁定对象实例，(2) 共享计算资源以应对子问题，从而进行自适应调整和识别不一致性。最终，我们借助 LLM 的推理能力，通过分析每个子声明中 (问题, 答案) 对的一致性和置信度来验证声明的准确性。实验表明，Pelican 在多个基准测试中将幻觉率降低了 8%-32%，相较于 MMHal-Bench 上的幻觉缓解方法，效果提升了 27%。其他两个基准测试的结果也支持了我们的结论。

> Large Visual Language Models (LVLMs) struggle with hallucinations in visual instruction following task(s), limiting their trustworthiness and real-world applicability. We propose Pelican -- a novel framework designed to detect and mitigate hallucinations through claim verification. Pelican first decomposes the visual claim into a chain of sub-claims based on first-order predicates. These sub-claims consist of (predicate, question) pairs and can be conceptualized as nodes of a computational graph. We then use Program-of-Thought prompting to generate Python code for answering these questions through flexible composition of external tools. Pelican improves over prior work by introducing (1) intermediate variables for precise grounding of object instances, and (2) shared computation for answering the sub-question to enable adaptive corrections and inconsistency identification. We finally use reasoning abilities of LLM to verify the correctness of the the claim by considering the consistency and confidence of the (question, answer) pairs from each sub-claim. Our experiments reveal a drop in hallucination rate by $\sim$8%-32% across various baseline LVLMs and a 27% drop compared to approaches proposed for hallucination mitigation on MMHal-Bench. Results on two other benchmarks further corroborate our results.

[Arxiv](https://arxiv.org/abs/2407.02352)