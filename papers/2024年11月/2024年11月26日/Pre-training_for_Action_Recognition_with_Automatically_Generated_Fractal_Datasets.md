# 利用自动生成的分形数据集进行动作识别的预训练

发布时间：2024年11月26日

`其他` `计算机视觉` `视频处理`

> Pre-training for Action Recognition with Automatically Generated Fractal Datasets

# 摘要

> 近年来，合成数据备受关注，尤其是在对图像模态进行预训练以支持诸如对象分类、医学成像等一系列计算机视觉任务的情境下。以往研究表明，通过各种生成流程自动产出的合成样本能够取代真实样本，并生成强大的视觉表征。此方法解决了真实数据存在的诸如采集和标注成本、版权及隐私等问题。
  我们将这一趋势拓展至视频领域，并应用于动作识别任务。借助分形几何，我们给出了自动生成大规模短合成视频片段数据集的方法，这些数据集可用于预训练神经模型。生成的视频片段具有显著的多样性，这源于分形生成复杂多尺度结构的天然能力。为缩小领域差距，我们进一步明确了真实视频的关键属性，并在预训练时精心模拟。通过全面的消融实验，我们确定了能强化下游结果的属性，并为利用合成视频进行预训练提供了通用指南。通过在已有的动作识别数据集 HMDB51 和 UCF101 以及另外四个与群体动作识别、细粒度动作识别和动态场景相关的视频基准上对预训练模型进行微调，对所提出的方法予以评估。与标准的 Kinetics 预训练相比，我们所报告的结果接近，甚至在部分下游数据集上更出色。代码和合成视频样本可在 https://github.com/davidsvy/fractal_video 获取。

> In recent years, interest in synthetic data has grown, particularly in the context of pre-training the image modality to support a range of computer vision tasks, including object classification, medical imaging etc. Previous work has demonstrated that synthetic samples, automatically produced by various generative processes, can replace real counterparts and yield strong visual representations. This approach resolves issues associated with real data such as collection and labeling costs, copyright and privacy.
  We extend this trend to the video domain applying it to the task of action recognition. Employing fractal geometry, we present methods to automatically produce large-scale datasets of short synthetic video clips, which can be utilized for pre-training neural models. The generated video clips are characterized by notable variety, stemmed by the innate ability of fractals to generate complex multi-scale structures. To narrow the domain gap, we further identify key properties of real videos and carefully emulate them during pre-training. Through thorough ablations, we determine the attributes that strengthen downstream results and offer general guidelines for pre-training with synthetic videos. The proposed approach is evaluated by fine-tuning pre-trained models on established action recognition datasets HMDB51 and UCF101 as well as four other video benchmarks related to group action recognition, fine-grained action recognition and dynamic scenes. Compared to standard Kinetics pre-training, our reported results come close and are even superior on a portion of downstream datasets. Code and samples of synthetic videos are available at https://github.com/davidsvy/fractal_video .

[Arxiv](https://arxiv.org/abs/2411.17584)