# 除了电影字幕，YouTube 是否能更准确地反映口语词汇？

发布时间：2024年10月04日

`LLM应用` `心理语言学` `语言学`

> Beyond Film Subtitles: Is YouTube the Best Approximation of Spoken Vocabulary?

# 摘要

> 词频在心理语言学中至关重要，即使在 LLM 时代，它也能有效衡量人类对词汇的熟悉度。电影字幕中的词频尤其能反映日常语言使用情况。然而，许多语言的电影字幕难以获取，或多为英译本。我们发现，精心处理的 YouTube 字幕词频不仅与现有最佳资源相当，甚至更优，且适用于缺乏高质量字幕的语言。我们为五种语言（中文、英语、印尼语、日语和西班牙语）构建了词频规范，并验证了其与词汇决策时间、熟悉度和复杂性的高度相关性。此外，基于这些新词频的简单线性回归模型在英语和日语的词汇复杂性预测任务中表现卓越，超越了基于电影字幕的模型和 GPT-4。所有资源均可免费获取，详见 https://github.com/naist-nlp/tubelex。

> Word frequency is a key variable in psycholinguistics, useful for modeling human familiarity with words even in the era of large language models (LLMs). Frequency in film subtitles has proved to be a particularly good approximation of everyday language exposure. For many languages, however, film subtitles are not easily available, or are overwhelmingly translated from English. We demonstrate that frequencies extracted from carefully processed YouTube subtitles provide an approximation comparable to, and often better than, the best currently available resources. Moreover, they are available for languages for which a high-quality subtitle or speech corpus does not exist. We use YouTube subtitles to construct frequency norms for five diverse languages, Chinese, English, Indonesian, Japanese, and Spanish, and evaluate their correlation with lexical decision time, word familiarity, and lexical complexity. In addition to being strongly correlated with two psycholinguistic variables, a simple linear regression on the new frequencies achieves a new high score on a lexical complexity prediction task in English and Japanese, surpassing both models trained on film subtitle frequencies and the LLM GPT-4. Our code, the frequency lists, fastText word embeddings, and statistical language models are freely available at https://github.com/naist-nlp/tubelex.

[Arxiv](https://arxiv.org/abs/2410.03240)