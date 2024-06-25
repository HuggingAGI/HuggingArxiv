# 合成提示法：助力大型语言模型，生成思维链式演示

发布时间：2023年02月01日

`Agent

理由：该论文提出了一种名为“合成提示”的新方法，旨在通过模型自主生成高质量示例来提升推理效果。这种方法涉及到模型的自主行为，即模型能够根据少数精心设计的示例自主生成更多示例，并从中挑选出最有效的演示。这种自主生成和选择行为符合Agent的定义，即一个能够感知环境并采取行动以达到目标的系统。因此，这篇论文更符合Agent分类。` `人工智能` `推理任务`

> Synthetic Prompting: Generating Chain-of-Thought Demonstrations for Large Language Models

# 摘要

> 大型语言模型借助链式思维提示，能够通过逐步演示解决多种推理任务。但提示的质量受限于所提供的演示，手工制作大量演示既费时又费力。为此，我们提出了一种名为“合成提示”的新方法，它利用少数精心设计的示例，激发模型自主生成更多高质量示例，并从中挑选出最有效的演示以提升推理效果。我们的方法通过交替进行“后向”与“前向”两个过程来创造新示例：后向过程确保问题与推理链相匹配，使之既可解又清晰；前向过程则进一步细化推理链，增强示例的深度。经过在数值、符号及算法推理任务上的测试，我们的方法展现出了超越现有技术的优越性能。

> Large language models can perform various reasoning tasks by using chain-of-thought prompting, which guides them to find answers through step-by-step demonstrations. However, the quality of the prompts depends on the demonstrations given to the models, and creating many of them by hand is costly. We introduce Synthetic prompting, a method that leverages a few handcrafted examples to prompt the model to generate more examples by itself, and selects effective demonstrations to elicit better reasoning. Our method alternates between a backward and forward process to generate new examples. The backward process generates a question that match a sampled reasoning chain, so that the question is solvable and clear. The forward process produces a more detailed reasoning chain for the question, improving the quality of the example. We evaluate our method on numerical, symbolic, and algorithmic reasoning tasks, and show that it outperforms existing prompting techniques.

[Arxiv](https://arxiv.org/abs/2302.00618)