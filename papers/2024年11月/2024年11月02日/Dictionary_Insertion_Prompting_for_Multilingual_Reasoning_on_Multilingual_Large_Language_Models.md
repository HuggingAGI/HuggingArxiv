# 字典插入提示应用于多语言大型语言模型的多语言推理

发布时间：2024年11月02日

`LLM应用` `语言模型`

> Dictionary Insertion Prompting for Multilingual Reasoning on Multilingual Large Language Models

# 摘要

> 当前，大型语言模型（LLMs）的训练数据多由英语语料库占据，因此它们以英语为核心，在英语推理任务上表现抢眼。ootnote{本文重点研究以英语为核心的模型，不过对于非英语核心的LLMs，我们的方法通过运用字典中的核心语言也能通用。} 但在其他语言方面，它们的表现往往欠佳。全球约有7000种语言，其中不少在以英语为核心的LLMs中资源稀缺。为了主要使用这些语言的人群，让我们的LLMs支持这些语言迫在眉睫。模型训练通常有效，可计算成本高，还需要经验丰富的NLP专业人员。本文提出了一种名为	extbf{D}ictionary 	extbf{I}nsertion 	extbf{P}rompting（	extbf{DIP}）的新颖、简单却有效的方法。当给出非英语提示时，DIP会查阅单词字典，将单词的英语对应词插入到LLMs的提示中，从而能更好地翻译成英语，产生更优的英语模型思考步骤，进而取得明显更出色的结果。我们针对来自FLORES-200的约200种语言展开实验。由于缺乏充足的数据集，我们借助NLLB翻译器，从现有的4个英语推理基准（如GSM8K和AQuA）创建了合成的多语言基准。尽管DIP简单且计算量不大，我们却惊喜地发现它在多个开源和闭源LLMs的数学及常识推理任务上十分有效。ootnote{我们的字典、代码和合成基准将会开源，以助力未来的研究。}

> As current training data for Large Language Models (LLMs) are dominated by English corpus, they are English-centric and they present impressive performance on English reasoning tasks.\footnote{This paper primarily studies English-centric models, but our method could be universal by using the centric language in the dictionary for non-English-centric LLMs.} Yet, they usually suffer from lower performance in other languages. There are about 7,000 languages over the world, and many are low-resourced on English-centric LLMs. For the sake of people who primarily speak these languages, it is especially urgent to enable our LLMs in those languages. Model training is usually effective, but computationally expensive and requires experienced NLP practitioners. This paper presents a novel and simple yet effective method called \textbf{D}ictionary \textbf{I}nsertion \textbf{P}rompting (\textbf{DIP}). When providing a non-English prompt, DIP looks up a word dictionary and inserts words' English counterparts into the prompt for LLMs. It then enables better translation into English and better English model thinking steps which leads to obviously better results. We experiment with about 200 languages from FLORES-200. Since there are no adequate datasets, we use the NLLB translator to create synthetic multilingual benchmarks from the existing 4 English reasoning benchmarks such as GSM8K and AQuA. Despite the simplicity and computationally lightweight, we surprisingly found the effectiveness of DIP on math and commonsense reasoning tasks on multiple open-source and close-source LLMs.\footnote{Our dictionaries, code, and synthetic benchmarks will be open-sourced to facilitate future research.}

[Arxiv](https://arxiv.org/abs/2411.01141)