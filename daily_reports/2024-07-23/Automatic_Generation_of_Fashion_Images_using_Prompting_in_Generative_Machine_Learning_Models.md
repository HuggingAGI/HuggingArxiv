# 借助生成模型中的提示技术，自动创作时尚图像
发布时间：2024年07月20日

`多模态大模型`
> Automatic Generation of Fashion Images using Prompting in Generative Machine Learning Models
>
> 人工智能的兴起为时尚界带来了革命性的变革，重新定义了创造与创新的新境界。本研究采用两种大型语言模型及一款稳定扩散模型，探索生成个性化时尚描述的方法。我们突破传统，聚焦于零-shot、少-shot学习及思维链（CoT）等提示技术，丰富了色彩与纹理的多样性，提升了作品的多元性。核心方法为检索增强生成（RAG），通过融合时尚领域的智慧，确保作品的时代感。评估方面，我们结合CLIPscore等量化指标与人类的主观评价，凸显了作品在创意、连贯性与美感上的卓越表现。在众多参与者中，RAG与少-shot学习技术因其生成的描述更具相关性与吸引力而备受推崇。项目代码已公开于https://github.com/georgiarg/AutoFashion。
>
> https://arxiv.org/abs/2407.14944

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/Baseline.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/few-shot.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/CoT-model.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/RAG.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/ageStats.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/englishStats.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/occuStats.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/relatArtStats.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/fashPartStats.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/AIPartStats.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/1stexp.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/exAbn.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/inspAbno.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/2ndexp.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/compComprehensib.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/compCoherence.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/compOutOccas.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/compOutType.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/compOutStyle.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/compColOccas.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/compColType.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/compColStyle.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/compTexOccas.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/compTexType.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/compTexStyle.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/3rd.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14944/myresults1.jpg)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.14944](https://arxiv.org/abs/2407.14944)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1