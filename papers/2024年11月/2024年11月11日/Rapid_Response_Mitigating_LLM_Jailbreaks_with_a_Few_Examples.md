# 快速响应：以几个实例减轻 LLM 的越狱问题

发布时间：2024年11月11日

`LLM应用` `语言模型` `安全防御`

> Rapid Response: Mitigating LLM Jailbreaks with a Few Examples

# 摘要

> 随着大型语言模型（LLMs）愈发强大，保障其不被滥用的安全性变得极为关键。尽管研究人员一直致力于研发强有力的防御手段，然而至今尚无任何方法能做到完全不受攻击。我们提出了另一种思路：不追求完美的对抗稳健性，而是开发快速响应技术，在仅观察到少量攻击后，就力图阻止整类的越狱行为。为研究此情形，我们开发了 RapidResponseBench，这一基准用于衡量在适应少量观察到的实例后，防御措施针对各类越狱策略的稳健性。我们评估了五种快速响应方法，它们均采用越狱扩散，即自动生成与所观察到的实例相似的额外越狱。我们最有效的方法是微调输入分类器以阻拦扩散的越狱，在仅观察到每种越狱策略的一个示例后，在分布内的越狱集合中，攻击成功率降低超过 240 倍，在分布外的集合中降低超过 15 倍。而且，进一步的研究表明，扩散模型的质量和扩散实例的数量在这种防御的有效性方面发挥着重要作用。总之，我们的成果凸显了对新型越狱迅速响应以限制 LLM 滥用的潜力。

> As large language models (LLMs) grow more powerful, ensuring their safety against misuse becomes crucial. While researchers have focused on developing robust defenses, no method has yet achieved complete invulnerability to attacks. We propose an alternative approach: instead of seeking perfect adversarial robustness, we develop rapid response techniques to look to block whole classes of jailbreaks after observing only a handful of attacks. To study this setting, we develop RapidResponseBench, a benchmark that measures a defense's robustness against various jailbreak strategies after adapting to a few observed examples. We evaluate five rapid response methods, all of which use jailbreak proliferation, where we automatically generate additional jailbreaks similar to the examples observed. Our strongest method, which fine-tunes an input classifier to block proliferated jailbreaks, reduces attack success rate by a factor greater than 240 on an in-distribution set of jailbreaks and a factor greater than 15 on an out-of-distribution set, having observed just one example of each jailbreaking strategy. Moreover, further studies suggest that the quality of proliferation model and number of proliferated examples play an key role in the effectiveness of this defense. Overall, our results highlight the potential of responding rapidly to novel jailbreaks to limit LLM misuse.

[Arxiv](https://arxiv.org/abs/2411.07494)