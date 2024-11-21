# 语言模型在有噪声原理的思维链提示下能否进行可靠的推理？

发布时间：2024年10月31日

`LLM应用` `人工智能`

> Can Language Models Perform Robust Reasoning in Chain-of-thought Prompting with Noisy Rationales?

# 摘要

> 这篇论文深入探究了大型语言模型（LLMs）中一个尚未被充分挖掘的难题：带有噪声原理的思维链提示，即用于上下文学习的示例中存在不相关或不准确的推理思路。我们精心构建了 NoRa 数据集，旨在评估面对噪声原理时推理的稳健性。我们在 NoRa 数据集上的研究成果表明，当前的 LLMs 普遍容易受到此类噪声的影响，现有的诸如自我纠正和自我一致性等稳健方法效果有限。特别要指出的是，与使用干净原理的提示相比，基础 LLM 在面对不相关思路时准确率下降 1.4%-19.8%，在面对不准确思路时下降幅度更大，为 2.2%-40.4%。
  要应对这一挑战，需要在实践中能够获取的外部监督。在此，我们提出了带有噪声思维链的对比去噪（CD-CoT）方法。它通过将噪声原理与仅一个干净原理进行对比，增强 LLMs 的去噪推理能力，这可以作为去噪提示的最低要求。该方法遵循探索与利用的原则：（1）在输入空间中重新表述和选择原理，以实现明确的去噪；（2）在输出空间中探索多样的推理路径并对答案进行投票。从实践来看，CD-CoT 比基础模型的准确率平均提升了 17.8%，并且展现出比基线方法更强大的去噪能力。源代码在以下网址公开：https://github.com/tmlr-group/NoisyRationales。

> This paper investigates an under-explored challenge in large language models (LLMs): chain-of-thought prompting with noisy rationales, which include irrelevant or inaccurate reasoning thoughts within examples used for in-context learning. We construct NoRa dataset that is tailored to evaluate the robustness of reasoning in the presence of noisy rationales. Our findings on NoRa dataset reveal a prevalent vulnerability to such noise among current LLMs, with existing robust methods like self-correction and self-consistency showing limited efficacy. Notably, compared to prompting with clean rationales, base LLM drops by 1.4%-19.8% in accuracy with irrelevant thoughts and more drastically by 2.2%-40.4% with inaccurate thoughts.
  Addressing this challenge necessitates external supervision that should be accessible in practice. Here, we propose the method of contrastive denoising with noisy chain-of-thought (CD-CoT). It enhances LLMs' denoising-reasoning capabilities by contrasting noisy rationales with only one clean rationale, which can be the minimal requirement for denoising-purpose prompting. This method follows a principle of exploration and exploitation: (1) rephrasing and selecting rationales in the input space to achieve explicit denoising and (2) exploring diverse reasoning paths and voting on answers in the output space. Empirically, CD-CoT demonstrates an average improvement of 17.8% in accuracy over the base model and shows significantly stronger denoising capabilities than baseline methods. The source code is publicly available at: https://github.com/tmlr-group/NoisyRationales.

[Arxiv](https://arxiv.org/abs/2410.23856)