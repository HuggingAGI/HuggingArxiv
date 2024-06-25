# 大型语言模型，知识推理的情境导师。

发布时间：2024年06月17日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）在上下文学习中的应用，特别是通过“自解释”方法和“回授”技术来优化模型在特定上下文中的推理能力。这些研究不仅涉及模型的应用，更深入地探讨了模型如何通过特定的训练和教学方法来提高其推理能力，这属于对LLM理论的深入研究。因此，将其归类为LLM理论。` `人工智能`

> Large Language Models are In-context Teachers for Knowledge Reasoning

# 摘要

> 思维链提示法教导大型语言模型在特定上下文中进行深入推理，超越了简单的信息检索。然而，这种上下文学习往往依赖于人类专家精心设计的演示，成本高且效果参差不齐。更重要的是，如何设计有效的推理示例以促进上下文学习仍是一个未解之谜。本研究探讨了大型语言模型是否能成为更优秀的上下文知识推理导师。我们依据人类记忆检索的“编码特异性”原则，假设推理阶段的上下文示例应与训练环境相契合。基于此，我们提出了“自解释”方法，利用模型自身从训练实例中提炼出的解释作为上下文演示，这种方法显著优于人类设计的示例和其他基准。进一步研究发现，那些更贴近学生模型自我解释的教师模型或人类专家提供的推理理由，在上下文教学中表现更佳，这验证了我们的编码特异性假设。随后，我们开发了“回授”技术，通过调整教师模型与学生的匹配度，显著提升了上下文教学的效果。例如，通过回授，一个70亿参数的模型能在上下文中有效指导更大的GPT-3.5模型，在医学问答测试中准确率超越人类教师约5%。

> Chain-of-thought (CoT) prompting teaches large language models (LLMs) in context to reason over queries that require more than mere information retrieval. However, human experts are usually required to craft demonstrations for in-context learning (ICL), which is expensive and has high variance. More importantly, how to craft helpful reasoning exemplars for ICL remains unclear. In this work, we investigate whether LLMs can be better in-context teachers for knowledge reasoning. We follow the ``encoding specificity'' hypothesis in human's memory retrieval to assume in-context exemplars at inference should match the encoding context in training data. We are thus motivated to propose Self-Explain to use one LLM's self-elicited explanations as in-context demonstrations for prompting it as they are generalized from the model's training examples. Self-Explain is shown to significantly outperform using human-crafted exemplars and other baselines. We further reveal that for in-context teaching, rationales by distinct teacher LLMs or human experts that more resemble the student LLM's self-explanations are better demonstrations, which supports our encoding specificity hypothesis. We then propose Teach-Back that aligns the teacher LLM with the student to enhance the in-context teaching performance. For example, Teach-Back enables a 7B model to teach the much larger GPT-3.5 in context, surpassing human teachers by around 5% in test accuracy on medical question answering.

[Arxiv](https://arxiv.org/abs/2311.06985)