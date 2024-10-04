# 通过合成编辑序列训练语言模型，能显著提升代码合成的质量。

发布时间：2024年10月03日

`LLM应用` `软件开发` `人工智能`

> Training Language Models on Synthetic Edit Sequences Improves Code Synthesis

# 摘要

> 软件工程师通过编辑现有程序编写代码，而大型语言模型 (LLM) 则通过单次传递自动生成程序。这种差异部分源于开源编辑数据的稀缺。尽管高质量的代码合成指令数据已经稀少，但编辑数据更为匮乏。为此，我们开发了 LintSeq 算法，通过程序化采样无错误插入，将代码重构为一系列编辑序列。我们使用 LintSeq 将指令与程序对的数据集转换为指令与程序差异序列，并对一系列小型 LLM 进行微调，比较其在代码合成基准上的表现。结果显示，经过编辑序列微调的模型生成的程序更加多样化，显著提升了基准覆盖率。例如，在 HumanEval pass@50 上，微调后的小型 LLM 与 GPT-4 表现相当，且比基线模型高出 20%。此外，我们还预训练了小型代码理解模型，发现微调后的 150M 参数模型在代码合成方面达到了最先进水平，超越了包括 Codex 和 AlphaCode 在内的更大参数模型。

> Software engineers mainly write code by editing existing programs. In contrast, large language models (LLMs) autoregressively synthesize programs in a single pass. One explanation for this is the scarcity of open-sourced edit data. While high-quality instruction data for code synthesis is already scarce, high-quality edit data is even scarcer. To fill this gap, we develop a synthetic data generation algorithm called LintSeq. This algorithm refactors existing code into a sequence of code edits by using a linter to procedurally sample across the error-free insertions that can be used to sequentially write programs. It outputs edit sequences as text strings consisting of consecutive program diffs. To test LintSeq, we use it to refactor a dataset of instruction + program pairs into instruction + program-diff-sequence tuples. Then, we instruction finetune a series of smaller LLMs ranging from 2.6B to 14B parameters on both the re-factored and original versions of this dataset, comparing zero-shot performance on code synthesis benchmarks. We show that during repeated sampling, edit sequence finetuned models produce more diverse programs than baselines. This results in better inference-time scaling for benchmark coverage as a function of samples, i.e. the fraction of problems "pass@k" solved by any attempt given "k" tries. For example, on HumanEval pass@50, small LLMs finetuned on synthetic edit sequences are competitive with GPT-4 and outperform models finetuned on the baseline dataset by +20% (+/-3%) in absolute score. Finally, we also pretrain our own tiny LMs for code understanding. We show that finetuning tiny models on synthetic code edits results in state-of-the-art code synthesis for the on-device model class. Our 150M parameter edit sequence LM matches or outperforms code models with twice as many parameters, both with and without repeated sampling, including Codex and AlphaCode.

[Arxiv](https://arxiv.org/abs/2410.02749)