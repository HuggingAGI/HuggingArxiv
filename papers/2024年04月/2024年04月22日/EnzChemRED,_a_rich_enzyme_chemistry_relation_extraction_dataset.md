# EnzChemRED，一个涵盖丰富酶化学关系的提取数据集。

发布时间：2024年04月22日

`LLM应用` `生物信息学`

> EnzChemRED, a rich enzyme chemistry relation extraction dataset

# 摘要

> 专家精选对于在公平开放的知识库中捕捉科学文献中的酶功能知识至关重要，但面对新发现和出版物的快速增长，这一过程显得力不从心。本研究介绍了EnzChemRED——酶化学关系提取数据集，这是一个新的训练和基准数据集，旨在支持自然语言处理（NLP）方法的发展，包括大型语言模型，以辅助酶的功能策划。EnzChemRED包含1,210篇经专家精选的PubMed摘要，其中酶及其催化的化学反应均已通过UniProt知识库（UniProtKB）和生物化学实体本体（ChEBI）的标识符进行了标注。研究表明，使用EnzChemRED对预训练的语言模型进行微调，可以显著提升模型在文本中识别蛋白质和化学物质（命名实体识别，NER）以及提取它们参与的化学反应（关系提取，RE）的能力，其中NER的平均F1得分为86.30%，化学转换对的RE平均F1得分为86.66%，化学转换对及关联酶的RE平均F1得分为83.79%。我们将微调后表现最优的方法结合起来，构建了一个文本知识提取的端到端流程，并将其应用于PubMed规模的摘要，创建了一份酶功能文献草图，以指导UniProtKB和反应知识库Rhea中的策划工作。EnzChemRED语料库目前已在https://ftp.expasy.org/databases/rhea/nlp/上开放获取。

> Expert curation is essential to capture knowledge of enzyme functions from the scientific literature in FAIR open knowledgebases but cannot keep pace with the rate of new discoveries and new publications. In this work we present EnzChemRED, for Enzyme Chemistry Relation Extraction Dataset, a new training and benchmarking dataset to support the development of Natural Language Processing (NLP) methods such as (large) language models that can assist enzyme curation. EnzChemRED consists of 1,210 expert curated PubMed abstracts in which enzymes and the chemical reactions they catalyze are annotated using identifiers from the UniProt Knowledgebase (UniProtKB) and the ontology of Chemical Entities of Biological Interest (ChEBI). We show that fine-tuning pre-trained language models with EnzChemRED can significantly boost their ability to identify mentions of proteins and chemicals in text (Named Entity Recognition, or NER) and to extract the chemical conversions in which they participate (Relation Extraction, or RE), with average F1 score of 86.30% for NER, 86.66% for RE for chemical conversion pairs, and 83.79% for RE for chemical conversion pairs and linked enzymes. We combine the best performing methods after fine-tuning using EnzChemRED to create an end-to-end pipeline for knowledge extraction from text and apply this to abstracts at PubMed scale to create a draft map of enzyme functions in literature to guide curation efforts in UniProtKB and the reaction knowledgebase Rhea. The EnzChemRED corpus is freely available at https://ftp.expasy.org/databases/rhea/nlp/.

[Arxiv](https://arxiv.org/abs/2404.14209)