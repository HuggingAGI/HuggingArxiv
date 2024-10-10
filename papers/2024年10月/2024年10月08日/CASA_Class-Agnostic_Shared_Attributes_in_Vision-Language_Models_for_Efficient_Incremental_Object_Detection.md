# CASA：视觉-语言模型中，类不可知的共享属性助力高效增量对象检测

发布时间：2024年10月08日

`LLM应用` `计算机视觉` `机器学习`

> CASA: Class-Agnostic Shared Attributes in Vision-Language Models for Efficient Incremental Object Detection

# 摘要

> 增量对象检测 (IOD) 面临背景偏移的挑战，即序列数据中的背景类别可能包含先前学习或未来的类别。受 CLIP 等视觉语言基础模型的启发，我们提出了一种利用这些模型中的共享属性进行 IOD 的新方法。我们构建了一个类无关共享属性基 (CASA)，以捕捉增量类之间的共同语义信息。具体来说，我们利用大型语言模型生成候选文本属性，并根据当前训练数据选择最相关的属性，记录在属性分配矩阵中。对于后续任务，我们冻结保留的属性，并继续从剩余候选中选择，同时更新属性分配矩阵。我们采用 OWL-ViT 作为基线，保留预训练模型的原始参数。通过参数高效微调，我们的方法仅增加了 0.7% 的参数存储，显著提升了 IOD 的可扩展性和适应性。在 COCO 数据集上的广泛实验证明了我们方法的领先性能。

> Incremental object detection (IOD) is challenged by background shift, where background categories in sequential data may include previously learned or future classes. Inspired by the vision-language foundation models such as CLIP, these models capture shared attributes from extensive image-text paired data during pre-training. We propose a novel method utilizing attributes in vision-language foundation models for incremental object detection. Our method constructs a Class-Agnostic Shared Attribute base (CASA) to capture common semantic information among incremental classes. Specifically, we utilize large language models to generate candidate textual attributes and select the most relevant ones based on current training data, recording their significance in an attribute assignment matrix. For subsequent tasks, we freeze the retained attributes and continue selecting from the remaining candidates while updating the attribute assignment matrix accordingly. Furthermore, we employ OWL-ViT as our baseline, preserving the original parameters of the pre-trained foundation model. Our method adds only 0.7% to parameter storage through parameter-efficient fine-tuning to significantly enhance the scalability and adaptability of IOD. Extensive two-phase and multi-phase experiments on the COCO dataset demonstrate the state-of-the-art performance of our proposed method.

[Arxiv](https://arxiv.org/abs/2410.05804)