# 分割翻译法：组合一阶逻辑在复杂推理中的翻译与验证

发布时间：2024年10月10日

`论文摘要：复杂的逻辑推理任务需要长序列的推理，即使使用链式思维提示的 LLM 也难以胜任。为此，神经符号方法引入了符号求解器，LLM 将自然语言问题转换为 SAT 问题，由符号求解器提供数学上正确的解决方案。然而，LLM 在处理这些任务时仍然面临挑战，特别是在处理复杂逻辑和不确定性时。为了解决这些问题，我们提出了一种新的方法，结合了 LLM 和符号求解器的优势，通过引入一种新的推理框架，该框架能够在处理复杂逻辑问题时提供更高的准确性和效率。我们的方法不仅提高了 LLM 在逻辑推理任务中的表现，还展示了在实际应用中的潜力，特别是在需要高度精确和复杂推理的领域。

LLM应用` `人工智能`

> Divide and Translate: Compositional First-Order Logic Translation and Verification for Complex Logical Reasoning

# 摘要

> 复杂的逻辑推理任务需要长序列的推理，即使使用链式思维提示的 LLM 也难以胜任。为此，神经符号方法引入了符号求解器，LLM 将自然语言问题转换为 SAT 问题，由符号求解器提供数学上正确的解决方案。然而，LLM

> Complex logical reasoning tasks require a long sequence of reasoning, which a large language model (LLM) with chain-of-thought prompting still falls short. To alleviate this issue, neurosymbolic approaches incorporate a symbolic solver. Specifically, an LLM only translates a natural language problem into a satisfiability (SAT) problem that consists of first-order logic formulas, and a sound symbolic solver returns a mathematically correct solution. However, we discover that LLMs have difficulties to capture complex logical semantics hidden in the natural language during translation. To resolve this limitation, we propose a Compositional First-Order Logic Translation. An LLM first parses a natural language sentence into newly defined logical dependency structures that consist of an atomic subsentence and its dependents, then sequentially translate the parsed subsentences. Since multiple logical dependency structures and sequential translations are possible for a single sentence, we also introduce two Verification algorithms to ensure more reliable results. We utilize an SAT solver to rigorously compare semantics of generated first-order logic formulas and select the most probable one. We evaluate the proposed method, dubbed CLOVER, on seven logical reasoning benchmarks and show that it outperforms the previous neurosymbolic approaches and achieves new state-of-the-art results.

[Arxiv](https://arxiv.org/abs/2410.08047)