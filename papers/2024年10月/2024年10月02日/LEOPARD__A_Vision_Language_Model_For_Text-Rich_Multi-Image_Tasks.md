# LEOPARD：一款专为文本密集型多图像任务设计的视觉语言模型

发布时间：2024年10月02日

`LLM应用` `图像处理`

> LEOPARD : A Vision Language Model For Text-Rich Multi-Image Tasks

# 摘要

> 文本丰富的图像在现实应用中无处不在，如演示文稿和网页快照，其中文本是引导理解的关键。处理多个此类图像的任务尤为复杂，不仅需理解单个图像，还需推理图像间的逻辑关系。当前的多模态大型语言模型（MLLM）面临两大挑战：高质量多图像数据集的稀缺和图像分辨率与特征长度的平衡难题。为此，我们推出了\OurMethod，专为处理多文本图像的视觉语言任务设计。我们精心策划了百万级高质量多模态数据，并开发了自适应高分辨率编码模块，动态优化视觉序列长度。实验结果显示，我们的模型在多文本图像任务中表现卓越，并在通用领域评估中亦表现出色。

> Text-rich images, where text serves as the central visual element guiding the overall understanding, are prevalent in real-world applications, such as presentation slides, scanned documents, and webpage snapshots. Tasks involving multiple text-rich images are especially challenging, as they require not only understanding the content of individual images but reasoning about inter-relationships and logical flows across multiple visual inputs. Despite the importance of these scenarios, current multimodal large language models (MLLMs) struggle to handle such tasks due to two key challenges: (1) the scarcity of high-quality instruction tuning datasets for text-rich multi-image scenarios, and (2) the difficulty in balancing image resolution with visual feature sequence length. To address these challenges, we propose \OurMethod, a MLLM designed specifically for handling vision-language tasks involving multiple text-rich images. First, we curated about one million high-quality multimodal instruction-tuning data, tailored to text-rich, multi-image scenarios. Second, we developed an adaptive high-resolution multi-image encoding module to dynamically optimize the allocation of visual sequence length based on the original aspect ratios and resolutions of the input images. Experiments across a wide range of benchmarks demonstrate our model's superior capabilities in text-rich, multi-image evaluations and competitive performance in general domain evaluations.

[Arxiv](https://arxiv.org/abs/2410.01744)