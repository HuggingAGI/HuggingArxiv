# 重新审视数据合成：一份附带解释的教师模型训练秘籍

发布时间：2024年10月27日

`LLM应用` `语言模型` `数据生成`

> Rethinking Data Synthesis: A Teacher Model Training Recipe with Interpretation

# 摘要

> 近期大型语言模型（LLM）训练的新进展凸显了对多元、高质量指令数据的需求。近来，不少研究在探索利用LLM生成合成数据。然而，它们主要着眼于采用标准监督指令微调模型的提示工程，这存在一个根本性局限：这些模型是针对一般性问答/问题解决进行优化的，而非数据生成。我们通过探究如何专门训练用于数据生成的模型，提出了名为	extbf{NOMAD}的范式转变，表明此任务与训练传统LM有显著差异。我们明确了两个关键因素：无提示掩码训练和恰当的训练集规模选取。我们的NOMAD方法相比基线有大幅提升，在TriviaQA中实现了超过4％的增益，在GSM8K中实现了超过2％的增益，且训练数据有限。最后，我们从“相关性”和“新颖性”的视角解读合成数据，提供了新的见解。

> Recent advances in large language model (LLM) training have highlighted the need for diverse, high-quality instruction data. Recently, many works are exploring synthetic data generation using LLMs. However, they primarily focus on prompt engineering with standard supervised instruction-finetuned models, which contains a fundamental limitation: these models are optimized for general question-answering/problem-solving rather than data generation. We propose a paradigm shift named \textbf{NOMAD} by investigating how to specifically train models for data generation, demonstrating that this task differs significantly from training a classical LM. We identify two key factors: no-prompt-masked training and proper training set size selection. Our method, NOMAD, shows substantial improvements over baselines, achieving >4\% gains in TriviaQA and >2\% in GSM8K with limited training data. Finally, we offer new insights by interpreting synthetic data through the lenses of "relevance" and "novelty".

[Arxiv](https://arxiv.org/abs/2410.20362)