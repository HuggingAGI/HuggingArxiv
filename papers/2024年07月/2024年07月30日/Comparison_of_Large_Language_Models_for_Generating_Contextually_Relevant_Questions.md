# 探究大型语言模型在生成上下文相关问题方面的表现

发布时间：2024年07月30日

`LLM应用` `人工智能`

> Comparison of Large Language Models for Generating Contextually Relevant Questions

# 摘要

> 本研究深入探讨了大型语言模型（LLM）在教育场景下自动生成问题的能力。通过对比三种LLM模型（无需微调），我们发现GPT-3.5和Llama 2-Chat 13B在生成问题方面略胜一筹，尤其是在问题与答案的清晰度和对齐度上。具体来说，GPT-3.5尤其擅长根据答案内容定制问题。为了验证这些问题的教育适用性，我们邀请了46名学生对246个问题进行了五项指标的评估。本研究不仅揭示了LLM在教育领域的应用潜力，也为未来相关研究提供了宝贵的参考。

> This study explores the effectiveness of Large Language Models (LLMs) for Automatic Question Generation in educational settings. Three LLMs are compared in their ability to create questions from university slide text without fine-tuning. Questions were obtained in a two-step pipeline: first, answer phrases were extracted from slides using Llama 2-Chat 13B; then, the three models generated questions for each answer. To analyze whether the questions would be suitable in educational applications for students, a survey was conducted with 46 students who evaluated a total of 246 questions across five metrics: clarity, relevance, difficulty, slide relation, and question-answer alignment. Results indicate that GPT-3.5 and Llama 2-Chat 13B outperform Flan T5 XXL by a small margin, particularly in terms of clarity and question-answer alignment. GPT-3.5 especially excels at tailoring questions to match the input answers. The contribution of this research is the analysis of the capacity of LLMs for Automatic Question Generation in education.

[Arxiv](https://arxiv.org/abs/2407.20578)