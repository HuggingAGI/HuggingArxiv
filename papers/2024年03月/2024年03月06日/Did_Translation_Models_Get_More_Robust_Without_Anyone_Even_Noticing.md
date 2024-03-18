# [翻译模型是否悄无声息地增强了稳健性？]

发布时间：2024年03月06日

`LLM应用`

> Did Translation Models Get More Robust Without Anyone Even Noticing?

> 尽管神经机器翻译（MT）模型在各类场景下表现出色，但人们通常认为它们对拼写错误、缩略语等“噪音”输入很敏感。近期，我们以最新多语言MT模型及应用于机器翻译的大规模语言模型（LLMs）为背景，重新探讨了这一现象。出人意料的是，通过精心设计的实验，我们揭示了这些新模型在处理众多噪声类型时，相较于旧模型展现出了更高的鲁棒性，即使它们在无噪声数据上的性能相当。值得注意的是，尽管LLMs参数量更大且训练过程更为复杂，但所研究的公开模型并未特意采用增强鲁棒性的技术。进一步地，我们在社交媒体文本翻译实验中也观察到类似的趋势，即LLMs在应对社交媒体文本噪声方面表现得更为稳健。此外，我们还深入分析了在何种情况下运用源文本纠错技术能够有效缓解噪声的影响。综上所述，现今模型对多种噪声的抵御能力已有显著增强。

> Neural machine translation (MT) models achieve strong results across a variety of settings, but it is widely believed that they are highly sensitive to "noisy" inputs, such as spelling errors, abbreviations, and other formatting issues. In this paper, we revisit this insight in light of recent multilingual MT models and large language models (LLMs) applied to machine translation. Somewhat surprisingly, we show through controlled experiments that these models are far more robust to many kinds of noise than previous models, even when they perform similarly on clean data. This is notable because, even though LLMs have more parameters and more complex training processes than past models, none of the open ones we consider use any techniques specifically designed to encourage robustness. Next, we show that similar trends hold for social media translation experiments -- LLMs are more robust to social media text. We include an analysis of the circumstances in which source correction techniques can be used to mitigate the effects of noise. Altogether, we show that robustness to many types of noise has increased.

[Arxiv](https://arxiv.org/abs/2403.03923)