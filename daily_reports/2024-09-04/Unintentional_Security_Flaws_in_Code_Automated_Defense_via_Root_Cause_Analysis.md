# 代码中潜藏的安全漏洞，可通过根本原因分析实现自动化防御。
发布时间：2024年08月30日

`代码编写`
> Unintentional Security Flaws in Code: Automated Defense via Root Cause Analysis
>
> 软件安全问题依然严峻，尤其是初级开发人员因缺乏全面的安全知识而参与代码编写时。尽管有工具辅助编写安全代码，但其修复漏洞的实际效果尚未明确。现有方法多聚焦于漏洞的分类与定位，却未明确指出问题根源代码段，这对开发者修复漏洞至关重要。为此，我们开展了一项研究，评估现有方法在帮助初级开发者确保代码安全方面的有效性。研究发现，当前工具仅能提升36.2%的代码安全性。问卷调查显示，开发者面临的主要难题之一是不清楚漏洞根源代码。基于此，我们开发了T5-RCGCN工具包，结合T5语言模型与图卷积网络进行漏洞分类与定位，并利用DeepLiftSHAP识别根源代码段。在三个数据集上对56名初级开发者进行测试，结果显示代码安全性提升了28.9%，且开发者对漏洞根源的理解加深，独立确保代码安全的能力提高了17.0%。这表明该工具不仅能在短期内提升安全性，还能促进开发者技能的长期成长。
>
> https://arxiv.org/abs/2409.00199

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2409.00199](https://arxiv.org/abs/2409.00199)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)