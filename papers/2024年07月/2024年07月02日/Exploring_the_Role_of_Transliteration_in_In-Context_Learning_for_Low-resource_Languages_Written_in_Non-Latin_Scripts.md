# 研究音译在非拉丁文字低资源语言上下文学习中的角色

发布时间：2024年07月02日

`LLM应用` `语言技术`

> Exploring the Role of Transliteration in In-Context Learning for Low-resource Languages Written in Non-Latin Scripts

# 摘要

> 仅解码器的 LLM 在高资源语言的多种任务中通过少样本或零样本的 ICL 表现卓越，但其在低资源语言，尤其是非拉丁文字语言上的表现往往不佳。借鉴近期利用音译提升仅编码器模型性能的研究，我们探索音译是否同样能提升非拉丁文字低资源语言的 LLM 性能。为此，我们设计了三种提示模板，分别以原始文字、拉丁文字或两者兼备的形式呈现目标语言文本。在文本分类和序列标注等任务中，我们测试了这些方法在不同大小的 LLM 上的效果。结果显示，音译的效果因任务和模型大小而异，例如，所有模型在序列标注任务中均因音译而显著提升（最高达 25%）。

> Decoder-only large language models (LLMs) excel in high-resource languages across various tasks through few-shot or even zero-shot in-context learning (ICL). However, their performance often does not transfer well to low-resource languages, especially those written in non-Latin scripts. Inspired by recent work that leverages transliteration in encoder-only models, we investigate whether transliteration is also effective in improving LLMs' performance for low-resource languages written in non-Latin scripts. To this end, we propose three prompt templates, where the target-language text is represented in (1) its original script, (2) Latin script, or (3) both. We apply these methods to several representative LLMs of different sizes on various tasks including text classification and sequential labeling. Our findings show that the effectiveness of transliteration varies by task type and model size. For instance, all models benefit from transliterations for sequential labeling (with increases of up to 25%).

[Arxiv](https://arxiv.org/abs/2407.02320)