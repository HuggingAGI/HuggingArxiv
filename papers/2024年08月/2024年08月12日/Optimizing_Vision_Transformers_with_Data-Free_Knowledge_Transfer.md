# 无数据知识转移优化视觉变换器

发布时间：2024年08月12日

`LLM理论` `计算机视觉` `物体检测`

> Optimizing Vision Transformers with Data-Free Knowledge Transfer

# 摘要

> Transformer在NLP任务中的卓越表现使其取代了传统CNN，这归功于自注意力机制的高效与准确。这一成就激发了在计算机视觉领域应用Transformer的探索，以提升长期语义理解。视觉Transformer（ViTs）因其捕捉远距离依赖的能力，在视觉任务中大放异彩。现代ViTs如DeiT，能同时汲取图像的全局语义与局部细节，性能直逼传统CNN。但高光背后，庞大的参数导致高昂的计算成本，限制了其在资源受限设备上的应用。同时，ViTs对大量训练数据的依赖也是一个难题。为此，我们面临两大挑战：模型计算需求与数据训练量。为应对这些挑战，我们提出无数据知识蒸馏技术来压缩ViT模型，并在物体检测任务中验证其效能。实验表明，无数据知识蒸馏是解决这些问题的有效途径，使得ViTs能在资源较少的设备上得以应用。

> The groundbreaking performance of transformers in Natural Language Processing (NLP) tasks has led to their replacement of traditional Convolutional Neural Networks (CNNs), owing to the efficiency and accuracy achieved through the self-attention mechanism. This success has inspired researchers to explore the use of transformers in computer vision tasks to attain enhanced long-term semantic awareness. Vision transformers (ViTs) have excelled in various computer vision tasks due to their superior ability to capture long-distance dependencies using the self-attention mechanism. Contemporary ViTs like Data Efficient Transformers (DeiT) can effectively learn both global semantic information and local texture information from images, achieving performance comparable to traditional CNNs. However, their impressive performance comes with a high computational cost due to very large number of parameters, hindering their deployment on devices with limited resources like smartphones, cameras, drones etc. Additionally, ViTs require a large amount of data for training to achieve performance comparable to benchmark CNN models. Therefore, we identified two key challenges in deploying ViTs on smaller form factor devices: the high computational requirements of large models and the need for extensive training data. As a solution to these challenges, we propose compressing large ViT models using Knowledge Distillation (KD), which is implemented data-free to circumvent limitations related to data availability. Additionally, we conducted experiments on object detection within the same environment in addition to classification tasks. Based on our analysis, we found that datafree knowledge distillation is an effective method to overcome both issues, enabling the deployment of ViTs on less resourceconstrained devices.

[Arxiv](https://arxiv.org/abs/2408.05952)