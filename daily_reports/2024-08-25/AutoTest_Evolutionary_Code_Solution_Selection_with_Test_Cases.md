# AutoTest：借助测试用例，进化选择代码解决方案
发布时间：2024年08月22日

`代码编写`
> AutoTest: Evolutionary Code Solution Selection with Test Cases
>
> 随着代码生成技术的进步，从众多候选方案中挑选出最佳代码解决方案变得尤为关键。本研究引入AutoTest技术，它巧妙结合自动化测试用例生成与代码执行，借助进化遗传算法精炼选择流程。AutoTest首先借助codegen-16B等大型预训练模型，提供代码方案及对应测试用例。随后，通过执行这些方案并评估其在测试用例上的表现，形成共识集。借助进化遗传算法的选择、变异与交叉机制，结合alpha和beta参数的微调，实现精准排序，最终选出最优代码方案。在HumanEval基准测试中，AutoTest表现卓越，该数据集涵盖164个编程难题，AutoTest在pass@1评分上较基线方法提升了约10%。
>
> https://arxiv.org/abs/2408.12125

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.12125](https://arxiv.org/abs/2408.12125)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)