# 本研究旨在通过多种策略提升 CorefUD 中多语言指代消解的性能。

发布时间：2024年08月29日

`LLM应用` `多语言技术`

> Exploring Multiple Strategies to Improve Multilingual Coreference Resolution in CorefUD

# 摘要

> 本文介绍了一种利用CorefUD 1.1数据集（涵盖12种语言的17个数据集）构建的端到端神经指代消解系统。我们首先设立了强大的基线模型，包括单语和跨语言版本，随后提出多项扩展以提升在多样语言环境下的性能，如跨语言训练、整合句法信息、优化头部词预测的Span2Head模型及高级单例建模。此外，我们还探索了头部词跨度表示和长文档建模。这些扩展显著提升了多数数据集的性能，尤其是仅头部词方法、单例建模和长文档预测。我们还进行了零样本跨语言实验，揭示了跨语言迁移在指代消解中的潜力与局限。我们的研究成果推动了多语言指代消解系统的稳健性和可扩展性发展。最终，我们的模型在CorefUD 1.1测试集上表现优异，大幅超越了CRAC 2023共享任务中的最佳模型。模型代码已公开在GitHub：\url{https://github.com/ondfa/coref-multiling}

> Coreference resolution, the task of identifying expressions in text that refer to the same entity, is a critical component in various natural language processing (NLP) applications. This paper presents our end-to-end neural coreference resolution system, utilizing the CorefUD 1.1 dataset, which spans 17 datasets across 12 languages. We first establish strong baseline models, including monolingual and cross-lingual variations, and then propose several extensions to enhance performance across diverse linguistic contexts. These extensions include cross-lingual training, incorporation of syntactic information, a Span2Head model for optimized headword prediction, and advanced singleton modeling. We also experiment with headword span representation and long-documents modeling through overlapping segments. The proposed extensions, particularly the heads-only approach, singleton modeling, and long document prediction significantly improve performance across most datasets. We also perform zero-shot cross-lingual experiments, highlighting the potential and limitations of cross-lingual transfer in coreference resolution. Our findings contribute to the development of robust and scalable coreference systems for multilingual coreference resolution. Finally, we evaluate our model on CorefUD 1.1 test set and surpass the best model from CRAC 2023 shared task of a comparable size by a large margin. Our nodel is available on GitHub: \url{https://github.com/ondfa/coref-multiling}

[Arxiv](https://arxiv.org/abs/2408.16893)