# 面对长篇文档，细节总记不住？或许你需要来点“R&R”魔法。 （注：这里的“R&R”在原文中未明确指出含义，可能是“Rest and Relaxation（休息与放松）”或某种解决方法的缩写，在翻译时可根据上下文进行适当推测和解释。）

发布时间：2024年03月07日

`RAG`

> Can't Remember Details in Long Documents? You Need Some R&R

> 对于处理长文档问题回答（QA）这类任务，长篇上下文大型语言模型（LLMs）虽然前景广阔，却常常遗漏掉位于文档中部的关键信息（参考arXiv:2307.03172v3）。为此，我们创新提出了一项名为$\textit{R&R}$的方法，该方法巧妙融合了“重复提示”与“情境检索”（ICR）这两种新颖的基于提示策略，有效减轻了基于文档的QA中信息遗漏的问题。在“重复提示”技术中，我们不断在文档上下文中间隔插入提示指令，确保LLM时刻牢记其初始任务。而在“情境检索”环节，我们不再让LLM直面问题作答，而是指导它找出与目标问题最为相关的前k个段落编号，并以此为依据构建精炼的二次QA提示上下文。经过在最长80k标记文档上的实践验证，当采用GPT-4 Turbo和Claude-2.1时，R&R方案使得QA准确率平均提升了16个百分点。深入探究发现，R&R之所以能在长文档QA任务上有所建树，关键在于它缩小了关键上下文与指令间的认知差距。此外，我们还揭示相较于传统的短篇上下文分块法，R&R不仅能够使用更大、成本更低的文本块进行处理（减少LLM调用量和输出标记数），还能在保证精度的前提下实现效率优化。

> Long-context large language models (LLMs) hold promise for tasks such as question-answering (QA) over long documents, but they tend to miss important information in the middle of context documents (arXiv:2307.03172v3). Here, we introduce $\textit{R&R}$ -- a combination of two novel prompt-based methods called $\textit{reprompting}$ and $\textit{in-context retrieval}$ (ICR) -- to alleviate this effect in document-based QA. In reprompting, we repeat the prompt instructions periodically throughout the context document to remind the LLM of its original task. In ICR, rather than instructing the LLM to answer the question directly, we instruct it to retrieve the top $k$ passage numbers most relevant to the given question, which are then used as an abbreviated context in a second QA prompt. We test R&R with GPT-4 Turbo and Claude-2.1 on documents up to 80k tokens in length and observe a 16-point boost in QA accuracy on average. Our further analysis suggests that R&R improves performance on long document-based QA because it reduces the distance between relevant context and the instructions. Finally, we show that compared to short-context chunkwise methods, R&R enables the use of larger chunks that cost fewer LLM calls and output tokens, while minimizing the drop in accuracy.

[Arxiv](https://arxiv.org/abs/2403.05004)