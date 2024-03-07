# [本研究运用 GPT-turbo 3.5 技术，自动创建适合评估英语词汇掌握程度的多选填空题。](https://arxiv.org/abs/2403.02078)

发布时间：2024年03月04日

`LLM应用`

> Automated Generation of Multiple-Choice Cloze Questions for Assessing English Vocabulary Using GPT-turbo 3.5

> 在评估语言学习者的词汇掌握程度时，人们常常借助于多项选择填空题，但设计这类题目对个体教师或大型语言教育项目来说是一项繁重的任务。本文探讨了一种运用大型语言模型(LLM)自动构建此类试题的新策略——VocaTT引擎，它以Python编写，主要包含三步流程：预处理目标词汇表、运用GPT生成句子及候选词项，并最终筛选恰当的词项选项。为了验证该系统的效果，我们针对学术词汇生成了60道题目，并邀请专家评审员对生成的句子质量、词选项适宜度进行评估，对不合格题目给予评论。实验结果显示，生成的句子中有四分之三达到了良好的结构完整性，适宜词选项的比例则达到了66.85%，相较于我们先前未充分利用GPT优势的研究使用的生成器有了显著提升。后续定性分析指出，在未来的改进方向上，应考虑引入交叉参考词性标注、强化句子有效性的校验机制以及进一步优化GPT的提示输入。

> A common way of assessing language learners' mastery of vocabulary is via multiple-choice cloze (i.e., fill-in-the-blank) questions. But the creation of test items can be laborious for individual teachers or in large-scale language programs. In this paper, we evaluate a new method for automatically generating these types of questions using large language models (LLM). The VocaTT (vocabulary teaching and training) engine is written in Python and comprises three basic steps: pre-processing target word lists, generating sentences and candidate word options using GPT, and finally selecting suitable word options. To test the efficiency of this system, 60 questions were generated targeting academic words. The generated items were reviewed by expert reviewers who judged the well-formedness of the sentences and word options, adding comments to items judged not well-formed. Results showed a 75% rate of well-formedness for sentences and 66.85% rate for suitable word options. This is a marked improvement over the generator used earlier in our research which did not take advantage of GPT's capabilities. Post-hoc qualitative analysis reveals several points for improvement in future work including cross-referencing part-of-speech tagging, better sentence validation, and improving GPT prompts.