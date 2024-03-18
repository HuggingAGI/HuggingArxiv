# [CLongEval —— 专为评估大型语言模型在处理长文本情境能力而设的中文评测基准]

发布时间：2024年03月06日

`LLM应用`

> CLongEval: A Chinese Benchmark for Evaluating Long-Context Large Language Models

> 近年来，科研人员致力于打造具有强大长上下文处理能力的大型语言模型，并成功推出了擅长中文的长上下文LLMs。但受限于缺乏统一的评估标准，这类模型的实际性能仍有待充分考察。为此，我们创新推出了一项名为CLongEval的综合评测基准，专门针对长上下文LLMs进行评估。该基准具有显著的三大特色：一是数据丰富多元，整合了涵盖7大任务的7,267个实例；二是适用面广，能够适应上下文窗口从1K至100K的各类模型；三是评价精准度高，额外包含了超2,000组人工标注的问题与答案配对。通过CLongEval，我们对6款开源长上下文LLMs以及2款兼具长上下文技能和卓越中文表现的商业领先模型进行了全方位测评，并根据实测数据进行了深度剖析，力求揭示长上下文环境下模型所面临的核心挑战。未来我们会公开发布相关的数据集、评估脚本以及各模型的输出结果。

> Developing Large Language Models (LLMs) with robust long-context capabilities has been the recent research focus, resulting in the emergence of long-context LLMs proficient in Chinese. However, the evaluation of these models remains underdeveloped due to a lack of benchmarks. To address this gap, we present CLongEval, a comprehensive Chinese benchmark for evaluating long-context LLMs. CLongEval is characterized by three key features: (1) Sufficient data volume, comprising 7 distinct tasks and 7,267 examples; (2) Broad applicability, accommodating to models with context windows size from 1K to 100K; (3) High quality, with over 2,000 manually annotated question-answer pairs in addition to the automatically constructed labels. With CLongEval, we undertake a comprehensive assessment of 6 open-source long-context LLMs and 2 leading commercial counterparts that feature both long-context abilities and proficiency in Chinese. We also provide in-depth analysis based on the empirical results, trying to shed light on the critical capabilities that present challenges in long-context settings. The dataset, evaluation scripts, and model outputs will be released.

[Arxiv](https://arxiv.org/abs/2403.03514)