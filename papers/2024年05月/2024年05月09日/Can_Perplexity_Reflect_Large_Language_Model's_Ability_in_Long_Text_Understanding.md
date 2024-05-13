# 大型语言模型的困惑度是否是其长文本理解能力的晴雨表？

发布时间：2024年05月09日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在处理长文本时的性能评估问题，特别是对困惑度（PPL）这一指标的局限性进行了分析。它指出PPL并不能全面反映模型对长文本深刻理解的能力，而是更多地反映了模型对局部信息的把握。这种对评估指标的深入分析和对模型性能理解的探讨，属于对LLMs理论层面的研究，因此归类为LLM理论。` `语言模型评估`

> Can Perplexity Reflect Large Language Model's Ability in Long Text Understanding?

# 摘要

> 最新研究表明，大型语言模型（LLMs）能够驾驭长篇大论。然而，多数研究仅以语言建模任务中的困惑度（PPL）作为标尺来衡量其长文本处理能力，这并不全面。我们的研究发现，PPL与LLMs对长文本的深刻理解并无直接关联，它更多地反映了模型对局部信息的把握，而非长距离依赖的捕捉。因此，仅凭PPL来断定模型能驾驭长文本，未免过于片面。PPL的这一局限性也能解释为何某些模型，如采用ALiBi位置方法的模型，在文本外推方面表现卓越。在评估模型对长文本的处理能力时，我们应更加审慎，避免过度依赖PPL这一指标。

> Recent studies have shown that Large Language Models (LLMs) have the potential to process extremely long text. Many works only evaluate LLMs' long-text processing ability on the language modeling task, with perplexity (PPL) as the evaluation metric. However, in our study, we find that there is no correlation between PPL and LLMs' long-text understanding ability. Besides, PPL may only reflect the model's ability to model local information instead of catching long-range dependency. Therefore, only using PPL to prove the model could process long text is inappropriate. The local focus feature of PPL could also explain some existing phenomena, such as the great extrapolation ability of the position method ALiBi. When evaluating a model's ability in long text, we might pay more attention to PPL's limitation and avoid overly relying on it.

[Arxiv](https://arxiv.org/abs/2405.06105)