# [面向程序合成器的生成性解释技术](https://arxiv.org/abs/2403.03429)

发布时间：2024年03月05日

`LLM应用`

> Generative Explanations for Program Synthesizers

> 虽然程序合成技术日新月异，其内部机制仍如黑箱般神秘。即便合成成功能确保实现符合规格要求，但对于其实现原理及规格具体如何实现，却鲜有深入见解。为解决这一问题，有人提出使用大型语言模型（LLMs）来生成易于理解的解释说明，然而遗憾的是，当LLMs处理由程序合成器产出的非惯用代码时，往往会产生难以理解甚至误导性的解释。本文提出了一项创新方法，即通过添加详尽的解释性名称来增强实现代码的可读性。我们精细提取合成算法的输入输出数据，以此丰富提交给LLM的提示内容，并采用程序验证器与另一款语言模型相结合的方式，在展示给用户前对提出的解释进行严格验证。最终，这项技术显著提升了提出的名称准确率，从24%跃升至79%。通过两组小型用户调研，我们发现用户明显更倾向于接受我们技术提供的解释（76%的反馈认为给出的名称贴切适宜），远超于对照组（仅2%的反馈认同对照组的建议），而且这些精心设计的名称确实有效帮助用户理解合成出的代码实现。

> Despite great advances in program synthesis techniques, they remain algorithmic black boxes. Although they guarantee that when synthesis is successful, the implementation satisfies the specification, they provide no additional information regarding how the implementation works or the manner in which the specification is realized. One possibility to answer these questions is to use large language models (LLMs) to construct human-readable explanations. Unfortunately, experiments reveal that LLMs frequently produce nonsensical or misleading explanations when applied to the unidiomatic code produced by program synthesizers.
  In this paper, we develop an approach to reliably augment the implementation with explanatory names. We recover fine-grained input-output data from the synthesis algorithm to enhance the prompt supplied to the LLM, and use a combination of a program verifier and a second language model to validate the proposed explanations before presenting them to the user. Together, these techniques massively improve the accuracy of the proposed names, from 24% to 79% respectively. Through a pair of small user studies, we find that users significantly prefer the explanations produced by our technique (76% of responses indicating the appropriateness of the presenting names) to the baseline (with only 2% of responses approving of the suggestions), and that the proposed names measurably help users in understanding the synthesized implementation.