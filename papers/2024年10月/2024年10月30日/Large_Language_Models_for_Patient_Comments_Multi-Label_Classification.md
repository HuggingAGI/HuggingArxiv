# 用于患者评论多标签分类的大型语言模型

发布时间：2024年10月30日

`LLM应用` `文本分类`

> Large Language Models for Patient Comments Multi-Label Classification

# 摘要

> 患者体验和护理质量对医院的可持续发展及声誉举足轻重。对患者反馈的剖析能为患者满意度和治疗成效提供宝贵洞见。然而，这些评论的非结构化特点给遵循监督学习范式的传统机器学习方法造成了难题。原因在于缺乏有标注的数据以及这些文本所蕴含的细微差异。本研究致力于借助大型语言模型（LLMs）对住院患者出院后分享的评论开展多标签文本分类（MLTC）。采用了 GPT-4o-Turbo 进行分类。鉴于患者评论的敏感性，在将数据输入到 LLM 之前，通过受保护健康信息（PHI）检测框架引入了一层安全保障，以实现患者的去识别。此外，运用提示工程框架，对零样本学习、上下文学习和思维链提示进行了试验。结果显示，无论在零样本还是少样本的设定下，GPT-4o-Turbo 都胜过传统方法和预训练语言模型（PLMs），以 76.12%的 F1 分数和 73.61%的加权 F1 分数斩获最高的总体性能，少样本学习的结果也紧随其后。随后，还探究了结果与其他患者体验结构化变量（如评级）的关联。该研究通过应用 LLMs 强化了 MLTC，为医疗保健从业者提供了一种高效途径，使其能更深入地洞察患者反馈，并给出及时、恰当的回应。

> Patient experience and care quality are crucial for a hospital's sustainability and reputation. The analysis of patient feedback offers valuable insight into patient satisfaction and outcomes. However, the unstructured nature of these comments poses challenges for traditional machine learning methods following a supervised learning paradigm. This is due to the unavailability of labeled data and the nuances these texts encompass. This research explores leveraging Large Language Models (LLMs) in conducting Multi-label Text Classification (MLTC) of inpatient comments shared after a stay in the hospital. GPT-4o-Turbo was leveraged to conduct the classification. However, given the sensitive nature of patients' comments, a security layer is introduced before feeding the data to the LLM through a Protected Health Information (PHI) detection framework, which ensures patients' de-identification. Additionally, using the prompt engineering framework, zero-shot learning, in-context learning, and chain-of-thought prompting were experimented with. Results demonstrate that GPT-4o-Turbo, whether following a zero-shot or few-shot setting, outperforms traditional methods and Pre-trained Language Models (PLMs) and achieves the highest overall performance with an F1-score of 76.12% and a weighted F1-score of 73.61% followed closely by the few-shot learning results. Subsequently, the results' association with other patient experience structured variables (e.g., rating) was conducted. The study enhances MLTC through the application of LLMs, offering healthcare practitioners an efficient method to gain deeper insights into patient feedback and deliver prompt, appropriate responses.

[Arxiv](https://arxiv.org/abs/2410.23528)