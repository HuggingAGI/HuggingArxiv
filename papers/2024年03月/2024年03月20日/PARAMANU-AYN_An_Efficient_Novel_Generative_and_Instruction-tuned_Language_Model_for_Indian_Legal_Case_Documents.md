# PARAMANU-AYN，一款专为印度法律案卷打造的高效创新生成模型，其特色在于能够根据指令进行精细调优。

发布时间：2024年03月20日

`Agent`

> PARAMANU-AYN: An Efficient Novel Generative and Instruction-tuned Language Model for Indian Legal Case Documents

> 本文推出了一款独特的语言模型PARAMANU-AYN，它专为印度最高法院判例、印度宪法及印度刑法典定制。这款创新的自回归解码器模型以8192的上下文大小从零开始预训练。我们对该模型进行了预先训练后的法律领域困惑度评测，并对其进行了指令微调，涉及涵盖法律推理、判决解析、法条生成、法律文书起草、法律合同撰写、案情概要、宪法问答等在内的10,763条指令集。同时，我们借助GPT-3.5-Turbo对指令微调后模型的输出依据清晰度、关联性、完整性以及法律推理四项标准进行10分制评估。尽管没有在法律书籍和各类法律文本上预训练，此模型却能掌握起草各类法律合同时所需的领域知识，并能在少量指令调整下胜任法律合同和法条的起草工作。这表明，即使针对如法律这样的特定领域生成语言模型，也无需庞大无比的数据集从零起步。我们相信，这是首度尝试专门针对印度最高法院司法权乃至整个法律NLP领域，从零开始研发一款专注生成式法律语言模型的工作。未来我们将把Paramanu-Ayn模型在https://www.bharatgpts.com网站上公开发布。

> In this paper, we present PARAMANU-AYN, a language model based exclusively on case documents of the Supreme Court of India, the Constitution of India, and the Indian Penal Code. The novel Auto Regressive (AR) decoder based model is pretrained from scratch at a context size of 8192. We evaluated our pretrained legal model on perplexity metrics. We also instruction-tuned our pretrained model on a set of 10,763 instructions covering various legal tasks such as legal reasoning, judgement explanation, legal clause generation, legal drafting, legal contract drafting, case summarization, constitutional question-answering, etc. We also evaluated the responses of prompts for instruction-tuned models by GPT-3.5-Turbo on clarity, relevance, completeness, and legal reasoning metrics in a scale of 10. Our model can be run on CPU and achieved 42.46 tokens/sec CPU inference speed. We found that our models, despite not being pretrained on legal books, various legal contracts, and legal documents, were able to learn the domain knowledge required for drafting various legal contracts and legal clauses, and generalize to draft legal contracts and legal clauses with limited instruction tuning. Hence, we conclude that for a strong domain-specialized generative language model (such as legal), very large amounts of data are not required to develop models from scratch. We believe that this work is the first attempt to make a dedicated generative legal language model from scratch for Indian Supreme Court jurisdiction or in legal NLP overall. We plan to release our Paramanu-Ayn model at https://www.bharatgpts.com.

[Arxiv](https://arxiv.org/abs/2403.13681)