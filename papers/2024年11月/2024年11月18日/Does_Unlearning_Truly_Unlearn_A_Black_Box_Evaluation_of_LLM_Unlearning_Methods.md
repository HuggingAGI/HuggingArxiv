# 《遗忘是否真能遗忘？对 LLM 遗忘方法的黑箱式评估》

发布时间：2024年11月18日

`LLM应用` `语言模型` `数据安全`

> Does Unlearning Truly Unlearn? A Black Box Evaluation of LLM Unlearning Methods

# 摘要

> 大型语言模型的遗忘旨在消除其已习得的有害信息，以防被用于不良目的。LLMU 和 RMU 作为大型语言模型遗忘的两种方法已被提出，在遗忘基准测试中成绩斐然。我们通过评估它们对 WMDP 基准以及我们创建的生物学基准上的一般模型能力的影响，深入探究了这些方法的成效。实验显示，在遗忘效果相近或更优的情况下，RMU 通常能更好地保留模型能力。我们进一步测试了这些方法的稳定性，发现进行 5 次提示或简单改写问题，能让遗忘基准测试的准确率提升十倍有余。最后，我们指出在不相关数据上训练几乎能完全恢复遗忘前的性能，这表明这些方法并未真正达成遗忘。代码可在 $\href{https://github.com/JaiDoshi/Knowledge-Erasure}{此 https 网址}$ 获取。

> Large language model unlearning aims to remove harmful information that LLMs have learnt to prevent their use for malicious purposes. LLMU and RMU have been proposed as two methods for LLM unlearning, achieving impressive results on unlearning benchmarks. We study in detail the efficacy of these methods by evaluating their impact on general model capabilities on the WMDP benchmark as well as a biology benchmark we create. Our experiments show that RMU generally leads to better preservation of model capabilities, for similar or better unlearning. We further test the robustness of these methods and find that doing 5-shot prompting or rephrasing the question in simple ways can lead to an over ten-fold increase in accuracy on unlearning benchmarks. Finally, we show that training on unrelated data can almost completely recover pre-unlearning performance, demonstrating that these methods fail at truly unlearning. The code is available at $\href{https://github.com/JaiDoshi/Knowledge-Erasure}{this\, https\, URL}$.

[Arxiv](https://arxiv.org/abs/2411.12103)