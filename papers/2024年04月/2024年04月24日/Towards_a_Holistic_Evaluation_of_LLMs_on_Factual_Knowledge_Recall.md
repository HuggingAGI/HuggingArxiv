# 全面评估大型语言模型在事实知识回忆上的表现

发布时间：2024年04月24日

`LLM应用` `基准测试`

> Towards a Holistic Evaluation of LLMs on Factual Knowledge Recall

# 摘要

> 大型语言模型（LLMs）在众多自然语言处理（NLP）任务上展现了卓越性能，并迅速被应用于多种场景。鉴于幻觉问题依然棘手，全面评估LLMs生成内容的真实性显得尤为关键。本研究着眼于LLMs对预训练阶段学习到的事实知识的记忆力，以及影响这一能力的多种因素。我们创建了FACT-BENCH，一个涵盖20个领域、134种属性类型、3种答案类型和不同知识普及度的基准测试。通过对比10个模型家族的31个模型，我们进行了全面的优劣分析。研究发现，指令调整对知识记忆有负面影响，因为仅经过预训练的模型总是比经过指令调整的模型表现更好；同时，模型规模的扩大对性能有积极作用，即在所有模型家族中，较大模型的性能超越了较小模型。尽管如此，GPT-4的最佳表现与最佳可能性能之间仍有较大差距。我们还探讨了上下文示例在反事实演示中的作用，发现这会导致大型模型的事实知识记忆能力显著下降。进一步分析表明，这种下降归咎于与模型已知知识相冲突的示例，以及这类示例的数量。最后，我们在已知和未知知识的不同设置下对LLaMA-7B进行了微调，发现针对模型已知知识的微调尤其有效，其性能一致优于针对未知和混合知识的微调。我们将向公众开放这一基准测试。

> Large language models (LLMs) have shown remarkable performance on a variety of NLP tasks, and are being rapidly adopted in a wide range of use cases. It is therefore of vital importance to holistically evaluate the factuality of their generated outputs, as hallucinations remain a challenging issue.
  In this work, we focus on assessing LLMs' ability to recall factual knowledge learned from pretraining, and the factors that affect this ability. To that end, we construct FACT-BENCH, a representative benchmark covering 20 domains, 134 property types, 3 answer types, and different knowledge popularity levels. We benchmark 31 models from 10 model families and provide a holistic assessment of their strengths and weaknesses. We observe that instruction-tuning hurts knowledge recall, as pretraining-only models consistently outperform their instruction-tuned counterparts, and positive effects of model scaling, as larger models outperform smaller ones for all model families. However, the best performance from GPT-4 still represents a large gap with the upper-bound. We additionally study the role of in-context exemplars using counterfactual demonstrations, which lead to significant degradation of factual knowledge recall for large models. By further decoupling model known and unknown knowledge, we find the degradation is attributed to exemplars that contradict a model's known knowledge, as well as the number of such exemplars. Lastly, we fine-tune LLaMA-7B in different settings of known and unknown knowledge. In particular, fine-tuning on a model's known knowledge is beneficial, and consistently outperforms fine-tuning on unknown and mixed knowledge. We will make our benchmark publicly available.

[Arxiv](https://arxiv.org/abs/2404.16164)