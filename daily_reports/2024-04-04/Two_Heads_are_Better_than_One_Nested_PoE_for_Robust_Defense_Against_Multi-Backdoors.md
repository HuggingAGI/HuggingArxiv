# 双脑并用，胜于单机：采用嵌套PoE策略，构筑抵御多重后门攻击的坚实防线。
`模型安全`
> 数据投毒后门攻击可能引发大型语言模型的不良行为，因此构筑有效防线变得尤为关键。现行的防御手段多基于攻击者使用单一触发器的假设，而对于多元并发触发器的防御，尚缺乏普适性的策略和深入研究。本文提出了一种名为嵌套专家乘积（NPoE）的新型防御架构，该架构在专家乘积（PoE）框架内融入专家混合（MoE）机制，专门针对多类触发器进行综合防御。在NPoE的训练过程中，主模型与多个小型专家模型共同训练，后者负责学习后门触发器的特征。到了推理阶段，则仅依赖主模型。实验表明，NPoE在情感分析、仇恨言论识别和问题分类等任务中，能够有效地抵御各种单一或混合的触发器攻击。得益于NPoE中MoE结构的灵活性，该防御框架有望进一步扩展，以应对更多类型的攻击场景。
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02356/fig1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02356/Framework_paper2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02356/trigger-only.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02356/trigger_layers_sns.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02356/poison_rate_sns.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02356/alphas_sns.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02356/gate_layers_sns.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02356/num_experts.png)
