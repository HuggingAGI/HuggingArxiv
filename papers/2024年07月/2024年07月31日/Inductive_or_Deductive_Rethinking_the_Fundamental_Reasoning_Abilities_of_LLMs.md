# 归纳还是演绎？探讨 LLMs 的基本推理能力

发布时间：2024年07月31日

`LLM理论` `人工智能`

> Inductive or Deductive? Rethinking the Fundamental Reasoning Abilities of LLMs

# 摘要

> 推理分为演绎和归纳两大类。尽管大型语言模型（LLM）的推理研究众多，但多数研究未能清晰区分这两种推理方式，导致概念混淆。我们不禁要问：在LLM的推理世界里，演绎与归纳，哪一方更具挑战？虽然LLM的演绎能力（即遵循推理指令的能力）备受瞩目，但其真正的归纳能力却鲜为人知。为此，我们创新性地提出了SolverLearner框架，让LLM仅凭上下文示例就能掌握从输入到输出的映射函数。通过聚焦归纳推理并将其与演绎推理明确区分，SolverLearner使我们能够纯粹地探究LLM的归纳能力。实证结果令人瞩目：LLM在SolverLearner的助力下，归纳推理表现近乎完美，准确率高达1。然而，出乎意料的是，尽管归纳能力出众，LLM在处理涉及“反事实”推理的任务时，演绎能力却相对薄弱。

> Reasoning encompasses two typical types: deductive reasoning and inductive reasoning. Despite extensive research into the reasoning capabilities of Large Language Models (LLMs), most studies have failed to rigorously differentiate between inductive and deductive reasoning, leading to a blending of the two. This raises an essential question: In LLM reasoning, which poses a greater challenge - deductive or inductive reasoning? While the deductive reasoning capabilities of LLMs, (i.e. their capacity to follow instructions in reasoning tasks), have received considerable attention, their abilities in true inductive reasoning remain largely unexplored. To delve into the true inductive reasoning capabilities of LLMs, we propose a novel framework, SolverLearner. This framework enables LLMs to learn the underlying function (i.e., $y = f_w(x)$), that maps input data points $(x)$ to their corresponding output values $(y)$, using only in-context examples. By focusing on inductive reasoning and separating it from LLM-based deductive reasoning, we can isolate and investigate inductive reasoning of LLMs in its pure form via SolverLearner. Our observations reveal that LLMs demonstrate remarkable inductive reasoning capabilities through SolverLearner, achieving near-perfect performance with ACC of 1 in most cases. Surprisingly, despite their strong inductive reasoning abilities, LLMs tend to relatively lack deductive reasoning capabilities, particularly in tasks involving ``counterfactual'' reasoning.

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x1.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x2.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x3.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x4.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x5.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x6.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x7.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x8.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x9.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x10.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x11.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x12.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x13.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x14.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x15.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x16.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x17.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x18.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x19.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x20.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x21.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x22.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x23.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x24.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x25.png)

![归纳还是演绎？探讨 LLMs 的基本推理能力](../../../paper_images/2408.00114/x26.png)

[Arxiv](https://arxiv.org/abs/2408.00114)