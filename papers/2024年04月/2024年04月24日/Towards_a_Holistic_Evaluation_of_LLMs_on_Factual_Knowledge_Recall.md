# 迈向对大型语言模型在事实知识记忆能力上的全面评估

发布时间：2024年04月24日

`LLM应用` `基准测试`

> Towards a Holistic Evaluation of LLMs on Factual Knowledge Recall

# 摘要

> 大型语言模型（LLMs）在众多自然语言处理（NLP）任务上展现了卓越性能，并迅速被应用于多种场景。全面评估其输出内容的真实性极为重要，以应对生成幻觉这一棘手问题。本研究着眼于分析LLMs回忆预训练阶段学习到的事实知识的能力及其影响因素。为此，我们开发了FACT-BENCH，一个涵盖20个领域、134种属性类型、3种答案类型以及不同知识知名度水平的基准测试。我们对10个模型家族的31个模型进行了全面评估，揭示了它们的优势与不足。研究发现，指令调整对知识回忆有负面影响，因为仅经过预训练的模型总是比经过指令调整的模型表现更好；同时，模型规模的扩大对性能有积极影响，大型模型在所有家族中均优于小型模型。但即便是GPT-4的最佳表现，与最佳性能仍有较大差距。我们还探讨了上下文示例在反事实演示中的作用，发现这会导致大型模型的事实知识回忆能力显著下降。进一步分析表明，这种下降是由于与模型已知知识相冲突的示例以及这类示例的数量所导致的。最后，我们在已知和未知知识的不同设置下对LLaMA-7B进行了微调，发现针对模型已知知识的微调尤其有益，其性能一致超越了针对未知和混合知识进行的微调。我们将向公众开放这一基准测试。

> Large language models (LLMs) have shown remarkable performance on a variety of NLP tasks, and are being rapidly adopted in a wide range of use cases. It is therefore of vital importance to holistically evaluate the factuality of their generated outputs, as hallucinations remain a challenging issue.
  In this work, we focus on assessing LLMs' ability to recall factual knowledge learned from pretraining, and the factors that affect this ability. To that end, we construct FACT-BENCH, a representative benchmark covering 20 domains, 134 property types, 3 answer types, and different knowledge popularity levels. We benchmark 31 models from 10 model families and provide a holistic assessment of their strengths and weaknesses. We observe that instruction-tuning hurts knowledge recall, as pretraining-only models consistently outperform their instruction-tuned counterparts, and positive effects of model scaling, as larger models outperform smaller ones for all model families. However, the best performance from GPT-4 still represents a large gap with the upper-bound. We additionally study the role of in-context exemplars using counterfactual demonstrations, which lead to significant degradation of factual knowledge recall for large models. By further decoupling model known and unknown knowledge, we find the degradation is attributed to exemplars that contradict a model's known knowledge, as well as the number of such exemplars. Lastly, we fine-tune LLaMA-7B in different settings of known and unknown knowledge. In particular, fine-tuning on a model's known knowledge is beneficial, and consistently outperforms fine-tuning on unknown and mixed knowledge. We will make our benchmark publicly available.

[Arxiv](https://arxiv.org/abs/2404.16164)