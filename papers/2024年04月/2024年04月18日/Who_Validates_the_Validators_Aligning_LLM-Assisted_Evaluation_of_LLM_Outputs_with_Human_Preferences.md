# 谁来校验校验者？将大型语言模型（LLM）辅助的输出评估与人类偏好相协调

发布时间：2024年04月18日

`LLM应用` `人工智能` `软件工程`

> Who Validates the Validators? Aligning LLM-Assisted Evaluation of LLM Outputs with Human Preferences

# 摘要

> 鉴于人工评审的复杂性及基于代码的评审方法的局限，大型语言模型（LLMs）正日益成为辅助人类评审LLM输出的重要工具。但是，由LLM生成的评审工具往往会继承其所评审LLMs的问题，这就需要更多的人工确认。为此，我们提出了一种混合主动的方法，旨在“验证评审者”——确保由LLM生成的评审函数（无论是提示还是代码）与人类的评审标准相匹配。我们的界面EvalGen，能够自动协助用户制定评审标准并实现断言。在生成候选实现（如Python函数或LLM评分提示）的过程中，EvalGen会要求人类对LLM的部分输出进行评分，这些评分反馈将用于筛选出更符合用户标准的实现。一项定性研究总体上支持了EvalGen的有效性，但也指出了评审标准的主观性和对齐过程的迭代性。特别是，我们发现了一种现象，即“标准漂移”：用户需要依据标准来评审输出，而评审输出的过程本身又帮助用户形成了这些标准。此外，某些标准似乎与特定的LLM输出有关（而非可以预先定义的独立标准），这对于那些假设评审独立于模型输出观察的方法提出了质疑。我们详细介绍了我们的界面、实现细节，并将我们的算法与基线方法进行了比较，最后探讨了未来LLM评审助手设计的意义。

> Due to the cumbersome nature of human evaluation and limitations of code-based evaluation, Large Language Models (LLMs) are increasingly being used to assist humans in evaluating LLM outputs. Yet LLM-generated evaluators simply inherit all the problems of the LLMs they evaluate, requiring further human validation. We present a mixed-initiative approach to ``validate the validators'' -- aligning LLM-generated evaluation functions (be it prompts or code) with human requirements. Our interface, EvalGen, provides automated assistance to users in generating evaluation criteria and implementing assertions. While generating candidate implementations (Python functions, LLM grader prompts), EvalGen asks humans to grade a subset of LLM outputs; this feedback is used to select implementations that better align with user grades. A qualitative study finds overall support for EvalGen but underscores the subjectivity and iterative process of alignment. In particular, we identify a phenomenon we dub \emph{criteria drift}: users need criteria to grade outputs, but grading outputs helps users define criteria. What is more, some criteria appears \emph{dependent} on the specific LLM outputs observed (rather than independent criteria that can be defined \emph{a priori}), raising serious questions for approaches that assume the independence of evaluation from observation of model outputs. We present our interface and implementation details, a comparison of our algorithm with a baseline approach, and implications for the design of future LLM evaluation assistants.

[Arxiv](https://arxiv.org/abs/2404.12272)