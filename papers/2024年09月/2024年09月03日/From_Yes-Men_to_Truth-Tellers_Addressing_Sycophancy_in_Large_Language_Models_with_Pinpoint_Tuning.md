# 从迎合者到直言者：通过精准调校，解决大型语言模型中的谄媚现象

发布时间：2024年09月03日

`LLM理论` `人工智能` `语言模型`

> From Yes-Men to Truth-Tellers: Addressing Sycophancy in Large Language Models with Pinpoint Tuning

# 摘要

> 大型语言模型 (LLM) 往往更倾向于遵循用户指令而非提供准确答案，这种现象被称为“谄媚”。面对用户质疑时，即使最初答案正确，LLM 也会承认错误并给出不准确回应。为解决这一问题，我们提出了监督精准调优 (SPT)，仅对关键模块进行微调，以保持 LLM 的通用能力。实验表明，SPT 不仅有效缓解了谄媚问题，且对 LLM 的通用能力影响甚微。这一方法为精确提升 LLM 的特定能力提供了新思路。

> Large Language Models (LLMs) tend to prioritize adherence to user prompts over providing veracious responses, leading to the sycophancy issue. When challenged by users, LLMs tend to admit mistakes and provide inaccurate responses even if they initially provided the correct answer. Recent works propose to employ supervised fine-tuning (SFT) to mitigate the sycophancy issue, while it typically leads to the degeneration of LLMs' general capability. To address the challenge, we propose a novel supervised pinpoint tuning (SPT), where the region-of-interest modules are tuned for a given objective. Specifically, SPT first reveals and verifies a small percentage (<5%) of the basic modules, which significantly affect a particular behavior of LLMs. i.e., sycophancy. Subsequently, SPT merely fine-tunes these identified modules while freezing the rest. To verify the effectiveness of the proposed SPT, we conduct comprehensive experiments, demonstrating that SPT significantly mitigates the sycophancy issue of LLMs (even better than SFT). Moreover, SPT introduces limited or even no side effects on the general capability of LLMs. Our results shed light on how to precisely, effectively, and efficiently explain and improve the targeted ability of LLMs.

[Arxiv](https://arxiv.org/abs/2409.01658)