# WILBUR：为打造强大精准的网络代理，采用自适应式上下文学习方法

发布时间：2024年04月08日

`Agent` `网络代理` `自动化测试`

> WILBUR: Adaptive In-Context Learning for Robust and Accurate Web Agents

# 摘要

> 在网络代理研究的领域里，同时达到泛化能力和精确度是个难题。网站结构多变，导致现有方法屡屡碰壁。而且，传统的微调和上下文学习技术难以跨网站通用。我们提出了Wilbur方案，它采用可微分排序模型和创新的指令合成技术，以前次任务执行的示例来优化填充大型语言模型的提示。为了提高整体成功率，我们还设计了一种智能回溯机制，它能够识别并纠正错误。此外，我们的排序模型可以通过生成性自动课程的数据进行训练，该课程能够从大型语言模型中选取具有代表性的样本，自动执行代理任务并评估结果，无需人工注释。Wilbur在WebVoyager基准测试中取得了领先成果，比纯文本模型平均提升了8%，在某些网站上提升幅度高达36%。即便只接收文本输入，Wilbur在该基准测试中的得分也接近强大的多模态模型，仅低5%。深入分析发现，许多失败案例实际上源于网络操作的技术挑战。

> In the realm of web agent research, achieving both generalization and accuracy remains a challenging problem. Due to high variance in website structure, existing approaches often fail. Moreover, existing fine-tuning and in-context learning techniques fail to generalize across multiple websites. We introduce Wilbur, an approach that uses a differentiable ranking model and a novel instruction synthesis technique to optimally populate a black-box large language model's prompt with task demonstrations from previous runs. To maximize end-to-end success rates, we also propose an intelligent backtracking mechanism that learns and recovers from its mistakes. Finally, we show that our ranking model can be trained on data from a generative auto-curriculum which samples representative goals from an LLM, runs the agent, and automatically evaluates it, with no manual annotation. Wilbur achieves state-of-the-art results on the WebVoyager benchmark, beating text-only models by 8% overall, and up to 36% on certain websites. On the same benchmark, Wilbur is within 5% of a strong multi-modal model despite only receiving textual inputs, and further analysis reveals a substantial number of failures are due to engineering challenges of operating the web.

![WILBUR：为打造强大精准的网络代理，采用自适应式上下文学习方法](../../../paper_images/2404.05902/x1.png)

![WILBUR：为打造强大精准的网络代理，采用自适应式上下文学习方法](../../../paper_images/2404.05902/x2.png)

[Arxiv](https://arxiv.org/abs/2404.05902)