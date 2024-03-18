# UFO，作为一款统一且颇具灵活性的框架，专注于对大型语言模型的事实性进行精准评估。

发布时间：2024年02月22日

`LLM应用`

> UFO: a Unified and Flexible Framework for Evaluating Factuality of Large Language Models

> 大型语言模型产出的文本有时会出现与人类认知不符的现象，引发事实偏差甚至产生“虚构”内容。当前对LLMs事实准确性的评估方法主要依赖于模型抽取事实信息并与预设的事实数据库比对，但此类评估方式针对性强、难以推广，且对不同任务中事实来源的互换性研究尚浅。为此，我们将现有的四种事实来源——人工编撰的证据、参考文献、搜索引擎检索结果和LLM内含知识，与涵盖六大数据集的五个文本生成任务相结合，进行了分类梳理。进而，我们创新提出了一个基于LLM、具备统一性和灵活性的评估框架——\texttt{UFO}，该框架支持便捷接入各种事实来源以验证模型生成内容的真实性。依据这一框架，我们设计并实施了五种不同的评估情境。实验证明，在多数问答任务上，人工编写的证据和参考文档起到了决定性作用，二者在检索辅助型问答任务中可以相互替换；而在新闻事实生成任务中，则尤为倚重搜索引擎结果和LLM自身的知识库。目前，我们的数据集及代码已开放至GitHub平台，地址为 \url{https://github.com/WaldenRUC/UFO}。

> Large language models (LLMs) may generate text that lacks consistency with human knowledge, leading to factual inaccuracies or \textit{hallucination}. Existing research for evaluating the factuality of LLMs involves extracting fact claims using an LLM and verifying them against a predefined fact source. However, these evaluation metrics are task-specific, and not scalable, and the substitutability of fact sources in different tasks is under-explored. To address these challenges, we categorize four available fact sources: human-written evidence, reference documents, search engine results, and LLM knowledge, along with five text generation tasks containing six representative datasets. Then, we propose \texttt{UFO}, an LLM-based unified and flexible evaluation framework to verify facts against plug-and-play fact sources. We implement five evaluation scenarios based on this framework. Experimental results show that for most QA tasks, human-written evidence and reference documents are crucial, and they can substitute for each other in retrieval-augmented QA tasks. In news fact generation tasks, search engine results and LLM knowledge are essential. Our dataset and code are available at \url{https://github.com/WaldenRUC/UFO}.

[Arxiv](https://arxiv.org/abs/2402.14690)