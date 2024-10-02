# 通过特定风格的神经元，我们能够引导 LLM 在文本风格转换中更加精准。

发布时间：2024年10月01日

`LLM应用` `文本处理` `自然语言生成`

> Style-Specific Neurons for Steering LLMs in Text Style Transfer

# 摘要

> 文本风格转换 (TST) 旨在改变文本风格而不失原意。尽管大型语言模型 (LLM) 在多个任务中表现出色，但在零-shot 设置中，它们往往直接复制输入文本，风格变化有限。为此，我们提出了 sNeuron-TST，一种利用特定风格神经元引导 LLM 的新方法。通过识别并停用源风格神经元，我们提高了目标风格词汇的概率，增强了文本风格多样性。然而，这影响了文本流畅性，我们通过改进的对比解码方法解决了这一问题，该方法考虑了神经元停用引起的快速概率变化。实验证明，该方法在六个基准上效果显著，涵盖了正式性、毒性、政治、礼貌、作者身份和情感。

> Text style transfer (TST) aims to modify the style of a text without altering its original meaning. Large language models (LLMs) demonstrate superior performance across multiple tasks, including TST. However, in zero-shot setups, they tend to directly copy a significant portion of the input text to the output without effectively changing its style. To enhance the stylistic variety and fluency of the text, we present sNeuron-TST, a novel approach for steering LLMs using style-specific neurons in TST. Specifically, we identify neurons associated with the source and target styles and deactivate source-style-only neurons to give target-style words a higher probability, aiming to enhance the stylistic diversity of the generated text. However, we find that this deactivation negatively impacts the fluency of the generated text, which we address by proposing an improved contrastive decoding method that accounts for rapid token probability shifts across layers caused by deactivated source-style neurons. Empirical experiments demonstrate the effectiveness of the proposed method on six benchmarks, encompassing formality, toxicity, politics, politeness, authorship, and sentiment.

[Arxiv](https://arxiv.org/abs/2410.00593)