# 语言模型中的思维标记在语言模型中引入思维标记，旨在增强模型的理解和推理能力，使其在处理复杂语言任务时更加精准和高效。这些标记如同智慧的火花，在模型的计算过程中闪烁，引导其深入思考，从而提升了解决问题的能力。

发布时间：2024年05月14日

`LLM理论

这篇论文摘要讨论了大型语言模型（LLM）在处理复杂计算任务时的局限性，并提出了一种新的方法——引入“思考令牌”来增强模型的推理能力。这涉及到对LLM内部工作机制的改进，旨在提升其泛化能力和模仿人类思考过程。因此，这项研究更偏向于LLM的理论层面，探讨如何通过机制设计来改善模型的性能。` `人工智能推理`

> Thinking Tokens for Language Modeling

# 摘要

> 语言模型在面对56乘以37这样的复杂计算时往往力不从心，这源于它们缺乏复杂推理的能力。尽管它们依赖庞大的训练数据和记忆能力，但计算能力并非其所长。有趣的是，人类在面对此类计算时也需深思熟虑。鉴于此，我们提出引入“思考令牌”，使模型在遭遇难题时能进行更深入的推理，以此提升其泛化能力，并模仿人类的思考过程。

> How much is 56 times 37? Language models often make mistakes in these types of difficult calculations. This is usually explained by their inability to perform complex reasoning. Since language models rely on large training sets and great memorization capability, naturally they are not equipped to run complex calculations. However, one can argue that humans also cannot perform this calculation immediately and require a considerable amount of time to construct the solution. In order to enhance the generalization capability of language models, and as a parallel to human behavior, we propose to use special 'thinking tokens' which allow the model to perform much more calculations whenever a complex problem is encountered.

[Arxiv](https://arxiv.org/abs/2405.08644)