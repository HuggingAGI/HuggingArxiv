# 本研究提出一种无需训练的视频车牌追踪与识别框架，仅需一次学习即可实现。
发布时间：2024年08月11日

`多模态大模型`
> A Training-Free Framework for Video License Plate Tracking and Recognition with Only One-Shot
>
> 传统车牌识别模型受限于封闭数据集，难以应对各地车牌格式的多样性。而大规模预训练模型则展现出卓越的泛化能力，支持少样本和零样本学习。为此，我们推出了OneShotLP框架，该框架无需训练，利用先进模型实现视频车牌检测与识别。方法从视频首帧的车牌位置出发，通过点跟踪模块在后续帧中持续追踪，形成提示轨迹。这些提示被送入分割模块，利用大型分割模型生成车牌区域的局部掩码。随后，多模态大型语言模型对分割区域进行处理，确保车牌识别的准确性。OneShotLP不仅无需大量训练数据，还能适应多种车牌样式，展现出显著优势。在UFPR-ALPR和SSIG-SegPlate数据集上的实验结果表明，我们的方法在准确性上超越了传统方法，凸显了预训练模型在智能交通系统中多样化应用的潜力。代码已公开，详见https://github.com/Dinghaoxuan/OneShotLP。
>
> https://arxiv.org/abs/2408.05729

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05729/track014101.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05729/track014108.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05729/track014116.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05729/track014130.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05729/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05729/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05729/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05729/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.05729](https://arxiv.org/abs/2408.05729)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)