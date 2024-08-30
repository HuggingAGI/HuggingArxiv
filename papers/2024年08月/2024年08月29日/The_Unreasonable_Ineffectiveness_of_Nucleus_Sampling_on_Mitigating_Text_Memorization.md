# 核采样在缓解文本记忆问题上显得不尽如人意。

发布时间：2024年08月29日

`LLM理论` `人工智能`

> The Unreasonable Ineffectiveness of Nucleus Sampling on Mitigating Text Memorization

# 摘要

> 本研究探讨了大型语言模型在核采样下的文本记忆行为。核采样等随机解码方法旨在解决基于最大化解码技术中常见的单调重复文本问题。我们推测，核采样可能通过选择记忆序列外的标记来减少记忆模式的出现。为此，我们构建了一个包含已知重复分布的诊断数据集，以便控制训练数据部分内容的记忆概率。分析显示，增大核大小仅轻微减少记忆，且即使模型未进行“硬”记忆（逐字复制训练样本），也可能通过“软”记忆方式，即生成与训练数据相似但不完全相同的输出来反映训练内容。

> This work analyses the text memorization behavior of large language models (LLMs) when subjected to nucleus sampling. Stochastic decoding methods like nucleus sampling are typically applied to overcome issues such as monotonous and repetitive text generation, which are often observed with maximization-based decoding techniques. We hypothesize that nucleus sampling might also reduce the occurrence of memorization patterns, because it could lead to the selection of tokens outside the memorized sequence. To test this hypothesis we create a diagnostic dataset with a known distribution of duplicates that gives us some control over the likelihood of memorization of certain parts of the training data. Our analysis of two GPT-Neo models fine-tuned on this dataset interestingly shows that (i) an increase of the nucleus size reduces memorization only modestly, and (ii) even when models do not engage in "hard" memorization -- a verbatim reproduction of training samples -- they may still display "soft" memorization whereby they generate outputs that echo the training data but without a complete one-by-one resemblance.

[Arxiv](https://arxiv.org/abs/2408.16345)