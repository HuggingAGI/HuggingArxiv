# FiST框架：金融风格转换中的幻觉与创造力调控

发布时间：2024年08月09日

`LLM应用` `财务报告`

> FiST-Financial Style Transfer with Hallucination and Creativity Control Framework

# 摘要

> 利用通用大型语言模型生成财务报告时，常遇到复合句缺失和幻觉现象两大难题。尽管采用了先进的提示工程和RAG技术，写作风格差异仍难以克服。为此，我们设计了一个创新的两阶段微调流程：首先将公共财务报告转化为提示-完成格式，再通过简易LLM提示进行增强，最终实现仅需少量指令和表格数据即可生成部分财务报告。该微调框架不仅使正确答案数量翻倍，幻觉现象减少逾半，还显著降低了模型的困惑度，提升了ROUGE、TER和BLEU评分，增强了创造性与知识密度，同时降低了困惑度和交叉熵。

> Financial report generation using general purpose large language models pose two major challenges, including the lack of compound sentences and hallucinations. Advanced prompt engineering and retrieval augmented generation (RAG) techniques are incapable of curing the writing style discrepancies. In this work we propose a novel two-stage fine-tuning process wherein public domain financial reports are processed into prompt-completions and augmented using simple LLM prompts to then enable sectional financial report generation using minimal instructions and tabular data inputs. Our proposed fine-tuning framework results doubles the number of correct questions answers and reduces hallucinations by over 50%. Additionally, the two-stage fine tuned models have lower perplexity, improved ROUGE, TER and BLEU scores, higher creativity and knowledge density with lower uncertainty and cross entropy.

[Arxiv](https://arxiv.org/abs/2408.05365)