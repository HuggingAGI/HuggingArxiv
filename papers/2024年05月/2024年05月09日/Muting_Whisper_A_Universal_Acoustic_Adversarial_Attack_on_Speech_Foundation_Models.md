# 《沉默之声：对语音基础模型发起的通用声学对抗攻击》

发布时间：2024年05月09日

`Agent

解释：这篇论文讨论了针对大型语音基础模型（如Whisper）的对抗性攻击，特别是通过创造一个通用的声学实现来影响模型的行为，使其忽略语音内容。这种攻击可以被视为一种智能Agent的行为，因为它涉及到对模型的操纵和利用。此外，论文还探讨了这种攻击在现实世界中的潜在风险和机遇，这与Agent的行为和影响相符。因此，这篇论文更适合归类为Agent，而不是RAG、LLM应用或LLM理论。` `自动语音识别` `隐私保护`

> Muting Whisper: A Universal Acoustic Adversarial Attack on Speech Foundation Models

# 摘要

> Whisper等大型语音基础模型的最新进展，使其在自动语音识别应用中大放异彩。这些模型通过引入特殊标记，如$\texttt{<endoftext>}$，来优化语言生成。然而，我们发现这些标记可能成为对抗性攻击的工具，影响模型的行为。我们提出了一种巧妙的方法，能够为Whisper的$\texttt{<endoftext>}$标记创造一个通用的声学实现，一旦它被前置于任何语音信号，模型便会忽略语音内容，仅转录该特殊标记，从而“静音”模型。实验证明，一段仅0.64秒的通用对抗音频，能让目标Whisper ASR模型对97%以上的语音样本失效。更令人惊讶的是，这段音频还能在不同数据集和任务间迁移。这项研究揭示了Whisper模型在面对“静音”攻击时的脆弱性，这种攻击在现实世界中既可能带来风险，也可能带来保护隐私语音数据的新机遇。

> Recent developments in large speech foundation models like Whisper have led to their widespread use in many automatic speech recognition (ASR) applications. These systems incorporate `special tokens' in their vocabulary, such as $\texttt{<endoftext>}$, to guide their language generation process. However, we demonstrate that these tokens can be exploited by adversarial attacks to manipulate the model's behavior. We propose a simple yet effective method to learn a universal acoustic realization of Whisper's $\texttt{<endoftext>}$ token, which, when prepended to any speech signal, encourages the model to ignore the speech and only transcribe the special token, effectively `muting' the model. Our experiments demonstrate that the same, universal 0.64-second adversarial audio segment can successfully mute a target Whisper ASR model for over 97\% of speech samples. Moreover, we find that this universal adversarial audio segment often transfers to new datasets and tasks. Overall this work demonstrates the vulnerability of Whisper models to `muting' adversarial attacks, where such attacks can pose both risks and potential benefits in real-world settings: for example the attack can be used to bypass speech moderation systems, or conversely the attack can also be used to protect private speech data.

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/attack.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/medium_spect_e0.02.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/ablation_T.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/ablation_e.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/success_saliency.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/unsuccess_saliency.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/tiny_spect_e0.02.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/tiny-multi_spect_e0.02.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/base_spect_e0.02.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/base-multi_spect_e0.02.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/small_spect_e0.02.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/small-multi_spect_e0.02.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/medium_spect_e0.02.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/medium-multi_spect_e0.02.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/tiny_spect_e0.02.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/tiny_spect_e0.01.png)

![《沉默之声：对语音基础模型发起的通用声学对抗攻击》](../../../paper_images/2405.06134/tiny_spect_e0.005.png)

[Arxiv](https://arxiv.org/abs/2405.06134)