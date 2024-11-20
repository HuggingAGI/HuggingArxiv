# 大型语言模型在技术 MRI 问题回答方面的性能：一项对比研究

发布时间：2024年11月19日

`LLM应用` `MRI 技术`

> Performance of Large Language Models in Technical MRI Question Answering: A Comparative Study

# 摘要

> 背景：人工智能的进步，尤其是大型语言模型（LLMs），不论操作者的技能高低和所处地域，都有望增强磁共振成像（MRI）的技术专长。
  方法：我们对几个大型语言模型回答源自标准化复习书的 570 个 MRI 技术问题的准确性进行了评估。这些问题涵盖九个 MRI 主题，包括基本原理、图像生成和安全等。测试了闭源模型（如 OpenAI 的 o1 Preview、GPT-4o、GPT-4 Turbo 和 Claude 3.5 Haiku）和开源模型（如 Phi 3.5 Mini、Llama 3.1、smolLM2）。通过 LangChain 框架使用标准化提示来查询模型，并依据正确答案使用自动评分协议对回答进行评分。准确性，即正确答案的比例，是主要的评估结果。
  结果：闭源的 o1 Preview 模型准确率最高（94%），远超随机猜测的基线（26.5%）。GPT-4o 和 o1 Mini 的准确率为 88%，GPT-4 Turbo 和 Claude 3.5 Haiku 均为 84%。在开源模型中，Phi 3.5 Mini 表现良好，准确率达 78%，与部分闭源模型相当。在基本原理和仪器类别中的准确率较高，而在图像加权和对比度、历史以及伪影和校正方面的准确率较低。
  结论：大型语言模型在处理 MRI 技术问题时准确率颇高，这表明它们有可能使 MRI 实践标准化并得以提升。这些模型或许能在不同临床环境中提高图像质量和一致性。还需要进一步研究来优化大型语言模型以用于临床，并将其融入 MRI 工作流程。

> Background: Advances in artificial intelligence, particularly large language models (LLMs), have the potential to enhance technical expertise in magnetic resonance imaging (MRI), regardless of operator skill or geographic location.
  Methods: We assessed the accuracy of several LLMs in answering 570 technical MRI questions derived from a standardized review book. The questions spanned nine MRI topics, including Basic Principles, Image Production, and Safety. Closed-source models (e.g., OpenAI's o1 Preview, GPT-4o, GPT-4 Turbo, and Claude 3.5 Haiku) and open-source models (e.g., Phi 3.5 Mini, Llama 3.1, smolLM2) were tested. Models were queried using standardized prompts via the LangChain framework, and responses were graded against correct answers using an automated scoring protocol. Accuracy, defined as the proportion of correct answers, was the primary outcome.
  Results: The closed-source o1 Preview model achieved the highest accuracy (94%), exceeding the random-guess baseline (26.5%). GPT-4o and o1 Mini scored 88%, and GPT-4 Turbo and Claude 3.5 Haiku each scored 84%. Among open-source models, Phi 3.5 Mini performed well, achieving 78% accuracy, comparable to several closed-source models. Accuracy was highest in Basic Principles and Instrumentation categories but lower in Image Weighting and Contrast, History, and Artifacts and Corrections.
  Conclusions: LLMs exhibit high accuracy in addressing technical MRI questions, suggesting their potential to standardize and enhance MRI practice. These models may improve image quality and consistency across varied clinical environments. Further studies are needed to refine LLMs for clinical use and integrate them into MRI workflows.

[Arxiv](https://arxiv.org/abs/2411.12238)