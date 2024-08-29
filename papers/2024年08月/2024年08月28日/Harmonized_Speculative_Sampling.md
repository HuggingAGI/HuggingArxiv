# 和谐推测采样

发布时间：2024年08月28日

`LLM理论` `人工智能` `计算机科学`

> Harmonized Speculative Sampling

# 摘要

> 推测采样是加速大型语言模型解码的有效手段，其性能关键在于接受率。以往研究多聚焦于训练与解码的优化，却忽视了两者间的内在联系。本研究首先探讨了这一联系，并提出了HArmonized Speculative Sampling（HASS）方案，通过统一训练与解码的目标与上下文，提升接受率且不增加推理负担。实验显示，HASS在三个LLaMA模型上实现了2.81x至3.65x的加速，比EAGLE-2快8%至15%。

> Speculative sampling has proven to be an effective solution to accelerate decoding from large language models, where the acceptance rate significantly determines the performance. Most previous works on improving the acceptance rate focus on aligned training and efficient decoding, implicitly paying less attention to the linkage of training and decoding. In this work, we first investigate the linkage of training and decoding for speculative sampling and then propose a solution named HArmonized Speculative Sampling (HASS). HASS improves the acceptance rate without extra inference overhead by harmonizing training and decoding on their objectives and contexts. Experiments on three LLaMA models demonstrate that HASS achieves 2.81x-3.65x wall-clock time speedup ratio averaging across three datasets, which is 8%-15% faster than EAGLE-2.

[Arxiv](https://arxiv.org/abs/2408.15766)