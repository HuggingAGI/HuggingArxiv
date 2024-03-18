# 针对大型语言模型，本研究案例展示了如何高效地以最小化人工投入的方式快速构建高质量的指令数据集及评估基准，此方法特别适用于日语场景。

发布时间：2024年03月06日

`LLM应用`

> Rapidly Developing High-quality Instruction Data and Evaluation Benchmark for Large Language Models with Minimal Human Effort: A Case Study on Japanese

> 针对大型语言模型服务所需的指令数据及评估标准制定，往往需要投入大量人力进行标注，这一挑战在迅速构建类似日语等非英文资源时更为凸显。不同于传统的直接将英文资源翻译为日语的做法（如日本-羊驼项目），我们创新性地提出了基于 GPT-4 的高效自动生成策略。我们先将少量英文指令精心翻译并本土化为日语文本，再由 GPT-4 根据这些高质量的日语示例自动生成更多的日语指令数据。此外，我们巧妙运用 GPT-4 创建了一个涵盖八大类别、共计80个问题的评估基准，无需依赖人工参照即可自动评估 LLMs 的回复品质。实验结果显示，在三种不同的预训练基础模型上，经由我们基于 GPT-4 自我指导数据微调后的模型全面超越了日本-羊驼项目的性能。其中，LLaMA 13B 模型借助我们的 GPT-4 数据，更以54.37\%的胜率力压 GPT-3.5（Davinci-003）。进一步的人工评估验证了 GPT-4 评估结果与人类判断的一致性。目前，我们已公开发布这套高质量的指令数据集和评估基准。

> The creation of instruction data and evaluation benchmarks for serving Large language models often involves enormous human annotation. This issue becomes particularly pronounced when rapidly developing such resources for a non-English language like Japanese. Instead of following the popular practice of directly translating existing English resources into Japanese (e.g., Japanese-Alpaca), we propose an efficient self-instruct method based on GPT-4. We first translate a small amount of English instructions into Japanese and post-edit them to obtain native-level quality. GPT-4 then utilizes them as demonstrations to automatically generate Japanese instruction data. We also construct an evaluation benchmark containing 80 questions across 8 categories, using GPT-4 to automatically assess the response quality of LLMs without human references. The empirical results suggest that the models fine-tuned on our GPT-4 self-instruct data significantly outperformed the Japanese-Alpaca across all three base pre-trained models. Our GPT-4 self-instruct data allowed the LLaMA 13B model to defeat GPT-3.5 (Davinci-003) with a 54.37\% win-rate. The human evaluation exhibits the consistency between GPT-4's assessments and human preference. Our high-quality instruction data and evaluation benchmark have been released here.

[Arxiv](https://arxiv.org/abs/2403.03690)