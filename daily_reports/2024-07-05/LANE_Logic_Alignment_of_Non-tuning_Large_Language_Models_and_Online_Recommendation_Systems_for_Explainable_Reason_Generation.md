# LANE：实现非调优大型语言模型与在线推荐系统的逻辑对齐，旨在生成可解释的推理。
发布时间：2024年07月03日

`推荐系统`
> LANE: Logic Alignment of Non-tuning Large Language Models and Online Recommendation Systems for Explainable Reason Generation
>
> 推荐系统的透明度是提升用户信任与满意度的关键。借助大型语言模型（LLM），我们迎来了全面推荐逻辑生成的新契机。然而，现有研究在为推荐任务微调LLM时，面临高昂计算成本及与现有系统对齐的难题，这限制了如GPT-4等专有/闭源LLM模型的应用前景。为此，我们创新性地提出了LANE策略，无需额外微调即可实现LLM与在线推荐系统的无缝对接，既降低了成本，又增强了可解释性。该策略通过语义嵌入、零-shot提示下的用户多偏好提取、语义对齐及思维链（CoT）提示下的可解释推荐生成等关键环节，确保了用户偏好与候选项目的语义一致性，从而提供连贯且贴合用户需求的推荐。实验结果显示，我们的方法不仅保障了推荐质量，更以直观易懂的方式呈现了推荐逻辑，赢得了用户的广泛认可。
>
> https://arxiv.org/abs/2407.02833

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02833/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02833/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02833/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02833/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02833/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02833/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02833/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02833/x8.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.02833](https://arxiv.org/abs/2407.02833)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1