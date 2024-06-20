# OpenVLA：一款开源的视觉-语言-动作融合模型
发布时间：2024年06月13日

`多模态大模型`
> OpenVLA: An Open-Source Vision-Language-Action Model
>
> 结合海量视觉-语言数据与多样化机器人演示的预训练大型策略，正革新机器人技能教学：我们不再从零开始训练，而是微调视觉-语言-动作（VLA）模型，以获得稳健且可泛化的视觉运动控制策略。但VLA在机器人领域的普及受阻，主要因为现有VLA不开放且缺乏高效微调方法。为此，我们推出了开源的OpenVLA，一个70亿参数的模型，基于97万真实世界机器人演示训练。它结合了Llama 2语言模型与融合DINOv2和SigLIP预训练特征的视觉编码器，在通用操作任务中超越了封闭模型RT-2-X 16.5%，且参数仅为后者的七分之一。我们展示了OpenVLA在多任务环境中，尤其是涉及多对象和强语言基础能力的情况下，能有效微调并显著优于从头开始的模仿学习方法。此外，我们证明了OpenVLA能在消费级GPU上通过现代低秩适应方法微调，并通过量化高效服务，不影响下游任务成功率。最后，我们发布了模型检查点、微调笔记本及PyTorch代码库，支持在Open X-Embodiment数据集上大规模训练VLA。
>
> https://arxiv.org/abs/2406.09246

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09246/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09246/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09246/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09246/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09246/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09246/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09246/rt1_robot_tasks.jpeg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09246/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09246/droid_wipe_task.jpeg)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.09246](https://arxiv.org/abs/2406.09246)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2