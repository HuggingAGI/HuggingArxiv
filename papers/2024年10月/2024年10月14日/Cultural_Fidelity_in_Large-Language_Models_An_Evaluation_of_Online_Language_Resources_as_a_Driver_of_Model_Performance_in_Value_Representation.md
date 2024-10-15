# 大型语言模型中的文化保真度：探讨在线语言资源如何影响模型在价值表示方面的性能。

发布时间：2024年10月14日

`LLM应用` `语言技术` `数字鸿沟`

> Cultural Fidelity in Large-Language Models: An Evaluation of Online Language Resources as a Driver of Model Performance in Value Representation

# 摘要

> LLM的训练数据中嵌入了社会价值观，使其更熟悉语言文化。研究发现，GPT-4o反映国家社会价值观的能力，44%的差异与该语言数字资源的丰富程度相关。特别是，资源匮乏语言的错误率是资源丰富语言的五倍多。对于GPT-4-turbo，这一相关性提升至72%，表明除了网络数据外，还需努力提升对非英语语言的熟悉度。我们构建了包含21个国家和语言对的大型数据集，每个对包含94个经母语者验证的调查问题。结果显示，LLM性能与目标语言数字数据可用性密切相关。低资源语言，尤其是全球南方的语言，表现较弱，可能加剧数字鸿沟。我们探讨了应对策略，如从头开发多语言LLM和在多样语言数据集上进行微调，如非洲语言项目所示。

> The training data for LLMs embeds societal values, increasing their familiarity with the language's culture. Our analysis found that 44% of the variance in the ability of GPT-4o to reflect the societal values of a country, as measured by the World Values Survey, correlates with the availability of digital resources in that language. Notably, the error rate was more than five times higher for the languages of the lowest resource compared to the languages of the highest resource. For GPT-4-turbo, this correlation rose to 72%, suggesting efforts to improve the familiarity with the non-English language beyond the web-scraped data. Our study developed one of the largest and most robust datasets in this topic area with 21 country-language pairs, each of which contain 94 survey questions verified by native speakers. Our results highlight the link between LLM performance and digital data availability in target languages. Weaker performance in low-resource languages, especially prominent in the Global South, may worsen digital divides. We discuss strategies proposed to address this, including developing multilingual LLMs from the ground up and enhancing fine-tuning on diverse linguistic datasets, as seen in African language initiatives.

[Arxiv](https://arxiv.org/abs/2410.10489)