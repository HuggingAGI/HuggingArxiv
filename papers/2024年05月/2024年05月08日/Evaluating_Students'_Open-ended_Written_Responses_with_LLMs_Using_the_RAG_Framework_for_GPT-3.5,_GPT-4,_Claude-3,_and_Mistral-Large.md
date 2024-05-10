# 借助RAG框架，我们评估了GPT-3.5、GPT-4、Claude-3和Mistral-Large在评价学生开放式书面回答方面的表现。本研究旨在探索这些大型语言模型在教育评估中的应用潜力。

发布时间：2024年05月08日

`RAG

理由：这篇论文主要探讨了使用大型语言模型（LLMs）如ChatGPT-3.5、ChatGPT-4、Claude-3和Mistral-Large在教育评估中的应用，特别是通过RAG框架来指导这些模型进行学生答案的评估。虽然论文涉及了LLM的应用，但其核心在于使用RAG框架来改进评估过程，因此更符合RAG分类。同时，论文并没有深入探讨LLM的理论问题，也没有提及Agent的概念，因此LLM理论和Agent分类不适用。` `教育评估` `人工智能辅助教育`

> Evaluating Students' Open-ended Written Responses with LLMs: Using the RAG Framework for GPT-3.5, GPT-4, Claude-3, and Mistral-Large

# 摘要

> 教育工作者在评估学生的开放式书面考试答案时面临着既重要又耗时的挑战，这要求他们付出巨大的努力、保持一致性和精确性。大型语言模型（LLMs）的进步是解决这一难题的希望之光，它们能够在确保评估质量的同时节省教育工作者的时间。在我们的研究中，我们测试了ChatGPT-3.5、ChatGPT-4、Claude-3和Mistral-Large这四种LLMs在评估大学生对所学材料的开放式问题答案时的效果。每个模型在两种不同的温度设置下重复评估了54个答案，总共进行了4,320次评估。我们使用了RAG框架来指导LLMs进行评估。到2024年春季，我们的分析显示，这些LLMs在评分一致性和结果上存在显著差异。我们需要更深入地了解LLMs在教育评估中的优势和局限性。进一步的研究对于确定LLMs在教育评估中的准确性和经济性至关重要。

> Evaluating open-ended written examination responses from students is an essential yet time-intensive task for educators, requiring a high degree of effort, consistency, and precision. Recent developments in Large Language Models (LLMs) present a promising opportunity to balance the need for thorough evaluation with efficient use of educators' time. In our study, we explore the effectiveness of LLMs ChatGPT-3.5, ChatGPT-4, Claude-3, and Mistral-Large in assessing university students' open-ended answers to questions made about reference material they have studied. Each model was instructed to evaluate 54 answers repeatedly under two conditions: 10 times (10-shot) with a temperature setting of 0.0 and 10 times with a temperature of 0.5, expecting a total of 1,080 evaluations per model and 4,320 evaluations across all models. The RAG (Retrieval Augmented Generation) framework was used as the framework to make the LLMs to process the evaluation of the answers. As of spring 2024, our analysis revealed notable variations in consistency and the grading outcomes provided by studied LLMs. There is a need to comprehend strengths and weaknesses of LLMs in educational settings for evaluating open-ended written responses. Further comparative research is essential to determine the accuracy and cost-effectiveness of using LLMs for educational assessments.

[Arxiv](https://arxiv.org/abs/2405.05444)