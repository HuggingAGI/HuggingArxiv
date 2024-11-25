# 调解思维的模式：用于设计脚本的 LLM

发布时间：2024年11月19日

`LLM应用`

> Mediating Modes of Thought: LLM's for design scripting

# 摘要

> 以下是为您更新的摘要版本，已做清理以便提交给 arXiv，还纠正了可能存在的“不良字符”，以符合 ASCII 标准：
  建筑师运用视觉脚本和参数化设计工具，去探索更广阔的设计空间（科茨，2010），优化他们对于设计几何逻辑的思考（伍德伯里，2010），并突破传统软件的限制（伯里，2011）。尽管为了让设计脚本更易获取已努力了二十年，但设计师自由的思维方式和算法的僵化之间仍存在脱节（伯里，2011）。大型语言模型（LLM）的最新进展表明这种状况可能很快会改变，因为 LLM 对人类背景有一般性的理解，还具备生成几何逻辑的能力。本项目推测，如果 LLM 能在用户意图和算法之间有效调解，它们将成为让设计中的脚本编写更普及和有趣的有力工具。我们探究这样的系统能否解读自然语言提示，从而组装与计算设计脚本相关的几何操作。在该系统中，配置了具有特定上下文的多层 LLM 代理，以推断用户意图并构建顺序逻辑。给定用户的高级文本提示，创建几何描述，提炼成一系列逻辑操作，并映射到特定软件的命令。完成的脚本在用户的可视化编程界面中构建。该系统能成功生成一定复杂程度以内的完整可视化脚本，但超过这个复杂程度阈值就会失败。它展示了 LLM 如何让设计脚本更贴合人类的创造力和思维。未来的研究应当探索对话式交互，拓展到多模态的输入和输出，并评估这些工具的性能。

> Here is an updated version of your abstract, cleaned for submission to arXiv with potential "bad characters" corrected to conform to ASCII standards:
  Architects adopt visual scripting and parametric design tools to explore more expansive design spaces (Coates, 2010), refine their thinking about the geometric logic of their design (Woodbury, 2010), and overcome conventional software limitations (Burry, 2011). Despite two decades of effort to make design scripting more accessible, a disconnect between a designer's free ways of thinking and the rigidity of algorithms remains (Burry, 2011). Recent developments in Large Language Models (LLMs) suggest this might soon change, as LLMs encode a general understanding of human context and exhibit the capacity to produce geometric logic. This project speculates that if LLMs can effectively mediate between user intent and algorithms, they become a powerful tool to make scripting in design more widespread and fun. We explore if such systems can interpret natural language prompts to assemble geometric operations relevant to computational design scripting. In the system, multiple layers of LLM agents are configured with specific context to infer the user intent and construct a sequential logic. Given a user's high-level text prompt, a geometric description is created, distilled into a sequence of logic operations, and mapped to software-specific commands. The completed script is constructed in the user's visual programming interface. The system succeeds in generating complete visual scripts up to a certain complexity but fails beyond this complexity threshold. It shows how LLMs can make design scripting much more aligned with human creativity and thought. Future research should explore conversational interactions, expand to multimodal inputs and outputs, and assess the performance of these tools.

[Arxiv](https://arxiv.org/abs/2411.14485)