# 刻板印象之源：在线资源中种族与性别疾病关联的大规模文本探析

发布时间：2024年05月08日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在医疗保健领域的应用中可能出现的偏见问题，特别是关注了训练数据中疾病与人口统计学关联的不平衡性。通过分析网络文本资源，研究揭示了LLMs可能吸收的潜在偏见，并与真实的人口统计学疾病流行率以及GPT-4的输出进行了对比。这项工作强调了对LLM预训练数据集中偏见的深入审查和透明报告的必要性，以及在医疗保健领域减轻这些偏见影响的策略。因此，它属于LLM理论分类，因为它关注的是LLMs的理论基础和潜在问题，而不是它们的实际应用或特定的Agent或RAG系统。` `医疗保健` `人工智能伦理`

> Seeds of Stereotypes: A Large-Scale Textual Analysis of Race and Gender Associations with Diseases in Online Sources

# 摘要

> 大型语言模型（LLMs）在医疗保健领域具有革命性的潜力，但最近的研究揭示了这些模型在输出中显露种族或性别偏见的倾向。尽管训练数据可能是偏见的源头，但大规模文本数据中疾病与人口统计学关联的研究仍显不足。方法：我们进行了一项广泛的文本分析，利用了包含多种网络资源（如Arxiv、Wikipedia和Common Crawl）的数据集。该研究探究了疾病在网络文本中与种族和性别标记的关联情况。由于LLMs的预训练数据集与此类似，这使我们能够揭示LLMs可能吸收的潜在偏见。我们将这些发现与真实的人口统计学疾病流行率以及GPT-4的输出进行了对比，以衡量偏见的表现程度。结果：我们的研究表明，在线文本中，人口统计学术语与特定疾病概念的关联存在显著的不平衡。性别术语与疾病概念的关联尤为突出，而种族术语的关联则相对较少。我们发现，在分析的18种疾病中，特定种族和性别术语的关联存在广泛的不平等。最引人注目的是，我们观察到黑人种族的提及在人口比例中被显著高估。结论：我们的研究强调了对LLM预训练数据集中偏见的深入审查和透明报告的紧迫性。我们的发现表明，有必要制定策略来减轻LLMs中偏见训练数据的影响，尤其是在医疗保健这样对偏见敏感的领域。

> Background Advancements in Large Language Models (LLMs) hold transformative potential in healthcare, however, recent work has raised concern about the tendency of these models to produce outputs that display racial or gender biases. Although training data is a likely source of such biases, exploration of disease and demographic associations in text data at scale has been limited.
  Methods We conducted a large-scale textual analysis using a dataset comprising diverse web sources, including Arxiv, Wikipedia, and Common Crawl. The study analyzed the context in which various diseases are discussed alongside markers of race and gender. Given that LLMs are pre-trained on similar datasets, this approach allowed us to examine the potential biases that LLMs may learn and internalize. We compared these findings with actual demographic disease prevalence as well as GPT-4 outputs in order to evaluate the extent of bias representation.
  Results Our findings indicate that demographic terms are disproportionately associated with specific disease concepts in online texts. gender terms are prominently associated with disease concepts, while racial terms are much less frequently associated. We find widespread disparities in the associations of specific racial and gender terms with the 18 diseases analyzed. Most prominently, we see an overall significant overrepresentation of Black race mentions in comparison to population proportions.
  Conclusions Our results highlight the need for critical examination and transparent reporting of biases in LLM pretraining datasets. Our study suggests the need to develop mitigation strategies to counteract the influence of biased training data in LLMs, particularly in sensitive domains such as healthcare.

[Arxiv](https://arxiv.org/abs/2405.05049)