# 调整语言模型以明确解决歧义问题

发布时间：2024年04月18日

`分类：LLM应用` `对话系统`

> Aligning Language Models to Explicitly Handle Ambiguity

# 摘要

> 在日常对话中，为了效率，人们常使语句显得简略或含糊，这可能导致基于不同上下文假设的多样化解读。在这样的情境下，模型必须巧妙地应对用户提问中的歧义，以保证用户与模型之间的可靠互动。但是，即使是基于最新大型语言模型（LLMs）的对话系统，在解析含糊信息时也遇到了难题，这主要归咎于两点：首先，LLMs 并未被专门训练来处理那些过于含糊、难以有效管理的输入；其次，输入的含糊性会根据 LLMs 内在的知识水平而异，这使得问题的探究变得复杂。为了应对这些挑战，本文提出了一种方法，让 LLMs 能够明确地处理含糊的输入。具体而言，我们设计了一个代理任务，促使 LLMs 运用其内在的知识来自动消除输入信息的歧义。我们通过量化消歧过程中的信息增益，来衡量模型对输入歧义性的感知程度。这一衡量标准帮助我们从模型的视角筛选出那些被认为是含糊的样本，进而用于模型的优化。多个问答数据集的实验结果显示，采用我们方法进行微调的 LLMs 在处理含糊输入时表现出色，同时在处理明确问题时也保持了竞争力。

> In spoken languages, utterances are often shaped to be incomplete or vague for efficiency. This can lead to varying interpretations of the same input, based on different assumptions about the context. To ensure reliable user-model interactions in such scenarios, it is crucial for models to adeptly handle the inherent ambiguity in user queries. However, conversational agents built upon even the most recent large language models (LLMs) face challenges in processing ambiguous inputs, primarily due to the following two hurdles: (1) LLMs are not directly trained to handle inputs that are too ambiguous to be properly managed; (2) the degree of ambiguity in an input can vary according to the intrinsic knowledge of the LLMs, which is difficult to investigate. To address these issues, this paper proposes a method to align LLMs to explicitly handle ambiguous inputs. Specifically, we introduce a proxy task that guides LLMs to utilize their intrinsic knowledge to self-disambiguate a given input. We quantify the information gain from the disambiguation procedure as a measure of the extent to which the models perceive their inputs as ambiguous. This measure serves as a cue for selecting samples deemed ambiguous from the models' perspectives, which are then utilized for alignment. Experimental results from several question-answering datasets demonstrate that the LLMs fine-tuned with our approach are capable of handling ambiguous inputs while still performing competitively on clear questions within the task.

![调整语言模型以明确解决歧义问题](../../../paper_images/2404.11972/x1.png)

![调整语言模型以明确解决歧义问题](../../../paper_images/2404.11972/x2.png)

[Arxiv](https://arxiv.org/abs/2404.11972)