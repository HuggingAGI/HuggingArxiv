# ActiveLLM：大型语言模型驱动的主动学习，专为文本少量样本场景设计
发布时间：2024年05月17日

`动手训练`
> ActiveLLM: Large Language Model-based Active Learning for Textual Few-Shot Scenarios
>
> 主动学习通过优先处理关键实例来减少标注负担，但许多策略在初期因数据不足而效果不佳。针对这一挑战，我们推出了ActiveLLM，一种利用GPT-4、Llama 3和Mistral Large等大型语言模型的新方法，用于精准挑选学习实例。实验证明，ActiveLLM在少量样本条件下大幅提升了BERT分类器的性能，超越了传统方法和SetFit。不仅如此，ActiveLLM还适用于多样的学习场景，并能助力其他策略克服初期的数据瓶颈。我们的研究揭示，ActiveLLM是提升模型性能的强大工具，适用于多种学习环境。
>
> https://arxiv.org/abs/2405.10808

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10808/prompt_engineering.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10808/presented_examples.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10808/example_size.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10808/comparisons.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10808/iterated_querying.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10808/coldstart.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10808/prompt_engineering_appendix.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.10808](https://arxiv.org/abs/2405.10808)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 公众号回复关键词获取论文原文： 8855218418481252