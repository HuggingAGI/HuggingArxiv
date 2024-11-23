# AmpleGCG-Plus：一种强大的对抗性后缀生成模型，能以更少的尝试次数和更高的成功率来破解大型语言模型（LLMs）。

发布时间：2024年10月29日

`LLM应用` `模型安全`

> AmpleGCG-Plus: A Strong Generative Model of Adversarial Suffixes to Jailbreak LLMs with Higher Success Rates in Fewer Attempts

# 摘要

> 尽管大型语言模型（LLMs）通常已对齐，但仍可能因精心设计的自然语言提示，或者有趣的是，胡言乱语的对抗后缀而被破解。然而，尽管胡言乱语令牌在攻击对齐的 LLMs 时成效显著，却相对较少受到关注。近期的工作，AmpleGCG~\citep{liao2024amplegcg}表明，生成模型能够为任何有害查询迅速生成大量可定制的胡言乱语对抗后缀，暴露出分布外（OOD）语言空间中的一系列对齐差距。为引起对这一领域的更多关注，我们推出了增强版的 AmpleGCG-Plus，它在更少的尝试中取得了更优的性能。通过一系列探索性实验，我们确定了若干训练策略以改进胡言乱语后缀的学习。我们的结果在严格评估设置下得到验证，表明其在开放权重和闭源模型上均优于 AmpleGCG，在针对 Llama-2-7B-chat 的白盒设置中攻击成功率（ASR）提高多达 17％，在针对 GPT-4 的黑盒设置中 ASR 提高两倍有余。值得注意的是，AmpleGCG-Plus 破解较新的 GPT-4o 系列模型的速率与 GPT-4 相近，并揭示了针对近期提出的断路器防御的漏洞。我们公开发布了 AmpleGCG-Plus 以及我们收集的训练数据集。

> Although large language models (LLMs) are typically aligned, they remain vulnerable to jailbreaking through either carefully crafted prompts in natural language or, interestingly, gibberish adversarial suffixes. However, gibberish tokens have received relatively less attention despite their success in attacking aligned LLMs. Recent work, AmpleGCG~\citep{liao2024amplegcg}, demonstrates that a generative model can quickly produce numerous customizable gibberish adversarial suffixes for any harmful query, exposing a range of alignment gaps in out-of-distribution (OOD) language spaces. To bring more attention to this area, we introduce AmpleGCG-Plus, an enhanced version that achieves better performance in fewer attempts. Through a series of exploratory experiments, we identify several training strategies to improve the learning of gibberish suffixes. Our results, verified under a strict evaluation setting, show that it outperforms AmpleGCG on both open-weight and closed-source models, achieving increases in attack success rate (ASR) of up to 17\% in the white-box setting against Llama-2-7B-chat, and more than tripling ASR in the black-box setting against GPT-4. Notably, AmpleGCG-Plus jailbreaks the newer GPT-4o series of models at similar rates to GPT-4, and, uncovers vulnerabilities against the recently proposed circuit breakers defense. We publicly release AmpleGCG-Plus along with our collected training datasets.

[Arxiv](https://arxiv.org/abs/2410.22143)