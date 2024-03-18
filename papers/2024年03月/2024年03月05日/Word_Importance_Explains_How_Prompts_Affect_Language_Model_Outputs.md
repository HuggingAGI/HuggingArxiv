# [探究词语权重：揭示提示如何驱动语言模型的输出变化](https://arxiv.org/abs/2403.03028)

发布时间：2024年03月05日

`LLM应用`

> Word Importance Explains How Prompts Affect Language Model Outputs

> 随着LLMs横扫各行各业，其“黑箱”特性带来的决策过程不透明问题，引起了对模型透明度、可靠性和伦理应用的高度关注。本研究创新性地引入一种方法，通过调整提示语中的单个词汇，揭示这些词汇对模型输出的统计学影响，从而提升LLMs的可解释性。这一灵感来源于表格数据领域中置换重要性的思想，即逐个遮蔽系统提示中的单词，并根据多组用户输入综合计算出的文本评分变化，来量化各单词的影响效果。相较于经典的注意力机制，这种方法侧重于分析提示词对各类自定义文本评分（如偏见、阅读难度、冗余度等）的具体贡献。即便在无法获得注意力权重时，此方法也能有效评估单词的影响力度。为了验证该方法的准确性，我们尝试在多种系统提示后添加不同后缀，并对比运用不同大型语言模型生成的后续文本。实验结果显示，单词重要性得分与多种评分函数所预期的后缀重要性之间存在着紧密关联。

> The emergence of large language models (LLMs) has revolutionized numerous applications across industries. However, their "black box" nature often hinders the understanding of how they make specific decisions, raising concerns about their transparency, reliability, and ethical use. This study presents a method to improve the explainability of LLMs by varying individual words in prompts to uncover their statistical impact on the model outputs. This approach, inspired by permutation importance for tabular data, masks each word in the system prompt and evaluates its effect on the outputs based on the available text scores aggregated over multiple user inputs. Unlike classical attention, word importance measures the impact of prompt words on arbitrarily-defined text scores, which enables decomposing the importance of words into the specific measures of interest--including bias, reading level, verbosity, etc. This procedure also enables measuring impact when attention weights are not available. To test the fidelity of this approach, we explore the effect of adding different suffixes to multiple different system prompts and comparing subsequent generations with different large language models. Results show that word importance scores are closely related to the expected suffix importances for multiple scoring functions.

[Arxiv](https://arxiv.org/abs/2403.03028)