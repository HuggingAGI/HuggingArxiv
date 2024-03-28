# 通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。

发布时间：2024年03月21日

`Agent` `机器人` `导航系统`

> Leveraging Large Language Model-based Room-Object Relationships Knowledge for Enhancing Multimodal-Input Object Goal Navigation

# 摘要

> 目标导向导航作为具身导航的核心技术难题，要求智能体在未曾探索过的环境中找到指定类别物体的目标实例。尽管针对这一问题的研究已深入探讨了端到端及基于模块的数据驱动方案，但如何让智能体凭借感知智慧高效理解环境、媲美人类执行目标导向导航仍是一项艰巨挑战。近期，大型语言模型因其卓越的知识抽取与融合能力，在此任务中崭露头角。为此，我们创新性地设计了一种基于数据驱动且模块化的解决方案，并在融入了由大型语言模型提炼出的物体与房间间常识关系知识的大数据集上进行训练。我们采用多通道 Swin-Unet 结构进行多模态输入下的多任务学习。实验在 Habitat 模拟器中表明，相较于基准方法，我们的框架在衡量效率的关键指标 SPL（按路径长度加权的成功率）上平均提升了10.6%。而在实际演示中，这一新方法成功展示了通过穿梭于多个房间来高效完成目标导向导航任务的能力。欲知更多细节及真实场景演示，请访问我们的项目主页（https://sunleyuan.github.io/ObjectNav）。

> Object-goal navigation is a crucial engineering task for the community of embodied navigation; it involves navigating to an instance of a specified object category within unseen environments. Although extensive investigations have been conducted on both end-to-end and modular-based, data-driven approaches, fully enabling an agent to comprehend the environment through perceptual knowledge and perform object-goal navigation as efficiently as humans remains a significant challenge. Recently, large language models have shown potential in this task, thanks to their powerful capabilities for knowledge extraction and integration. In this study, we propose a data-driven, modular-based approach, trained on a dataset that incorporates common-sense knowledge of object-to-room relationships extracted from a large language model. We utilize the multi-channel Swin-Unet architecture to conduct multi-task learning incorporating with multimodal inputs. The results in the Habitat simulator demonstrate that our framework outperforms the baseline by an average of 10.6% in the efficiency metric, Success weighted by Path Length (SPL). The real-world demonstration shows that the proposed approach can efficiently conduct this task by traversing several rooms. For more details and real-world demonstrations, please check our project webpage (https://sunleyuan.github.io/ObjectNav).

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x1.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x2.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x3.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x4.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x5.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x6.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x7.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x8.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x9.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x10.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x11.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x12.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x13.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x14.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x15.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x16.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x17.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x18.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x19.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x20.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x21.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x22.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x23.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x24.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x25.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x26.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x27.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x28.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x29.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x30.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x31.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x32.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x33.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x34.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x35.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x36.png)

![通过汲取大型语言模型中蕴含的房间与物体间关系知识，我们致力于提升多模态输入下的目标对象导航能力。](../../../paper_images/2403.14163/x37.png)

[Arxiv](https://arxiv.org/abs/2403.14163)