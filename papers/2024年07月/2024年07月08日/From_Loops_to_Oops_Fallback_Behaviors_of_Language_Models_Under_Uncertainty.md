# 当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。

发布时间：2024年07月08日

`LLM理论` `人工智能`

> From Loops to Oops: Fallback Behaviors of Language Models Under Uncertainty

# 摘要

> 大型语言模型（LLM）常出现幻觉和序列重复等不良行为。我们将其视为模型在不确定性下的回退，并探究其关联。我们将这些行为分为序列重复、退化文本和幻觉，并在不同预训练程度和参数量的模型中深入分析。实验显示，LLM越先进（训练更多、参数更多、指令调优），其回退行为依次从序列重复转为退化文本，再到幻觉。即使在最佳模型中，随着不确定性上升，生成顺序也从幻觉变为退化文本，最终是序列重复。此外，我们发现随机采样等解码技术虽能减轻序列重复，却可能增加难以察觉的幻觉。

> Large language models (LLMs) often exhibit undesirable behaviors, such as hallucinations and sequence repetitions. We propose to view these behaviors as fallbacks that models exhibit under uncertainty, and investigate the connection between them. We categorize fallback behaviors -- sequence repetitions, degenerate text, and hallucinations -- and extensively analyze them in models from the same family that differ by the amount of pretraining tokens, parameter count, or the inclusion of instruction-following training. Our experiments reveal a clear and consistent ordering of fallback behaviors, across all these axes: the more advanced an LLM is (i.e., trained on more tokens, has more parameters, or instruction-tuned), its fallback behavior shifts from sequence repetitions, to degenerate text, and then to hallucinations. Moreover, the same ordering is observed throughout a single generation, even for the best-performing models; as uncertainty increases, models shift from generating hallucinations to producing degenerate text and then sequence repetitions. Lastly, we demonstrate that while common decoding techniques, such as random sampling, might alleviate some unwanted behaviors like sequence repetitions, they increase harder-to-detect hallucinations.

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x1.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x2.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x3.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x4.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x5.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x6.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x7.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x8.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x9.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x10.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x11.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x12.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x13.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x14.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x15.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x16.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x17.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x18.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x19.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x20.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x21.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x22.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x23.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x24.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x25.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x26.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x27.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x28.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x29.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x30.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x31.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x32.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x33.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x34.png)

![当不确定性来袭，语言模型从循环往复走向“哎呀”时刻，探索其在未知中的回退策略。](../../../paper_images/2407.06071/x35.png)

[Arxiv](https://arxiv.org/abs/2407.06071)