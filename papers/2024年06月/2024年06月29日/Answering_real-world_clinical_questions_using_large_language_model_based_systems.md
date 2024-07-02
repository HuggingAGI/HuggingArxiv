# 利用大型语言模型系统解答实际临床难题

发布时间：2024年06月29日

`RAG` `人工智能`

> Answering real-world clinical questions using large language model based systems

# 摘要

> 在医疗决策中，由于缺乏相关且可信的文献，以及难以将现有研究应用于特定患者，证据往往受限。大型语言模型（LLM）通过总结文献或基于真实世界数据（RWD）生成新研究，有望解决这些难题。我们测试了五个LLM系统回答50个临床问题的能力，并由九名独立医生评估了答案的相关性、可靠性和可操作性。结果显示，通用型LLM（如ChatGPT-4、Claude 3 Opus、Gemini Pro 1.5）很少能提供相关且基于证据的答案（仅占2% - 10%）。相反，基于检索增强生成（RAG）和代理型LLM系统的表现更佳，能提供相关且基于证据的答案，占比从24%（OpenEvidence）到58%（ChatRWD）。特别是代理型ChatRWD，能回答更多新问题（65% vs. 0-9%）。这些发现表明，虽然不应直接使用通用型LLM，但专门设计的基于RAG的证据总结系统和协同工作的系统，将显著提升患者护理相关证据的可用性。

> Evidence to guide healthcare decisions is often limited by a lack of relevant and trustworthy literature as well as difficulty in contextualizing existing research for a specific patient. Large language models (LLMs) could potentially address both challenges by either summarizing published literature or generating new studies based on real-world data (RWD). We evaluated the ability of five LLM-based systems in answering 50 clinical questions and had nine independent physicians review the responses for relevance, reliability, and actionability. As it stands, general-purpose LLMs (ChatGPT-4, Claude 3 Opus, Gemini Pro 1.5) rarely produced answers that were deemed relevant and evidence-based (2% - 10%). In contrast, retrieval augmented generation (RAG)-based and agentic LLM systems produced relevant and evidence-based answers for 24% (OpenEvidence) to 58% (ChatRWD) of questions. Only the agentic ChatRWD was able to answer novel questions compared to other LLMs (65% vs. 0-9%). These results suggest that while general-purpose LLMs should not be used as-is, a purpose-built system for evidence summarization based on RAG and one for generating novel evidence working synergistically would improve availability of pertinent evidence for patient care.

[Arxiv](https://arxiv.org/abs/2407.00541)