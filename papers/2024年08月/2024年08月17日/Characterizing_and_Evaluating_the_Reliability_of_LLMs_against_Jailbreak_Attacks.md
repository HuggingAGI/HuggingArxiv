# 探究与评估 LLM 在面对越狱攻击时的可靠性

发布时间：2024年08月17日

`LLM应用` `网络安全` `人工智能`

> Characterizing and Evaluating the Reliability of LLMs against Jailbreak Attacks

# 摘要

> 随着大型语言模型（LLM）在内容生成中的作用日益凸显，其社会影响力也愈发显著。然而，这些模型潜在的生成有害内容的能力不容忽视。为此，业界已采取措施，如加强社会伦理的遵守，但“越狱”现象——即通过精心设计的提示诱导模型产生有害反应——仍是一大挑战。面对这一持续威胁，本研究不仅构建了一个全面的评估框架，还开展了一项大规模实证实验，旨在深入分析LLM的抗攻击能力。我们选取了10种前沿的越狱策略、涵盖61个有害类别的1525个问题，以及13个主流LLM，运用攻击成功率、毒性评分、流畅度等多维度指标，全面评估模型在越狱情境下的表现。通过这些指标的综合分析，我们为各LLM提供了详尽的可靠性评分，并提出针对性建议，以降低其易受攻击性。此外，我们还深入探讨了模型、攻击策略与有害内容之间的关联，以及评估指标间的相互关系，从而验证了我们评估框架的多维有效性。实验结果显示，所有测试的LLM在某些策略面前均显脆弱，这强调了提升LLM可靠性的紧迫性。我们坚信，本研究能为LLM安全评估领域提供宝贵洞见，助力其抵御越狱威胁。

> Large Language Models (LLMs) have increasingly become pivotal in content generation with notable societal impact. These models hold the potential to generate content that could be deemed harmful.Efforts to mitigate this risk include implementing safeguards to ensure LLMs adhere to social ethics.However, despite such measures, the phenomenon of "jailbreaking" -- where carefully crafted prompts elicit harmful responses from models -- persists as a significant challenge. Recognizing the continuous threat posed by jailbreaking tactics and their repercussions for the trustworthy use of LLMs, a rigorous assessment of the models' robustness against such attacks is essential. This study introduces an comprehensive evaluation framework and conducts an large-scale empirical experiment to address this need. We concentrate on 10 cutting-edge jailbreak strategies across three categories, 1525 questions from 61 specific harmful categories, and 13 popular LLMs. We adopt multi-dimensional metrics such as Attack Success Rate (ASR), Toxicity Score, Fluency, Token Length, and Grammatical Errors to thoroughly assess the LLMs' outputs under jailbreak. By normalizing and aggregating these metrics, we present a detailed reliability score for different LLMs, coupled with strategic recommendations to reduce their susceptibility to such vulnerabilities. Additionally, we explore the relationships among the models, attack strategies, and types of harmful content, as well as the correlations between the evaluation metrics, which proves the validity of our multifaceted evaluation framework. Our extensive experimental results demonstrate a lack of resilience among all tested LLMs against certain strategies, and highlight the need to concentrate on the reliability facets of LLMs. We believe our study can provide valuable insights into enhancing the security evaluation of LLMs against jailbreak within the domain.

[Arxiv](https://arxiv.org/abs/2408.09326)