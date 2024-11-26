# 借助任务上下文来对对象可供性进行排序

发布时间：2024年11月24日

`Agent` `智能体` `多模态`

> Leverage Task Context for Object Affordance Ranking

# 摘要

> 智能体依靠基于其可供性的各类对象来完成不同任务，然而如何依照任务上下文选取恰当的对象，尚未得到充分探究。当下的研究把可供性类别里的对象视作等同，忽略了对象的可供性在不同任务语境中的优先级存在差异，这妨碍了在复杂环境中做出准确决策。为让智能体对执行任务所需的对象有更深刻的理解，我们提议借助任务上下文给对象的可供性进行排序，也就是给定复杂场景的图像以及可供性和任务上下文的文本描述，揭示任务与对象的关系，并明确检测到的对象的优先等级。为此，我们提出了一个新颖的带有任务关系挖掘模块和图组更新模块的上下文嵌入组排序框架，以深度融合任务上下文并进行全局相对关系传递。鉴于缺乏这类数据，我们构建了首个大规模面向任务的可供性排序数据集，涵盖 25 个常见任务、逾 5 万张图像以及 66 万余个对象。实验结果表明基于任务上下文的可供性学习范式可行，且我们的模型在显著排名和多模态对象检测领域优于前沿模型。源代码和数据集将向公众开放。

> Intelligent agents accomplish different tasks by utilizing various objects based on their affordance, but how to select appropriate objects according to task context is not well-explored. Current studies treat objects within the affordance category as equivalent, ignoring that object affordances vary in priority with different task contexts, hindering accurate decision-making in complex environments. To enable agents to develop a deeper understanding of the objects required to perform tasks, we propose to leverage task context for object affordance ranking, i.e., given image of a complex scene and the textual description of the affordance and task context, revealing task-object relationships and clarifying the priority rank of detected objects. To this end, we propose a novel Context-embed Group Ranking Framework with task relation mining module and graph group update module to deeply integrate task context and perform global relative relationship transmission. Due to the lack of such data, we construct the first large-scale task-oriented affordance ranking dataset with 25 common tasks, over 50k images and more than 661k objects. Experimental results demonstrate the feasibility of the task context based affordance learning paradigm and the superiority of our model over state-of-the-art models in the fields of saliency ranking and multimodal object detection. The source code and dataset will be made available to the public.

[Arxiv](https://arxiv.org/abs/2411.16082)